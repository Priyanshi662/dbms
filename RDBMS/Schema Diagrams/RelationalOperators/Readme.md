## Relational Operators

### <u> SELECT (σ) </u>
It is analogous to the 'Where' operator of SQL. It is used to select tuples from a table which fulfill the given predicate .
Notation - σp(r)
σ is the predicate
r stands for relation which is the name of the table
p is prepositional logic

### <u> Project (π) </u>
It works same as the 'Select' operator of SQL. It is used to define a relation that contains vertical subset of a relation (contains the columns that are specified).

### <u> Rename </u>
Rename is a unary operation used for renaming attributes of a relation.
ρ (a/b)R will rename the attribute ‘b’ of relation by ‘a’.

## JOINS:
1. Cartesian Product :
Cartesian product is the cross product of two relations, which merges columns of two relations.

2. Inner Join :
Inner join includes only those tuples which match the given criterion.

3. Equi Join :
When a theta join uses equivalence condition only then it is called equi join.

4. Natural Join :
When there is a common column(attribute) between the relations , a natural join can be used to combine the relations.

5. Outer Join :
It returns more columns along with the tuples matched .It is of three types
    a. Left outer join
    b. Right outer join
    c. Full outer join