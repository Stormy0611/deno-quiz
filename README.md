# Quiz
Simple Deno Oak MVC, API, CRUD Application
Main Directory is drill-and-pracitce
## Installation
### PostgreSQL
### Deno
Using Powershell command
```
irm https://deno.land/install.ps1 | iex
```
## Usage
### Setup Environment
#### Environment Variables
|Key | Value |
|--|--|
|DATABASE_URL|postgres://username:password@host:port/dbname|
#### Restore Database nameed dbname above in PostgreSQL
Using flyway/sql/V1__initial_schema.sql
## Running
```
deno task dev
```
