# Learning Objectives

## Spring Data Rest - Expose CRUD methods for free

- Scan for JpaRepository
- Expose REST APIs for each entity type for JpaRepository
  - Create endpoints based on entity type
  - Simple pluralized form
    - First character of Entity is lower case
    - Then adds an "s" to the end of the entity name
- HATEOAS (meta-data for REST data)
- Pagination, sorting and searching (using spring data properties)

### For Spring Data Rest, you only need 3 items

- Your entity: Ex: Employee
- JpaRepository: Ex: EmployeeRepository extends JpaRepository
- Maven POM dependency: spring-boot-starter-data-rest
