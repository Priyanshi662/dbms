## Keys
Keys are attributes which can identify the row in the relation (table) uniquely.
For example in a student table , the keys can be student id, class, section,etc.
</br>
They are of following types :

![keys](primKey.png)
### Primary Key:
Out of many candidate keys , the key which identifies an entity uniquely is choosen as primary key.
It cannot be NULL,and more than one column can constitute a primary key. It is the responsibility of database admins to set a primary key which has a unique value for each row in the table.

### Candidate Key:
candidate key is an attribute or a set of attributes which uniquely identifies a tuple. They are as strong as primary key. For example, to identify a citizen there can be many candidate keys such as PAN number, SSN, Voter Id number which can be chosen as candidate keys.
Characteristics:
1. It can contain NULL values.
2. Every table must have at least a single candidate key.
3. It is a super key with no repeated data is called a candidate key.

### Super Key :
It is set of attributes which can uniquely identify a tuple.Adding zero or more attributes to the candidate key generates the super key.. For example, a super key can be EMPLOYEE_NO and EMPLOYEE_NAME.It supports NULL values. 

## foreign key :

## alternate key :

## secondary key :

## composite key :
