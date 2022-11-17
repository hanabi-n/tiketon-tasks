# tiketon-tasks

Цель репозитория
======
Этот репозиторий является ответом на задания от tiketon.

Задача №1
------
  Написать на HTML образ билета

В этой задаче, я использовала HTML и CSS

![Screenshot 2022-11-17 at 22-46-10 tiketon-task-1](https://user-images.githubusercontent.com/53466808/202507424-70ea3753-0990-4e00-aa74-557f72297bd9.png)

Задача №2
------
Развернуть виртуальную машину в Linux, запустить любой сервер

В этой задаче, я подняла веб сервер Nginx. Для этого:
1. Установила на виртуальную машину Nginx:

![1](https://user-images.githubusercontent.com/53466808/202527105-1636c968-0f56-4dc8-b754-2e7da315e92b.png)

2. В файле /etc/nginx/conf.d/jojosite.local.conf написала контекст server. Он нужен для работы с сервером:

![4](https://user-images.githubusercontent.com/53466808/202527838-66b6ccaa-e790-4c71-9e3e-eee93c2f5fa7.png)

3. Перезапустила Nginx;
4. Создала index.html. Это наш сайт, который будет на сервере nginx. В этом сайте будет надпись "This is site to watch JOJO (used Nginx)":

![7](https://user-images.githubusercontent.com/53466808/202529533-780d212e-5033-4864-afe6-63cecec3e315.png)

5. Если парсить сайт (если это GUI виртуальная машина, то можно открыть браузер для красивого оутпута):

![8](https://user-images.githubusercontent.com/53466808/202529805-2de64fa4-b744-4337-96fa-09ab514de275.png)
