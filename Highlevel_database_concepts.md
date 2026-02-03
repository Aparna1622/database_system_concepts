Book name- Database System Concepts-Seventh Edition  
website of the book- www.mheducation.co.in  
for practice exercises- https://connect.mheducation.com  
to send any suggestions- db-book-authors@cs.yale.edu  
  
--Database-Management-System(DBMS):  
It is a collection of interrelated data and a set of programs to access those data. The primary goal of a DBMS is 
to provide a way to store and retrieve database information that is both convenient and efficient.
The earliest database systems arose in the 1960's.  
  
--Database systems are used to manage collections of data that:
1. are highly valuable  
2. are relatively large and  
3. are accessed by multiple users and applications, ofter at the same time.

--- Purpose of data base systems
1. Conventional file-processing environment do not allow needed data to be retrieved in a convenient and efficient manner. More responsive data retrieval systems are required for this purpose.
2. It is developed to overcome the disadvantages of file-based applications to database systems.
3. The major purpose of database is to provide users with an abstract view of the data. That is, the system hides certain details of how the data are stored and maintained.  
Drawbacks of data saved in OS with some programs:
1. Data redundancy and inconsistency(duplication)
2. Difficulty in accessing data
3. Data isolation
4. Integrity problems
5. Atomicity problems(what if a system crashes and transaction holds)
6. Concurrent access anomalies
7. Security problems

Data Models:
Underlying the structure of a database is the data model. It is collection of conceptual tools for describing data, data relationships, data semantics, and consistency constraints.  
Different types of data models:  
1. Relational model:  
It uses a collection of tables to represent both data and the relationships among those data. Each table has multiple columns, each column has a unique name. Tables are also know as relations.
2. Entity-Relationship Model:
The entity-relation(E-R) data model uses a collection of basic objects, called entities, and relationships among these objects. An entity is a "thing" or "object" in the real world that is distinguishable from other objects. The entity-relationship model is widely used in database design.
3. Semi-structured Data Model:
Here, the data model permits the specification of data where individual data items of the same type may have different sets of attributes. JSON and Extensible Markup Language(XML) are widely used semi-structured data representations.
4. Object-Based Data Model: Object-oriented programming has led to the develpment of a distinct object-oriented data model, but today the concept of objects is well integrated into relational databases. 
