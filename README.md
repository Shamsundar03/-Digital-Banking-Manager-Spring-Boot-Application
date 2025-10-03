A simple Spring Boot CRUD project for managing bank accounts.
This application demonstrates core backend concepts like REST API design, database operations, and numeric updates (deposit/withdraw).

🚀 Features
Create new account
View account details by ID
Update balance (deposit/withdraw)
Close account (delete)


🗄 Database Schema
Table: accounts

id (PK) → Unique account ID
accountHolder → Account holder name
accountType → Savings / Current
balance → Account balance
openedDate → Date of account opening

⚙️ Tech Stack
Java 17+
Spring Boot
Spring Data JPA (Hibernate)
H2 / MySQL
Maven

Application runs on: http://localhost:8080/accounts

📖 Learning Outcomes

CRUD operations with Spring Boot RESTful API implementation Database handling using JPA/Hibernate Real-world banking use case simulation

▶️ How to Run
git clone https://github.com/<your-username>/BankAccountManager.git
cd BankAccountManager
mvn spring-boot:run
