# docker-compose-mysql-crud
Spring CRUD with MySQL Database and containerized with docker compose

## How to launch application

In your terminal, move to root folder of project "SimpleCrud" and run the following command: docker-compose up --build

## First time run

Please verify if the application propertie, in file "application.properties", "spring.jpa.hibernate.ddl-auto" is setted to create

## After first time rume

Please set application propertie, in file "application.properties", "spring.jpa.hibernate.ddl-auto" to update

- Use this setup for in first time run Spring be cappable to create our database entities, and after our database will not be dropped and data persisted during runtime will be saved
