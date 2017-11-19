# spring-mvc-jdbc-template-app
Restfull webservices using spring-mvc-jdbc-template and data base as postgresql

Table creatin:
create table TRN_EMPLOYEE(employee_id numeric,first_name varchar, last_name varchar, age numeric);
commit;

Avaible rest end points:

1- http://localhost:8080/spring-mvc-jdbc-template-app/employees --> GET
2- http://localhost:8080/spring-mvc-jdbc-template-app/employee --> POST
3- http://localhost:8080/spring-mvc-jdbc-template-app/employee/{id} --> GET
4- http://localhost:8080/spring-mvc-jdbc-template-app/employee/{id} --> DELETE
5- http://localhost:8080/spring-mvc-jdbc-template-app/employee/{id} --> PUT
