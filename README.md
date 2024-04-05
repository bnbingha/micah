# Micah's CRUD sample project

## Download
- Visual Studio (note that this is a different program from Visual Studio Code)
- MySql Community
- Postman
- Git

## Database
- Create a local database
- Create a new schema and a table name "Customer"
- The table should have the following columns
  - "Id" of the INTEGER type. This should be the primary key and should auto increment
  - "Name" of VARCHAR(45)
 
## API
- Create a new project in Visual Studio using the "ASP.NET Core Web API" template
- Install the folloing NuGet packages
  - Dapper
  - MySqlConnector
- Create an API the following endpoints and functionality
  - /GetAllCustomers
  - /GetCustomer
  - /CreateCustomer
  - /UpdateCustomer
  - /DeleteCustomer
