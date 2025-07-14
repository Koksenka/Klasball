# Домашнее задание к занятию "`Кластеризация и балансировка нагрузки MoskalenkoVV`" 


### Задание 1

- Запустите два simple python сервера на своей виртуальной машине на разных портах
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

### Решение

![alt text](https://github.com/Koksenka/Klasball/blob/master/1.png)

https://github.com/Koksenka/Klasball/blob/master/haproxy1.cfg
---

### Задание 2

- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

### Решение

![alt text](https://github.com/Koksenka/Klasball/blob/master/2.png)

https://github.com/Koksenka/Klasball/blob/master/haproxy2.cfg