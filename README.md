# dz9_security
По секьюрити:


ДЗ

Реализовать приложение с разделением прав доступа  
АПИ:
* public/api - доступ разрешен для всех
* admin/api - доступ разрешен для пользователей с ролью admin
* support/api - доступ разрешен для пользователей  с ролью support  
Все приватные АПИ должны возвращать имя и роль пользователя - [UserController.java](https://github.com/shiriaeva/dz9_security/blob/main/dz9_security/src/main/java/com/example/aspects_and_security/controller/UserController.java)    
Хранение пользователей в памяти приложения (использование InMemoryUserDetailsManager)  |  
Для хеширования паролей использовать BCryptPasswordEncoder  | - [WebSecurityConfig.java](https://github.com/shiriaeva/dz9_security/blob/main/dz9_security/src/main/java/com/example/aspects_and_security/config/security/WebSecurityConfig.java)  
Basic аутентификация                                        |   

* public/api:  
![](https://github.com/shiriaeva/dz9_security/blob/main/dz9_security/src/screenshots/1.png)
* admin/api - без авторизации:  
![](https://github.com/shiriaeva/dz9_security/blob/main/dz9_security/src/screenshots/2.png)
* admin/api - с авторизацией:  
![](https://github.com/shiriaeva/dz9_security/blob/main/dz9_security/src/screenshots/3.png)
* support/api - с авторизацией:  
![](https://github.com/shiriaeva/dz9_security/blob/main/dz9_security/src/screenshots/4.png)
