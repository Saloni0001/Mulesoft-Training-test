# Mulesoft-Training-test
CREATE DATABASE Movie4;
CREATE TABLE Movies4 (MovieName varchar(255),LeadActor varchar(255),Actress varchar(255),YearOfRelease varchar(255),DirectorName varchar(255));
INSERT INTO Movies4(MovieName,LeadActor,Actress,YearOfRelease,DirectorName)
VALUES('Padmaavat','Ranveer Singh','Deepika Padukon','25 Jan 2018','Sanjay Leela Bhansali'),('Singham','Ajay Devgan','Kajal Aggarwal','22 July 2011','Rohit Sheety'),('Singham Return','Ajay Devgan','Kareena Kapoor','15 August 2014','Rohit Sheety'),('Kick','Salman Khan','Jacqeline Ferandise','25 July 2014','Sajid Nadiyawade'),('Sultan','Salman Khan','Anushka Sharma','6 July 2016','Ali Abbas Zafar')		
SELECT *FROM Movies4;
SELECT MovieName FROM Movies4 where LeadActor='Salman Khan'
