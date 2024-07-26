![](https://www.teguharief.com/img/teguh-arief.png)

# Spring Web

Angular v18 CRUD operations with Spring Boot and MySQL.

## Installation

Install the app on terminal

```
git clone git@github.com:teguharifudin/Spring-Web.git
```
```
cd Spring-Web
```

### Backend
```
cd backend
```
```
mvn spring-boot:run
```

### Frontend
```
cd frontend
```
```
npm install
```
```
npm start
```

## Usage

- Backend in Postman

POST http://localhost:8080/api/v1/employees
```
{
    "firstName": "teguh",
    "lastName": "arief",
    "emailId": "teguh.arifudin@gmail.com"
}
```

GET http://localhost:8080/api/v1/employees

POST http://localhost:8080/api/v1/employees/{employeeId}
```
{
    "firstName": "teguh",
    "lastName": "arifudin",
    "emailId": "teguh.arifudin@gmail.com"
}
```

DELETE http://localhost:8080/api/v1/employees/{employeeId}

- And run the Frontend on browser at http://localhost:4200/

## Contributing

Please use the [issue tracker](https://github.com/teguharifudin/Spring-Web/issues) to report any bugs or file feature requests.