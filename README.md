# SimpleWpfDbApp
Простое WPF приложение, взаимодействующее с локальной с базой данных MS SQL Server посредством технологии ado.net. Работа идёт с одной таблицей. Ничего особенного. 
Скрипт для создания бд и таблицы:

**create database DB;
use DB;
create table Users(
Id int primary key identity,
Name nvarchar(50),
Age int)
insert Users (Name, Age) values ('Alpha', 1), ('Bravo', 2), ('Charlie', 3), ('Delta', 4), ('Echo', 5), ('Golf', 6), ('Foxtrot', 7)**
