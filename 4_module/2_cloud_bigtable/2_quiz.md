# True or false: Each table in NoSQL databases such as Cloud Bigtable has a single schema that is enforced by the database engine itself.

> False

Obs: NoSQL databases such as Cloud Bigtable are suitable when all items in the database needn't have their integrity checked by a database schema. Why not? Maybe you want your database items to contain variable fields, or maybe because you simply want your application to manage database integrity.

# Some developers think of Cloud Bigtable as a persistent hashtable. What does that mean?

> Each item in the database can be sparsely populated, and is looked up with a single key. 
