# PostgreSQL vs MySQL: What's the Difference?


##	What is MySQL?

-	MYSQL is a popular and widely used DBMS system.
-	It is an RDBMS (Relational Database Management System) and works primarily on the relational database model.
-	It makes database administration easier and more flexible

##	What is PostgreSQL?

-	Postgre is an object-relational database management system (ORDBMS).
-	Postgre is an Enterprise-class relational database system. 
-	It is easy to setup and installs. It offers support for SQL and NoSQL
-	Supports advanced data types 

##	Why use MySQL?

-	Supports features like Master-Slave Replication, Scale-Out
-	Support for Memory storage engine for frequently used tables
-	Query Cache for repeatedly used statements
-	Easy to learn and implement


##	Why use PostgreSQL?

-	Offers useful features like Table partitioning, Point in Time Recovery, Transactional DDL, etc
-	Offers advanced data-types and advanced features
-	Offers advanced locking mechanism
-	Users and Roles can be assigned with Object level privileges


##	Features of MySQL

-	Compatible with various platforms using all major languages and middleware
-	It offers support for Multi-version concurrency control
-	Compliant with the ANSI SQL standard
-	Object-oriented and ANSI-SQL2008 compatible
-	Fully multi-threaded, using Kernel Threads
-	It can handle any amount of data, up to as much as 50 million rows or more
-	MySQL runs on many varieties of UNIX, as well as on other non-UNIX systems like Windows and OS/2



##	Features of PostgreSQL
-	Most common alternative to Oracle, DB2 and SQL Server
-	Runs on all major OS platforms that you may have
-	supports large numbers of concurrent users
-	Extensive indexing for high-performance reporting
-	Support for modern applications (XML and JSON)
-	ANSI SQL support for transportable skills/code
-	Foreign keys support for efficient storage of data
-	Table joins and views for flexible data retrieval
-	Triggers/Stored Procedures for complex programs and transactions


##	Key Differences Between MySQL and PostgreSQL

-	MySQL

	-	MySQL is ACID compliant only when it is used with InnoDB and NDB Cluster Storage engines
	-	MySQL is partially SQL compliant. For example, it does not support check constraint.	
	-	It is mostly used for web-based projects that need a database for straightforward data transactions.	
	-	MySQL performs well in OLAP& OLTP systems when only read speeds are needed.	
	-	MySQL has a JSON data type support but does not support any other NoSQL feature.	
	-	Supports materialized views and temporary tables.	
	-	The default values can be overwritten at the session level and the statement level	
	-	Limit join capabilities	

	
-	PostgreSQL
	-	PostgreSQL is ACID compliant when using InnoDB and NDB cluster storage engines.
	-	PostgreSQL is largely SQL compliant.
	-	It is highly used in large systems where to read and write speeds are important
	-	PostgreSQL performance is utilized when executing complex queries.
	-	Support JSON and other NoSQL features like native XML support. 
		-	It also allows indexing JSON data for faster access.
	-	Supports temporary tables but does not offers materialized views.
	-	The default values can be changed at the system level only
	-	Good join capabilities


	
##	Disadvantages of using MySQL

-	Transactions related to system catalog are not ACID compliant
-	Some time A server crash can corrupt the system catalog
-	No pluggable authentication module preventing centrally managed account
-	No support for roles so it is difficult in maintaining privileges for many users
-	Stored procedures are not cacheable
-	Tables used for the procedure or trigger are always pre-locked


##	Disadvantages of using PostgreSQL

-	No upgrade facility for major releases
-	The data need to be exported or replicated to the new version
-	Double storage is needed during the upgrade process
-	The current external solutions require a high learning curve
-	indexes cannot be used to directly return the results of a query
-	Query execution plans are not cached
-	Bulk loading operations may become CPU bound




