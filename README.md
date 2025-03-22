# MYSQL
<h1> Exercise 1  </h1>
<h4> Content : Create, Use, Drop, Insert, Select, Update, Delete, Not Null, Default, Primary Key, Auto Increment, Alias, Where </h4>

<p>
  
  Create Database : create database bank_db;
  Create Table : create table emp( emp_id int, name varchar(50), desig varchar(50), dept varchar(50) );
  Use : Use bank_db;
  Drop : DROP bank_db;
  Insert : insert into emp(emp_id,name,desig,dept) values (101,"Raju","manger","Loan"),(102,"Sham","Casier","Cash"),(103,"Paul","Associate","Loan"),(104,"Alex","Accountant","Account");
  Select : Select * from emp;
  Update : Update emp set desig = "IT" where emp_id=103;
  Delete : Delete from emp where emp_id = 103;
  Not Null : create table emp( emp_id int Not Null, name varchar(50) Not Null );
  Defult : create table emp( emp_id int Not Null, name varchar(50) Not Null, desig varchar(50) Not Null default "Probation", dept varchar(50) Not Null );
  Primary Key : create table emp( emp_id int Primary Key, name varchar(50) Not Null, desig varchar(50) Not Null default "Probation", dept varchar(50) Not Null );
  Auot Increment : create table emp( emp_id int Primary Key auto_increment, name varchar(50) Not Null, desig varchar(50) Not Null default "Probation", dept varchar(50) Not Null );
  Alias : Select acc_no AS "Account_no." from emp;
  Where : Select emp_id,name from emp where desig="manger"; , Update emp set desig = "IT" where emp_id=103; , Delete from emp where emp_id = 103;
  
</p>
