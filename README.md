# SergeiAvchinnikov_microservices
SergeiAvchinnikov microservices repository
## **Оглавление:**
- [Docker контейнеры. Docker под капотом (docker-2)](#docker-2)
- [Docker-образы. Микросервисы. (docker-3)](#docker-3)
- [Сетевое взаимодействие Docker контейнеров. Docker Compose. Тестирование образов. (docker-4)](#docker-4)


## <a name="docker-2"></a>Docker контейнеры. Docker под капотом (docker-2)
+ устанавливаем докер
+ запускаем контейнеры изучаем команды
+ создаем первый образ через docker commit, продолжаем узучать команды
+ устанавливаем и настраиваем GCloud SDK
+ устанавливаем docker-machine
+ собираем образ с помощью Dockerfile, запускаем контейнер и проверяем
+ регистрируемся на DockerHub, пушим туда образы, учимся работать с образами из DockerHub

## <a name="docker-3"></a>Docker-образы. Микросервисы. (docker-3)
+ разбиваем приложение на микросервисы, собираем образы
+ запускаем контейнеры с микросервисами на docker-machine, проверяем
+ учимся уменьшать образ, проверяем результат
+ учимся создавать и подключать volume, проверяем результат

## <a name="docker-4"></a>Сетевое взаимодействие Docker контейнеров. Docker Compose. Тестирование образов. (docker-4)
+ упражняемся в работе с сетями в Docker
+ установка docker-compose
+ работа с docker-compose
+ базовое имя проекта
  + автоматически создается по имени папки в которой расположен docker-compose.yml
  + можно установить через  переменную окружения `export COMPOSE_PROJECT_NAME=foo`
  + или параметром `-p` при вызове : `docker-compose -p foo build`
