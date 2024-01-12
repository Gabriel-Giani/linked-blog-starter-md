Database systems

24
### Levels of abstraction
- #PhysicalLevel (Schema): describes 





Slide 25
# Physical Data Independence
- ability to mod physical schema without changing the logical schema
- supports program/data independence

26
# Data (Base) Models
### Data (Base) Model:  
collection of tools for describ logical levels
   ie. data, data relationships, data semantics, data contstraints
### Data Base models include
 #RelationalModel the most popular database model
 Older Models:
      Hierarchical model (first)(e.g. IMS by IBM)
      Network model (next) (e.g. IDMS,CODASYL)
 Object-based data models (object-oriented and object relational)
 semistructured data model(XML)
 NoSQL

### Data base model depends on tools used for descib logical levels
- relational model: table
- hierarchical model: tree
- network model: graph
- object oriented model: class(object)

### Object-relational data models
- Relational model
     flat "atomic" values
     mainly numbers and characters
- Object Relational (oriented) Data models
	- intended for expressing complex data
	- extend relational data model by including object orientation and constructs to deal with added data types
	- allow attributes of tuples to have complex types, including non atomic

### Relational Database Model
- most widely used today
- perceived by user as a collection of tables for data storage
- tables are series of row column intersections
- ##### Advantages:
	- Structural Independence 



Relational Model
- almost every DB model at present is relational model
- relational model uses table for logical level
- example of tabular data: (add image from slide)





### Data definition Language (DDL)
- ##### Database language has two parts: DML & DDL
- Specification for defining the database schema
- Example: ```Create table account(
					 account-number   char(10),
					 balance.         integer)```
- DDL compiler generates a set of tables stored in a data dictionary 
- *Data Dictionary* contains metadata(i.e., data about data)
	- Database schema
	- a special table in DB
	- Data storage and definition language
		- specifies the storage structure and access methods used
	- Stores integrity constraints
		- domain constraints 
		- referential integrity(*references* constraint in SQL)
		- assertions
	- Stores authorization information


### Data Manipulation Language (DML)
- Language for accessing and manipulating the data organized by appropriate data model
	- DML also known as query language
- Two classes of programming languages in general
	- *Procedural* - User specifies what data is required and how to get those data
		- C, C++, Java, etc (almost every language known)
	- *Declarative(nonprocedural)* - user specifies what data is required without specifying how to get those data
		- Just give goal, not procedure
		- we don't care how it is done
		- SQL, Query Language, Prolog, etc.
	- Which one is better and why?
- SQL is the most widely used commercial query language in relational model 

slide 35
### SQL
SQL: widely used non-procedural language
- example: Find the name of the instructor with ID 22222
	- *select* instructor.ID, department.building
	-  from instructor, deparment
	-  where instructor.dept name = "physics"
- Example 


### Database Access from Application Program
- SQL does not support action

### Database design 
- process of designing general structure of the database
- Logical design - Deciding on the database logical schema
	- Database design requires that we find a "good" 