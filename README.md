<h1>Wallet_Payment_Application</h1>
An Collabrative Project Consisting Of the 5 Developer Depicting the implementation of the payemnt wallet online transaction platform
An developement of RESTful API for an Online Payment Wallet application. This API performs all the fundamental CRUD operations of any Online Wallet Banking platform with user validation at every step.

Teach Stacks Implemented


Java
Spring framework
Spring Boot JPA
Hibernate
MySQL
Swagger
Lombok

Modules
Login Logout User authentication
Wallet
BankAccount
BeneficiaryDetails
BillPayment
Transaction

Features

User Login authrntication
validation for the account number
validation for the current user and user identification
RESTful API with CURD operations
Functional Front End For better user experience


Installation & Run


#changing the server port
server.port=8888
#db specific properties
spring.datasource.url=jdbc:mysql://localhost:3306/sb201db
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username=root
spring.datasource.password=root
#ORM s/w specific properties
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.mvc.pathmatch.matching-strategy = ANT_PATH_MATCHER


API Root Endpoint


https://localhost:8888/
https://localhost:8888/swagger-ui/#
