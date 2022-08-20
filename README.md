# MetroPayApp

## Project
Group project at second year of Bachelor's Degree studies during OTP -course (Software production project). Developed in group of four students.

## App
MetroPay is banking application developed using Java. The application can be used to send money, receive money, buy, sell and send cryptocurrencies, browse transaction history and take up quickie loans. App has easy to use interface and its localized to four different languages. Interface has two different color themes too.

## Technologies used
Project is build with Maven, developed using mainly Java, JavaFx and CSS. For testing purposes there are JUNIT and JaCoCo libraries used. With database is used Hibernate and MariaDB. Jenkins was used during the project as a DevOps tool and Nektion as project management tool (SCRUM).

## Configuration
App requires database, in file metropay_database.sql are the queries we used to create database. Database requires configurations in hibernate.cfg.xml file too, url and credentials at least. In our prohject, tests have own database that is configured on different hibernate.cfg.xml file locating in test -directory.

## APIs
App is using [Free Currency Rates API](https://github.com/fawazahmed0/currency-api) for currency exchange rates.

## Screenshots

Login:  
  
![kuva](https://user-images.githubusercontent.com/95911203/185739406-fc493b77-b4a9-4ce7-859f-cd9be04b6476.png)  
  
Front page after logged in:  
  
![kuva](https://user-images.githubusercontent.com/95911203/185739487-46a70529-3e08-429b-8c65-bd61936afbac.png)  
