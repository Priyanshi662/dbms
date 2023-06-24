## Some Important Terms in DBMS
### Instance of a Database:
A database instance is the snapshot of the database at the particular point of time. It represents the actual data present in the database at the runtime and at that time.

### Schema :
Schema refers to the logical structure of the database. It defines the relationship between the entities,layout of the tables , contraints and other database objects 

### Subschema :
Subschema is the subset of the schema of database. It is a customized view of the database tailored for a particular user or application. It contains only the relavant tables and attributes required by the user or application while abstracting the irrelevant details.

### Data abstraction :
Data abstraction in dbms is done by hiding unnecessary background details from the user and only showing relevant details, this helps in making accessing data more secure and easy.
There are 3 levels of abstraction in DBMS :
#### 1. Physical or internal level :
It is a layer that defines how the relations specified in the conceptual schema are actually stored in the secondary storage like disks and tapes.

#### 2. Conceptual level :
At the conceptual level the structure of the data is defined and all the relations between data in the database.

#### 3.View or external level :
Any given database has exactly one conceptual schema and one physical schema because it has just one set of stored relations, but it may have several external schemas, each tailored to a particular group of users.Each external schema consists of a collection of one or more views and relations from the conceptual schema.