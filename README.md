# Java Online Marathon
## To-Do List Project
Для розгортання бази даних встановіть параметр
spring.jpa.hibernate.ddl-auto=create
в файлі 
application.properties

Під час старту проекту база даних автоматично буде заповенена тестовими даними, що є в файлі data.sql 


У базі збережено трьох користувачів з ролями ADMIN та USER.

| Логін         | Пароль | Роль  |
| ------------- |:------:|:-----:|
| mike@mail.com | 1111   | ADMIN |
| nick@mail.com | 2222   | USER  |
| nora@mail.com | 3333   | USER  |

Користувач з роллю ADMIN має повний доступ до всіх ресурсів.
