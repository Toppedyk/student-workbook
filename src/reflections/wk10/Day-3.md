05/19/2021
Afternoon Link: https://github.com/Toppedyk/castles-cs

In a SQL table, what is the difference between information in a row and information in a column?
the row is a single object and a column is one variable for all objects

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters (
  name VARCHAR(255),
  age VARCHAR(255),
  description VARCHAR(255),
  id int AUTO_INCREMENT,


PRIMARY KEY(id)
)

What is the difference between the following statements:
delete from deletes a certain instance or instances from the table but drop deletes the entire table. 