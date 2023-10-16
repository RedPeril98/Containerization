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

![](![1](https://github.com/RedPeril98/Containerization/blob/main/1.jpg)
)

Добавляем содержимое файлa compose.yaml:

 ![](![2](https://github.com/RedPeril98/Containerization/blob/main/2.jpg)
)

Запускаем .yaml файл

sudo docker-compose up

![](![3](https://github.com/RedPeril98/Containerization/blob/main/3.jpg)
)

![](![4](https://github.com/RedPeril98/Containerization/blob/main/4.jpg)
)

![](![5](https://github.com/RedPeril98/Containerization/blob/main/5.jpg)
)
