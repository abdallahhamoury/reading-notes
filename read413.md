# Read: 13 - Related Resources and Integration Testing
------------------------------------------------------------------------------------

### Working with Relationships in Spring Data REST

Not all relational databases are created equal. A poorly designed database may make it difficult to access the information you need or jeopardize the accuracy of your data; On the other hand
You can avoid redundant, duplicate and invalid data
You can avoid situations where you are missing the required data
The database structure is easy to modify and maintain
The data itself is easy to modify
Easy to find the information you need
You can spend less time repairing your database and more time doing other types of work

### There are three types of relationships between tables

- One-to-one relationships
Where a record in one table is related to only one record in another table
- One-to-many relationships
A record in a table can be linked to one or more records in another table
- Many-to-many relationships
Where one or more records in one table can be linked to one or more records in another table

-------------------------------------------------------------------------------------------------------------
## Integration Testing in Spring

Spring boot provides @SpringBootTest annotation which starts the embedded server, creates a web environment and then enables @Test methods to do integration testing. Use it's webEnvironment attribute for it. It also creates the ApplicationContex
