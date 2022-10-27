# Java-taskTracker. Трекер задач.
![Java](https://img.shields.io/badge/-Java-green) ![Spring](https://img.shields.io/badge/-Spring-blue)![Postgres SQL](https://img.shields.io/badge/-Postgres%20SQL-brightgreen) ![H2](https://img.shields.io/badge/-H2-green) ![Maven](https://img.shields.io/badge/-Maven-yellowgreen) ![Lombok](https://img.shields.io/badge/-Lombok-lightgrey) ![JDBC](https://img.shields.io/badge/-JDBC-green) ![Git](https://badgen.net/badge/icon/github?icon=github&label)
## Учебный проект.


### Описание:

REST приложение на основе Java Core для организации работы над задачами. Не скромно говоря - аналог Jira

Приложение имеет следующую модель:
![Alt text](https://github.com/Gidrosliv/java-TaskManager/blob/main/schema.png?raw=true)

Задачи могут быть трёх типов: 
обычные задачи
эпики (сложные задачи)
подзадачи.

этапы жизни задачи: 
NEW — задача только создана, но к её выполнению ещё не приступили. 
IN_PROGRESS — над задачей ведётся работа. 
DONE — задача выполнена. 
        
### Схема работы API:
    
![Alt text](https://github.com/Gidrosliv/java-TaskManager/blob/main/schema%20API.png?raw=true)

#### Функциональность:
*  добавление и хранение данных в памяти;
*  добавление и хранение данных в файле;
*  доступ к данным через локальный сервер, проверяющий ключ доступа;
*  доступ к методам менеджера через HTTP-запросы.
