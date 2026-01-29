**Constraints**

Constraints are the rules enforced on table columns to maintain data integrity and consistency.

The following are different types of constraints:

i)*Primary key*: unique and not null, we can add primary key even after creating the table, but it should not contain null in that particular column.

ii)*Foreign key*: referencing to another table

iii)*Unique*: distinct values in that column

iv)*Not null*: values must not be duplicated

v)*Check*: checking any condition before insertion

vi)*Default*: if no value is entered, it takes default



***Note***: If we try to add any constraint later after creating the table, and it has any values that violates the constraint, then MySQL throws an error and the constraint is not added.

