Первая лаба:

1) Выберите из таблицы orders все заказы

   
![image](https://github.com/user-attachments/assets/ebdbfae2-ec2f-47eb-8656-98ed6774c9ab)

2) Выберите из таблицы orders все заказы кроме новых. 
У новых заказов status равен "new". Использовать in
   ![image](https://github.com/user-attachments/assets/a58f9a0d-4a17-4d46-a749-7d944637d798)

3) Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".

  ![image](https://github.com/user-attachments/assets/cef07c92-d10f-488a-a2dd-0732f816b8a4)

4) Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count).
Вывести нужно только номер (id) и сумму (sum) заказа.

![image](https://github.com/user-attachments/assets/11959c64-1e16-4d67-a962-0c5e45fe4714)



Вторая лаба:

1) Выберите из таблицы orders 3 самых дешевых заказа за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/ef4864c1-ccd4-4d9b-84df-cec5e0f6eee2)


2) Выберите из таблицы orders 2 самых дорогих заказов за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/6b7d7ed7-7168-441e-8674-a9dff5aa4457)


3) Добавьте в таблицу orders данные о новом заказе стоимостью 8000 рублей. В заказе 4 товара (products).

   ![image](https://github.com/user-attachments/assets/f0b7fe57-6c94-441e-9ff2-91ee55aec109)

![image](https://github.com/user-attachments/assets/cb894435-f384-49df-9a1a-35296fff1a52)


4) Добавьте в таблицу products новый товар — «VR-очки», стоимостью 70000 рублей в количестве (count) 2 штук.

   ![image](https://github.com/user-attachments/assets/b9d23143-30df-4c85-8e4a-1ba151d82b4f)

![image](https://github.com/user-attachments/assets/83cdec71-1cbc-4171-98df-3f4edd185509)

5) В таблицу products внесли данные с ошибкой, вместо "PS5" в наименовании написали IMAC. Исправьте ошибку.

   ![image](https://github.com/user-attachments/assets/f903e5f0-fe00-4fc5-846d-8d425beb2343)

   ![image](https://github.com/user-attachments/assets/267b0963-015c-47ea-b9c4-fa411901e773)

Шпоры: 
INSERT INTO table (column1, column2) VALUES (value1, value2);
 Добавление одной записи
 
INSERT INTO table (column1, column2) VALUES (value11, value12), (value21, value22), ...
 Добавление нескольких записей
 
INSERT INTO table1 (column1, column2) SELECT (col1, col2) FROM table2;
 Добавление записей из другой таблицы
 
UPDATE table1 SET column1 = new value;
 Обновление поля во всех записях
 
UPDATE table1 SET column1=new_value column2=new_value WHERE condition;
 Обновление поля во записях, соответствующих условию
 
 DELETE FROM table; Удаление всех записей
 
 DELETE FROM table WHERE condition; Удаление записей, соответствующих условию
