#	What Is PL/SQL? Introduction & Architecture

-	PL/SQL is an extension of Structured Query Language (SQL) that is used in Oracle.
-	Unlike SQL, PL/SQL allows the programmer to write code in a procedural format.
-	Full form of PL/SQL is "Procedural Language extensions to SQL
-	It combines the data manipulation power of SQL with the processing power of procedural language to create super powerful SQL queries
-	PL/SQL means instructing the compiler 'what to do' through SQL and 'how to do' through its procedural way.
-	Similar to other database languages, it gives more control to the programmers by the use of loops, conditions and object-oriented concepts.



##	Architecture of PL/SQL

-	The PL/SQL architecture mainly consists of following three components:

	-	PL/SQL block
	-	PL/SQL Engine
	-	Database Server

	
##	PL/SQL Block:

-	This is the component which has the actual PL/SQL code
-	This consists of different sections to divide the code logically 
	-	declarative section for declaring purpose
	-	execution section for processing statements
	-	exception handling section for handling errors
-	It also contains the SQL instruction that used to interact with the database server.
-	All the PL/SQL units are treated as PL/SQL blocks
	-	This is the starting stage of the architecture which serves as the primary input
-	Following are the different type of PL/SQL units:
	-	Anonymous Block
	-	Function
	-	Library
	-	Procedure
	-	Package Body
	-	Package Specification
	-	Trigger
	-	Type
	-	Type Body
	
	
##	PL/SQL Engine

-	PL/SQL engine is the component where the actual processing of the codes takes place
-	PL/SQL engine separates PL/SQL units and SQL part in the input
-	The separated PL/SQL units will be handled by the PL/SQL engine itself
-	The SQL part will be sent to database server where the actual interaction with database takes place
-	It can be installed in both database server and in the application server.


##	Database Server:
-	This is the most important component of Pl/SQL unit which stores the data.
-	The PL/SQL engine uses the SQL from PL/SQL units to interact with the database server.
-	It consists of SQL executor which parses the input SQL statements and execute the same.


##	Advantage of Using PL/SQL

-	Better performance, as SQL is executed in bulk rather than a single statement
-	High Productivity
-	Tight integration with SQL
-	Full Portability
-	Tight Security
-	Support Object Oriented Programming concepts.
