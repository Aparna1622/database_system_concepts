Data Abstraction:  
Since many database-system users are not computer trained, developers hide the complexity from users through several levels of data abstraction, to simplify users interaction with the system.  
Physical level:  
The lowest level of abstraction describes how the data are actually stored. The physical level describes complex low-level structures in detail.  
Logical level:  
The next-higher level of abstraction describes what data are stored in the database, and what relationships exist among those data.Database administrators who must decide what information to keep in the database, use the logical level of abstraction.  
View level:  
This view level of abstraction exists to simplify the user's interaction with the system. The system may provide many views for the same database.  

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/af27a203-9df3-4f3e-9db8-1ffd10128b50" />  

The important feature of data models, such as the relational model, is that they hide such low-level implementation details from not just database users, but even from database-application developers. 

---Database use a type of structure called index to support efficient retrieval of records; these too form part of the physical level.

Instance:  
The collection of information stored in the database at a particular moment is called an instance of the database. The values of the variable in a program at a point in time corresponds to an instance of a database schema.    
Schema:  
The overall design of the database is called the database schema. It corresponds to the variable declarations(along with associated type definitions) in a program. 

