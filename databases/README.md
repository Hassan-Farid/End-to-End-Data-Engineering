### Databases
Databases come forward as the fundamental building block for data engineering as it serves as one of the main sources from which data is picked in a data pipeline for transformation purposes.

Databases are basically a set of files stored in an organized manner. This helps in efficiently storing, retrieving and managing data. The type of data can vary for a database i.e. it can be some text, numbers, images, videos, etc. 

Although databases are everywhere, what really is the difficult part is managing them. That is why Database Management Systems (DBMS) were introduced so that data within these databases can be managed effectively. 

This particular part of the repository will focus on the DBMS part of the process as it gives you an idea on how data is stored and managed to ensure data integrity and quality. Knowing the concepts related to DBMS systems and its internals helps in getting a clearer picture about how SQL queries get executed and how everything works under the hood. 

Databases can themselves be categoried into multiple categories based on the use case they are being applied to. We have Relational Databases and Non-Relational Databases if we go by major categories, each with its own use cases. For the purpose of this repostory, we will be looking at some of the commonly used DBMS systems, how they work under the hood and how to write SQL queries to achieve different tasks using them. 

This section of the repository is structured as follows:

- Theoretical DBMS: In this part, we will be looking at theoretical concepts that apply to the various implementations of DBMS systems. Since relational and non-relational are considered the two major categories, we will divide them as such. Non-Relational can have sub-categories like key-value databases, graph databases, etc. which will be covered within it. One thing to highlight though that although concepts like vector databases and JSON documents will be a part of Non-Relational theory, in practical implementations there are cases where the said functionality is available within a relational database as an extension as well.

- Practical DBMS: In this part, we will be looking at some practical DBMS systems and how they handle or process various things under the hood. This part will built on top of the theoretical foundations covered in the theory part of this section. Following are the DBMS systems we will be taking a look at:
    - Oracle (Enterprise Relational DBMS)
    - Postgres (Row-oriented Object-oriented Relational DBMS)
    - DuckDB (Column-oriented Relational DBMS)
    - Redis (NoSQL In-memory Key-value DBMS)
    - MongoDB (NoSQL Document-oriented DBMS)
    - Neo4j (NoSQL Graph-oriented DBMS)
    - Weaviate (NoSQL Vector Database)
