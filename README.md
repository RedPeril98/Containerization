# Контейнеризация (семинары)

## *Урок 5.*   Docker Compose и Docker Swarm

**Задание:** 1 создать сервис, состоящий из 2 различных контейнеров: 1 - веб, 2 - БД (compose) выводы зафиксировать  
Задание со звездочкой - повышенной сложности..  
** не обязательно 2) необходимо создать 3 сервиса в каждом окружении (dev, prod, lab)  
** не обязательно 3) по итогу на каждой ноде должно быть по 2 работающих контейнера

**Решение:**

 Создаем директорию compose, через редактор nano добавляем файл compose.yaml:

 mkdir compose  
 cd compose/  
 nano compose.yaml  

![](![1](https://github.com/RedPeril98/Containerization/assets/120703806/e5a6a898-a3ee-4171-a66b-3ca9851028e4)
)

Добавляем содержимое файлa compose.yaml:

 ![](![2](https://github.com/RedPeril98/Containerization/assets/120703806/25640f3a-14ef-4451-b570-673ed840ac5b)
)

Запускаем .yaml файл

sudo docker-compose up

![](![3](https://github.com/RedPeril98/Containerization/assets/120703806/85ec8f44-348b-4b76-be30-994025e3b88d)
)

![](![4](https://github.com/RedPeril98/Containerization/assets/120703806/9daea684-a858-451c-9cf3-843e39f0ef2f)
)

![](![5](https://github.com/RedPeril98/Containerization/assets/120703806/3f77305b-dd18-477f-963e-cd6a95f1209d)
)
