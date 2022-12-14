# database-design

Лабораторная работа 1. Проектирование архитектуры БД

Задачи: 
1. Провести анализ функционала сайта или портала в выбранной предметной области с позиции работы с данными, выделить сущности, их атрибуты и связи между сущностями.
2. Спроектировать архитектуру БД для выбранной темы в виде ER-diagram в нотации IDEF1X или UML.
![image](https://user-images.githubusercontent.com/24692953/198312072-fba3d289-fdb1-4999-a110-16ebceaabf2b.png)

Обоснование нахождения модели данных в 3НФ:

1НФ - в таблице нет дублирующих строк, в каждой ячейке таблицы хранится атомарное значение (одно не составное значение), в столбце хранятся данные одного типа, отсутствуют массивы и списки в любом виде

2НФ – таблица находится в первой нормальной форме, у таблиц есть ключи, все неключевые столбцы таблицы должны зависят от полного ключа (в случае если он составной)

3НФ - ни один неключевой столбец не зависит от другого неключевого столбца

В данной ER диаграмме соблюдены все вышеперечисленные требования, значит модель данных находится в 3НФ.




Лабораторная работа 2. Создание таблиц в PostgreSQL

Задачи: 
1. На основе спроектированной ER-diagram из 1 лабораторной создать таблицы.
2. Заполнить таблицы данными, минимум по 15 записей в основных таблицах.
Команды, которые использовались: CREATE DATABASE, INSERT, добавление данных из файла
![image](https://user-images.githubusercontent.com/24692953/198313061-6070e0f5-69d5-479a-b007-b8753b2939d0.png)


Лабораторная работа 3 Создание представления и индексов в PostgreSQL

Задача:
Создать представление и индексы к нескольким таблицам (минимум к двум).

![image](https://user-images.githubusercontent.com/24692953/198313713-9ead0a32-3043-40b5-b88c-6dee1a329e51.png)
![image](https://user-images.githubusercontent.com/24692953/198313808-ed9c046b-f4a2-4c72-86f1-d169a81e59bf.png)
