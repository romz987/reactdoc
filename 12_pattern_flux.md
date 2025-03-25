Flux-паттерн в контексте Redux

    Action – объект, который описывает, что произошло (например, { type: 'ADD_ITEM', payload: item }).
    Dispatcher (в Redux это dispatch) – отправляет action в хранилище (store).
    Store – центральное место, где хранится состояние.
    Reducer – чистая функция, которая обновляет state в зависимости от action.
    View (React-компоненты) – подписываются на store и получают актуальное состояние через useSelector().
