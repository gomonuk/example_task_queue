Краткое описание методов:
- make_task - вызов API, при обращении к которому создается задача, которая добавляется в очередь, и пользователю возвращается номер задачи.
- get_status - вызов API возвращает статус задачи в формате json {'status:'', 'create_time":'', 'start_time':'', 'time_to_execute':''}. Статусы:
   - In Queue     - задача ждёт своей очереди на выполнение; 
   - Run          - произошел запуск задачи;
   - Completed    - задача выполнена.
