# Java-Filmorate
### Стек:
- Java 11
- Spring Boot
- PostgreSQL
- JDBC
- Maven
- Lombok
- JUnit 5

# Описание проекта
Бэкэнд приложения для поиска подходящих к просмотру фильмов, а также для коммуникации между пользователями.
Пользователи могут добавлять друг друга в друзья, оставлять комментарии к фильмам и рекомендовать фильмы друг другу.
Чтобы помочь пользователям следить за новостями на платформе, добавлена лента событий.
Также добавлен поиск - по ключевому слову из названия или описания фильма.

# Команда
## Большое спасибо членам команды, с которыми я имел возможность работать на этом проекте!
### GitHub:
* [OrionSleeve](https://github.com/OrionSleeve)
* [Nucleus1337](https://github.com/Nucleus1337)
* [AndreiSmazin](https://github.com/AndreiSmazin)
* [Buhanzaz](https://github.com/Buhanzaz)

## Функционал приложения

### Фильмы

- Создание фильма
- Обновление фильма
- Получение фильма по ID
- Добавление лайка фильму
- Добавление дизлайка фильму
- Получение списка самых популярных фильмов
- Удаление фильма

### Пользователи

- Добавление пользователя
- Обновление пользователя
- Получение списка всех пользователей
- Получение пользователя по ID
- Добавление пользователя в друзья
- Удаление пользователя из друзей
- Получение списка друзей пользователя
- Получение списка общих друзей
- Удаление пользователя

### Жанры

- Получение списка всех жанров
- Получение жанра по ID
- 
### Возрастной рейтинг

- Получение возрастного рейтинга по его ID
- Получение всех возрастных рейтингов

## Тестирование

Функциональность приложения была протестирована при помощи библиотеки JUnit 5.

## Запуск приложения

Чтобы запустить это приложение, выполните следующие шаги:

1. Скачайте репозиторий на компьютер: git pull https://github.com/Alex-Naumenko1986/java-filmorate-group.git
2. Перейдите в папку с проектом: cd java_filmorate_group
3. Cоздайте jar файлы: mvn package
4. Перейдите в папку target: cd target
5. Запустите приложение командой: java -jar filmorate-0.0.1-SNAPSHOT.jar
   
## Диаграмма базы данных
![Database diagram](/DBDiogram.png)

### Примеры запросов
1. Получение пользователя с  ID = 1:
```sql
   SELECT *  
   FROM users  
   WHERE user_id = 1;
```
2. Получение фильма с ID = 10:
```sql
   SELECT *  
   FROM films  
   WHERE film_id = 10.
```
