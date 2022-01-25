## Crowdfunding

Клиент-серверное приложение на микросервисной архитектуре в области краудфандинга. Наша команда занималась разработкой базовой реализации краудфандингового сервиса, список дополнительных фич ещё ждёт своей реализации.
Основная идея заключается в разработке платформы для коллективного сотрудничества людей, которые добровольно объединяют свои деньги или другие ресурсы для поддержки интересных им проектов.

### Состоит из трёх микросервисов:

`auth` - отвечает за аутентификацию и авторизацию пользователей, выдачу токенов, хранит личные данные пользователей.

`client` - центральный микросервис. Содержит в себе основную бизнес-логику приложения: обработка информации о проектах и пользователях, передача данных на фронт.

`tran` - финансовый микросервис. Отвечает за все финансовые операции в приложении: создание кошельков пользователей и проектов, перемещение средств внутри приложения, ввод и вывод денежных средств.


### Список основных технологий, использованных в данном проекте: 
+ Java 8 
+ Spring Boot 
+ Spring Security 
+ Spring Data Jpa
+ PostgreSQL
+ Maven
+ Git
+ JWT

#### Тесты:
+ Spring Boot Test
+ Mockito
+ JUnit
+ Hamcrest
+ AssertJ