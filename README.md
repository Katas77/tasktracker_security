# Task Tracker
## Обзор:
### "Task tracker" — это небольшое консольное приложение, построенное на архитектуре Representational State Transfer (REST).
### Оно реализует написание контроллеров с использованием Mono и Flux, а также работу с MongoDB в реактивном стиле.
## Возможности:
### Приложение предоставляет следующие функции:
- Работа с пользователями:
поиск всех пользователей
- Поиск пользователя по ID
- Создание пользователя
- Обновление информации о пользователе
- Удаление пользователя по ID
- Работа с задачами:
- Поиск всех задач
- Поиск конкретной задачи по ID
- Создание задачи
- Обновление задачи
- Назначение наблюдателя задаче
- Удаление задачи по ID
- Безопасность:
  ## Доступ к различным операциям ограничен ролями пользователей:
- Получение, обновление и удаление профилей пользователей доступны только клиентам с одной из ролей: ROLE_USER, ROLE_MANAGER.
- Получение списка задач, получение задачи по ID и назначение наблюдателей доступны пользователям с одной из ролей: ROLE_USER, ROLE_MANAGER.
- Создание, обновление и удаление задач доступно только пользователям с ролью ROLE_MANAGER.
  ## Требования:
- Java 22
- Maven (для сборки приложения)
- Spring Boot 3.2.3
- Docker Desktop
## Установка и настройка:
- Клонируйте репозиторий: git clone https://github.com/Katas77
- Перейдите в директорию проекта:
- Соберите приложение с помощью Maven:
## Для общего использования:
- Запустите и настройте базу данных через ### Чтобы  создать образ Docker и запустить контейнер, выполните следующие команды:
```bash
cd docker
```
```bash
docker-compose up
```
## Использованные технологии:
- Java
- Spring Boot
- Docker
- Spring-boot-starter-webflux
- Mongodb-reactive
- Spring Security
## Обратная связь:
____
✉ Почта для обратной связи:
<a href="">krp77@mail.ru</a>
