### Relational Keys
One of the most important component of the relational model is the concept of keys. Keys are columns specific to a particular table that allow to hold some sort of constraint and integrity over the data in the table. This allows to secure data from certain anomalies that may happen due to different data manipulation operations.

Database Keys can be categoried into two major parts:

1- Entity Integrity Keys
2- Referential Integrity Keys

#### 1- Entity Integrity Keys
These keys are used for the purpose of identifying whether each record associated with the respresentative attribute(s) of the table is unique or not. This helps in enforcing the definition of Entity (table), e.g. for a table with CUSTOMER information, something like CUSTOMER_NO or CUSTOMER_ID will be a representative column as it represents the CUSTOMER entity. If this column is not unique for some reason, it would mean that some other CUSTOMER with some other name is being referred with the same CUSTOMER_NO or CUSTOMER_ID, making data duplicated and unable to use for other tasks.

In terms of Entity Integrity enforcement, a lot of different terms are associated with keys, all of which lead back to this purpose, but depending on whether the key is being used to represent the entity or not, the name convention used is different. Here are the different types of entity integrity keys:
