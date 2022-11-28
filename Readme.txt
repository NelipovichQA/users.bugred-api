Коллекция запросов для тестирования API сайта http://users.bugred.ru/

Тестирование API проводилось в Postman. 
Документация по API для данного сайта находится по адресу https://testbase.atlassian.net/wiki/spaces/USERS/overview
Вход в конфлюинс: 
логин: mail.for.testbase@gmail.com     
пароль: 1234567891011

Во время тестирования были использованы следующие запросы:
- doRegister  (регистрация нового пользователя в системе)
- createCompany  (создание новой компании)
- createUser  (создание нового пользователя)
- deleteUser  (удаление пользователя)
- createUserWithTasks  (создание пользователя с заданными видами работ)

Согласно документации вышеперечисленные запросы использовали метод POST.


Возможные запросы REST:

{"resources":[{"name_method":"deletetask","url":"http:\/\/users.bugred.ru\/tasks\/rest\/deletetask"},
{"name_method":"addtaskincron","url":"http:\/\/users.bugred.ru\/tasks\/rest\/addtaskincron"},
{"name_method":"updatetask","url":"http:\/\/users.bugred.ru\/tasks\/rest\/updatetask"},
{"name_method":"deleteuser","url":"http:\/\/users.bugred.ru\/tasks\/rest\/deleteuser"},
{"name_method":"dologin","url":"http:\/\/users.bugred.ru\/tasks\/rest\/dologin"},
{"name_method":"getcompany","url":"http:\/\/users.bugred.ru\/tasks\/rest\/getcompany"},
{"name_method":"getuser","url":"http:\/\/users.bugred.ru\/tasks\/rest\/getuser"},
{"name_method":"getuserfull","url":"http:\/\/users.bugred.ru\/tasks\/rest\/getuserfull"},
{"name_method":"addavatar","url":"http:\/\/users.bugred.ru\/tasks\/rest\/addavatar"},
{"name_method":"deleteavatar","url":"http:\/\/users.bugred.ru\/tasks\/rest\/deleteavatar"},
{"name_method":"createuserwithtasks","url":"http:\/\/users.bugred.ru\/tasks\/rest\/createuserwithtasks"},
{"name_method":"magicsearch","url":"http:\/\/users.bugred.ru\/tasks\/rest\/magicsearch"},
{"name_method":"createuser","url":"http:\/\/users.bugred.ru\/tasks\/rest\/createuser"},
{"name_method":"fullupdateuser","url":"http:\/\/users.bugred.ru\/tasks\/rest\/fullupdateuser"},
{"name_method":"useronefield","url":"http:\/\/users.bugred.ru\/tasks\/rest\/useronefield"},
{"name_method":"list","url":"http:\/\/users.bugred.ru\/tasks\/rest\/list"},
{"name_method":"doregister","url":"http:\/\/users.bugred.ru\/tasks\/rest\/doregister"},
"name_method":"createcompany","url":"http:\/\/users.bugred.ru\/tasks\/rest\/createcompany"},
{"name_method":"createtask","url":"http:\/\/users.bugred.ru\/tasks\/rest\/createtask"}]}