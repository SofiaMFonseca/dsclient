# CRUD

## Skills

- Create Spring Boot Project 
- Create Git monorepo 
- Organize the project in layers
  - REST Controller 
  - Service 
  - Data Access (Repository) 
- Create entities 
- Configure project test profile 
- Database seeding 
- Create REST web services 
  - Route parameters @PathVariable 
  - Request parameters @RequestParam 
  - Requisition body @RequestBody 
  - ResponseEntity<T> request response 
- DTO standard 
- Full CRUD 
- Exception handling 
- Postman (Collections, Environments) 
- Audit data 
- Data pagination 
- Entity associations (N-N)

## Task to deliver (final chapter work)

You must submit a Spring Boot 2.4.x or higher project containing a complete CRUD of REST web services to access a client resource, containing the five basic operations learned in the chapter:

- Paginated resource search 
- Resource search by id 
- Insert new resource 
- Update resource 
- Delete resource
 
The project must have a test environment configured by accessing the H2 database, you should use Maven as the dependency manager, and Java 17 as the language. A client has a name, social security number, income, date of birth, and number of children. The specification of the Client entity is shown below. Your project should seed at least 10 customers with significant data.

![Figma](https://github.com/SofiaMFonseca/assets/blob/main/dsclient/conceptual-model-dsclient.png)
