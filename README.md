## Service Layer Pattern:

В классе TaskService выделен слой сервисов, который отвечает за выполнение бизнес-логики. Это помогает разделить ответственности между слоями приложения и обеспечивает модульность кода.
Repository Pattern:

В интерфейсе TaskRepository и его реализации используется репозиторий для работы с базой данных. Это позволяет абстрагировать доступ к данным и обеспечивает удобство при изменении источника данных.
## Factory Method Pattern:

В методе addTask класса TaskService используется фабричный метод для создания экземпляра задачи с определенными параметрами. Это делает процесс создания задачи более гибким и позволяет изолировать детали создания объектов.
## Strategy Pattern:

В методе updateStatus класса TaskService используется стратегия для изменения статуса задачи в зависимости от текущего статуса. Это позволяет легко добавлять новые варианты поведения без изменения существующего кода.
 ## Null Object Pattern:

В методе updateStatus также используется объект-заглушка для предотвращения ошибок при попытке обращения к нулевым объектам. Это повышает надежность приложения и делает его более стабильным.
