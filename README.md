# WebBND
Руты для UI (были созданы только для нормальной работы фронта):
https://tima-app.herokuapp.com/users/list - весь список users
https://tima-app.herokuapp.com/users/new - добавить 
https://tima-app.herokuapp.com/users/add2 - добавить 
https://tima-app.herokuapp.com/users/edit/{id} - редактировать
https://tima-app.herokuapp.com/users/update/{id} - редактировать
https://tima-app.herokuapp.com/users/delete/{id} - удалить

Основные руты:
https://tima-app.herokuapp.com/users/all - GET возвращает JSON всех users
https://tima-app.herokuapp.com/users/add - POST добовляет user {firstName, secondName, emailId}
https://tima-app.herokuapp.com/users/{id} - GET возвращает JSON user
https://tima-app.herokuapp.com/users/{id} - PUT редактирует user
https://tima-app.herokuapp.com/users/{id} - DELETE удаляет user

В качестве DB использовался postgreSQL
