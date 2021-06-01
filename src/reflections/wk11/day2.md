05/25/2021
Afternoon Link:https://github.com/Toppedyk/jobs

What is the difference between a primary key and a foreign key:
primary key is like the id of the component and foreign key refers to another component/table

What is an Alias? a temporary version of the table used on joining tables

Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
SELECT * FROM doctors dp
INNER JOIN patients p ON p.id = dp.patientId
INNER JOIN doctors d ON d.id = dp.doctorId;


CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

