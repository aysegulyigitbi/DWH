# Data Warehouse and Database

A data warehouse doesn't have to be the same as a traditional database. A database is a transactional system set up to track and modify data in real-time, with the sole purpose of having the most up-to-date data available. It's structured to store data for a period of time. For instance, a database may only have a customer's most current address, whereas a data warehouse can store all the addresses a consumer has had in the last ten years.

A centralized database serves as the foundation for data storage. In RDBMS technology, this database is implemented. While such an application may be constrained by the fact that it's optimized to handle operational databases rather than data storage for a traditional RDBMS system. For example, ad-hoc queries, multi-table joins, aggregations consume extensive resources and slow down the output. Alternative server methods are then employed, as detailed below:

Relational databases are distributed in parallel in a data warehouse to enable scalability. Parallel relational databases often require shared memory in different configurations of multiprocessors or models that share nothing.

Use cases for databases in organizations:

- Generating reports for financial and other data
- Analyzing relatively small data sets
- Automating business processes
- Controlling data input

## Data Lake

A data lake allows the storage of all data, whether required, potentially required, or not required at all. While a data warehouse may not be able to store website text or social media data, a data lake can store website text or social media data.

Even though databases and data warehouses can process unstructured data, they may not do so in the most efficient manner. Storing all data in a database or data warehouse can be costly when there is an abundance of data outside.

Furthermore, the data entered into a database or data warehouse needs to be cleaned and prepared before storage. In cases of unstructured data and uncertainty about its usage, the storage process can be long and challenging.

For this reason, the data lake has gained prominence. The data lake is designed to efficiently handle unstructured data at the lowest possible cost.

## Comparison of Database, DWH, and Data Lake

![image](https://github.com/aysegulyigitbi/DWH/assets/127193220/ca1c9c13-d2d1-4b09-a08e-585fab2ab05e)
