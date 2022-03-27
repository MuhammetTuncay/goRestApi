# goRestApi

POST localhost:3200/todos todo oluşturur (insert)

{
    "Detail":"Go da bir numara olana kadar çalışacağım!",
    "Completed":false
}

GET localhost:3200/todos tüm todoları çeker (select)

PUT localhost:3200/todos/5/complete todoları tamamlandıya çeker (update)

PUT localhost:3200/todos/5/uncomplete todoları tamamlanmadıya çeker (update)

DELETE localhost:3200/todos/5 todoyu siler (delete)
