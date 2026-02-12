Database Languages:  
A database system provides a data-definition language(DDL) to specify the database schema and a data-manipulation language(DML)
to express database queries and updates.

Meta_data:  
The output of the DDL is placed in the Data-Dictionary, which contains metadata, that is data about data. The data dictionary is considered to be a special type of table that can be accessed and updated only by the database system itself(not a regular user). The database system consults the data dictionary before reading or modifying the actual data.

Data Dictionary:  
It is a special notebook inside the database that stores information about the data(which is called meta data).  

Data Manipulation Language:  
It is a language that enables users to access or manipulate data as organized by the appropriate data model.  
There are basically two types of data-manipulation language:  
1. Procedural DMLs requires a user to specify what data are needed and how to get those data.
2. Declarative DMLs(also know as nonprocedural DMLs) require a user to specify what data are needed without specifying how to get those data.

The SQL Data-Manipulation Language:  
The SQL query language is nonprocedural. 
