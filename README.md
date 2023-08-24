THIS IS BASIC MYSQL PROJECT 










CREATE DATABASE PROJECT_DB; 
use project_db;

create table customer(c_id int , c_name varchar(50),c_city varchar(45), c_phone int,c_gender char(1),
c_order_name varchar(55));
describe customer;

insert into customer 
values
 (101,"shweta","pratapgarh",3226565,"F","lotus cream"),
(102,"sanu","bhupiyamau",4656554,"F","ponds"),
(103,"harsh" ,"chaukhada",4565565,"M","cricket bat") ,
(104, "rudresh","hasanpur",55551445,"M","ramayan"),
(105,"mummy", "allahabad",633665,"F","saree"),
(106,"chacha","lucknow", 55466444, "M","puma shoes"),
(107,"anant","orai",225552,"M","t-shirt");
