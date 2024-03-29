# Part 1. Готовый докер

В качестве конечной цели своей небольшой практики вы сразу выбрали написание докер образа для собственного веб сервера, а потому в начале вам нужно разобраться с уже готовым докер образом для сервера. Ваш выбор пал на довольно простой nginx.

## == Задание ==
	
	- 1 Взять официальный докер образ с nginx и выкачать его при помощи docker pull
	- 2 Проверить наличие докер образа через docker images
	- 3 Запустить докер образ через docker run -d [image_id|repository]
	- 4 Проверить, что образ запустился через docker ps

![img](/src/img/1.png)

	- 5 Посмотреть информацию о контейнере через docker inspect [container_id|container_name]
	- 6 По выводу команды определить и поместить в отчёт размер контейнера, список замапленных портов и ip контейнера

![img](/src/img/4.png)
![img](/src/img/2.png)
![img](/src/img/3.png)

	- 7 Остановить докер образ через docker stop [container_id|container_name]
	- 8 Проверить, что образ остановился через docker ps

![img](/src/img/5.png)

	- 9 Запустить докер с замапленными портами 80 и 443 на локальную машину через команду run

![img](/src/img/8.png)

	- 10 Проверить, что в браузере по адресу localhost:80 доступна стартовая страница nginx

![img](/src/img/6.png)

	- 11 Перезапустить докер контейнер через docker restart [container_id|container_name]
	- 12 Проверить любым способом, что контейнер запустился

![img](/src/img/7.png)