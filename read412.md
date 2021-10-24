# Read: 12 - Spring RESTful Routing & Static Files
-------------------------------------------------------------------------------------------------------------------
**RequestMapping** is the most popular and most used annotation in Spring MVC.
> It is used to assign web requests to specific processor classes and/or process processor methods. Assigning media types produced by the control method deserves special attention.
We can assign an order based on its accept address

It annotates HTTP requests to handler methods for MVC and REST controllers.
-----------------------------------------------------------------------------------------------------------------------



## Accessing Data with JPA

we Run Spring data on using JPA data in a relational database.
The most compelling expansion is the ability to build repository applications automatically, at runtime, from the repository interface.
The customer deposits an extension of the CrudRepository interface.
Define the MySQL JDBC driver dependency, which enables a Java application to communicate with a MySQL server
then Specify the dependency for Spring JDBC or Spring Data JPA. Specify the data source properties for the database connection information.

----------------------------------------------------------------------------------------------------------------------

## Baeldung: Comparing repositories

Crud Repository does not provide ways to perform pagination and sorting. JpaRepository links your repositories with JPA persistence technology so you should avoid it. We should use CrudRepository or PagingAndSortingRepository depending on whether you need to sort and migrate or not
The goal of Spring Data Repository extraction is to drastically reduce the amount of modular code required to implement data access layers for different persistence stores. Uses config forms and code for Java
