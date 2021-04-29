# About

MVC in : client/src/main/java

- Desktop App based on client-server architecture(Sockets are used for communication) used to manage a garden.
- there are 2 types of users: regular user(gardener) and administrator  
	The regular user can perform the following operations:
	- view graphically the garden
	- can plant new plants 
	- can send requests if some plant is out of stock
	
	The administrator can perform the following operations:
	- CRUD on plants 
	- CRUD on regular users
	- generate report files	
	- can accept/deny request
	- etc.
# Tools and Technologies used
- Java 8
- Lombok
- Java Sockets
- MySQL
- PMD static analysis tool(there isn't a single best practice violation in the project)

# Database Design(MySQL)
