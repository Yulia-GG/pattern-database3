# Домашнее задание к занятию "Репликация и масштабирование. Часть 1" - Юлия Гриб

### Задание 1.

На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.   

master-slave - master для записи и чтения,  slave будет только для чтения, создали реплику из которой только берем данные, т.о. распределяем нагрузку чтения.
master-master - позволяет копировать данные с одного сервера на другой, на любой сервер можно писать данные.

### Задание 2.

Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/1.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/2.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/3.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/4.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/5.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/6.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/7.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/8.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/9.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/10.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/11.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/12.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/13.png)

![image](https://github.com/Yulia-GG/pattern-database3/blob/main/14.png)

