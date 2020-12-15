# <a href="https://github.com/SeniorIgor/Hacker-News-Docker/blob/master/README.md#-hacker-news-docker"></a> Hacker-News-Docker
### Hacker-News-Docker - копия проекта <a href="https://github.com/SeniorIgor/Hacker-News#-hacker-news">Hacker-News</a> с конфигурацией сборки в Docker image.

1. Приложение разработано с использованием React и Redux. 
2. Реализован бэкенд для хостинга статики и API для инкапсуляции внешних запросов на Node.JS. 
3. Создана конфигурация сборки проекта в Docker image.

---

### Prerequisites

In order to run this application you need to install two tools: **Docker** & **Docker Compose**.

Instructions how to install **Docker** on [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/), [Windows](https://docs.docker.com/docker-for-windows/install/), [Mac](https://docs.docker.com/docker-for-mac/install/).

**Docker Compose** is already included in installation packs for *Windows* and *Mac*, so only Ubuntu users needs to follow [this instructions](https://docs.docker.com/compose/install/).


### How to run it?

The entire application can be run with a single command on a terminal:

```
$ docker-compose up --build
```

If you want to stop it, use the following command:

```
$ docker-compose down
```

---
