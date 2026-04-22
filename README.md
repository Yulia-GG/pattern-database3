# Домашнее задание к занятию "Репликация и масштабирование. Часть 1" - Юлия Гриб

### Задание 1.

На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.   

master-slave - master для записи и чтения,  slave будет только для чтения, создали реплику из которой только берем данные, т.о. распределяем нагрузку чтения.
master-master - позволяет копировать данные с одного сервера на другой, на любой сервер можно писать данные.

### Задание 2.

Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

```
SELECT COUNT(film_id) 
FROM film 
WHERE length > (SELECT AVG(length) FROM film);
```

![image](https://github.com/Yulia-GG/pattern-database2/blob/main/задание2.png)

## Дополнительные задания (со звездочкой*)

### Задание 3*.

Выполните конфигурацию master-master репликации. Произведите проверку.

```sql
SELECT staff_id, COUNT(rental_id),
IF(COUNT(rental_id) > 8000, 'Да', 'Нет') AS Премия
FROM payment
GROUP BY staff_id;
```

![image](https://github.com/Yulia-GG/pattern-database2/blob/main/задание4.png)
