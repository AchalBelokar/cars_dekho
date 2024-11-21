# cars_dekho
#use databases:-
use cars;
#select car_dekho table:-
select * from car_dekho;
#count all the car in the show room:-
select count(*) from car_dekho;
#count 2023 year of the car:-
select count(*) from car_dekho where year = 2023;
#count 2020,2021,2023 year of the car:-
select count(*) from car_dekho where year in (2020,2021,2023)group by year;
#select all the year and count:-
select year,count(*) from car_dekho group by year;
select count(*) from car_dekhho where year = 2020 and fuel="Diesel";
select  year, count(*) car_dekho where fuel = "Petrol" group by year;
select year,count(*) from car_dekho group by year having count(*)>100;
select count(*) from car_dekho where year between 2015 and 2023;
select * from car_dekho where year between 2025 and 2023;
