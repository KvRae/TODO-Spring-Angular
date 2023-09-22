# Todo with Spring And Angular


![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.2-brightgreen)
![Angular](https://img.shields.io/badge/Angular-12.2.10-red)
![Java](https://img.shields.io/badge/Java-11-blue)
![Maven](https://img.shields.io/badge/Maven-3.8.3-orange)
![Node](https://img.shields.io/badge/Node-14.17.6-green)
![npm](https://img.shields.io/badge/npm-6.14.15-yellow)
![MySQL](https://img.shields.io/badge/MySQL-8.0.27-blue)
## Description
This is a simple Todo application with Spring Boot and Angular.
The application is divided into two parts: backend and frontend. The backend part is a REST API application based on Spring Boot. 
The frontend part is an Angular  application that uses the backend part.

## Installation
### Backend
1. Clone the repository
```bash
git clone
```
2. Go to the backend directory
```bash
cd backend
```
3. Run the application
```bash
mvn spring-boot:run
```
### Frontend
1. Go to the frontend directory
```bash
cd frontend
```
2. Install dependencies
```bash
npm install
```
3. Run the application
```bash
npm start
```
## Usage
### Backend
The backend part is a REST API application based on Spring Boot.
The application uses the following technologies:
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Lombok
- DevTools

The application has the following endpoints:
- GET /api/todos - get all todos
- GET /api/todos/{id} - get todo by id
- POST /api/todos - create todo
- PUT /api/todos/{id} - update todo by id
- DELETE /api/todos/{id} - delete todo by id
- DELETE /api/todos - delete all todos

### Frontend
The frontend part is an Angular application that uses the backend part.
The application uses the following technologies:
- Angular
- Angular Material
- Angular Flex Layout

The application has the following pages:
- Home page - displays all todos
- Add todo page - adds a new todo
- Edit todo page - edits an existing todo
- Delete todo page - deletes an existing todo
- Delete all todos page - deletes all todos
- About page - displays information about the application
- Not found page - displays information about the error

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contribution
Pull requests are welcome. For major changes, 
please open an issue first to discuss what you would like to change.

## Contact
Created by [@KvRae](https://www.linkedin.com/in/karam-mannai) - feel free to contact me!
