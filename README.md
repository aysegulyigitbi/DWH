# What is OLTP?

Online Transaction Processing (OLTP) is a system that manages a business's daily transactions and organizes operations on a database. Its primary objective is to efficiently handle operations like Insert, Delete, and Update that occur within a business process, supporting the day-to-day operations of the business. The focal point of OLTP is to process real-time and filtered information swiftly.

![image](https://github.com/aysegulyigitbi/DWH/assets/127193220/78355ff9-fe0f-496b-8872-8a50d6c5e405)


## OLTP Workload and Tasks

OLTP workloads generally consist of short transactions that occur in a brief period. The system's core tasks include:

- **User Identity Management:** Determining the identity of the current user.
- **Location Tracking:** Tracking the current location of the user.
- **Invoice Information Management:** Adding, updating, or deleting invoice information for a specific user or group, especially crucial for financial institutions like banks.
- **User Information Update:** Updating user information, adding new users, or deleting old users.

## OLTP System Characteristics

1. **Data Processing Capacity:** Suitable for processing a small amount of data.
2. **Response Time:** OLTP typically focuses on fast response times.
3. **Real-time Data Processing:** Data is created or updated instantly during transactions.
4. **High User Volume:** OLTP systems are designed to handle a high number of users simultaneously.
5. **Data Management Ease:** Data can be easily updated, deleted, or added.

**Note:** In OLTP systems, "Select" and "Delete" commands are usually used sparingly. Deletion operations are recommended to be performed using the "IsDeleted" column.

## OLTP Systems

- MySQL
- Oracle Database
- PostgreSQL
- Microsoft SQL
- IBM DB2
