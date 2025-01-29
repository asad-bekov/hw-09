
# Домашнее задание к занятию «Кеширование Redis/memcached»
*Асадбеков Асадбек*

## Задание 1 Кеширование

Приведите примеры проблем, которые может решить кеширование.

### Ответы:

**Примеры проблем, которые решает кеширование:**

**1. Снижение нагрузки на базу данных** – часто запрашиваемые данные можно хранить в кеше, чтобы не делать повторные запросы в БД.

**2. Ускорение загрузки страниц** – кеширование статического контента (CSS, JS, HTML) помогает быстрее загружать веб-страницы.

**3. Оптимизация работы API** – ответы на API-запросы можно временно сохранять, чтобы избежать лишних вычислений и сетевых запросов.

**4. Экономия ресурсов сервера** – кеширование уменьшает потребление процессора и оперативной памяти за счёт меньшего количества вычислений.

**5. Защита от DDoS-атак** – кеширование помогает снизить нагрузку при массовых запросах на сервер, предоставляя уже сохранённые данные.Добавление двух хостов в Zabbix и привязка шаблонов.  

## Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*

![alt text](https://github.com/asad-bekov/hw-09/blob/main/img/1.png)

## Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*

![alt text](https://github.com/asad-bekov/hw-09/blob/main/img/3.png)

## Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями.

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

![alt text](https://github.com/asad-bekov/hw-09/blob/main/img/4.png)
![alt text](https://github.com/asad-bekov/hw-09/blob/main/img/5.png)

## Задание 5*. Работа с числами

Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*

![alt text](https://github.com/asad-bekov/hw-09/blob/main/img/6.png)