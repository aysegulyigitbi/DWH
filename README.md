# Database Storage Types

When considering the functions of an Enterprise Data Warehouse (EDW), there is always room for debate regarding how it should be technically designed. In the context of data storage and processing, these are specific to different job types and differ accordingly. Of course, depending on the volume of data, technical sophistication, security concerns, and budget, you always have options for setting up your system. 🤔

![image](https://github.com/aysegulyigitbi/DWH/assets/127193220/0599de3d-b622-4c51-9b09-e1cdafe2dc4c)


## 1. Classic Data Warehouse 🏢

For an EDW, storage combined with custom hardware and software is considered an excellent variable. You don't need to configure data integration tools between physical storage and multiple databases. Alternatively, the EDW can connect to data sources via APIs to continuously source and transform information in the process. Therefore, all work is done either in the staging area or within the warehouse itself, before loading data into the data warehouse.

Being without an additional abstraction layer, a classic data warehouse is considered superior to a modern data warehouse (which we will discuss below). It simplifies the work of computer developers and facilitates actual reporting as well as data flow on the preprocessing side. The disadvantages of a traditional warehouse depend on the actual implementation, but for most companies, these include:

- Expensive technical technology in terms of both hardware and software. 💰
- Hiring a team of computer developers and DevOps experts to set up and maintain the entire data network. 🛠️

## 2. Virtual Data Warehouse 💻

A virtual data warehouse is a form of EDW used as an alternative to a traditional warehouse. These are often digitally interconnected systems that can be queried as a single unit.

Such an approach allows organizations to keep things simple: data can remain in its source with the help of analytical tools but can still be queried. If you don't want to deal with all the underlying infrastructure, virtual data stores can be used. Additionally, the data you have can be managed as-is in a rapid manner. However, this strategy comes with many disadvantages: having multiple systems may require continuous maintenance and software and hardware expenses.

In a simulated data warehouse, there needs to be a program for transitioning processed data into a digestible form for end-users and reporting tools.

Complex data queries can take a long time since required data pieces can be placed in two separate databases. ⌛

## 3. Cloud Data Warehouse ☁️

As mentioned above, all providers offer fully managed, scalable storage as part of Business Intelligence tools or focus on EDWs as an independent service, such as Snowflake. In this case, the design of a cloud warehouse has the same advantages as any other cloud service. Microsoft, for instance, manages the network for you, so you don't have to set up your servers, pools, and software to be managed by Microsoft. The price of such a service will depend on the available memory and the amount of computational capabilities required for querying.

The only concern you may have with a cloud warehouse platform is data security. Your business data is something sensitive. Therefore, you want to test whether you can trust the provider you choose to prevent any breaches. This does not mean an on-premises facility is secure, but in this case, data security is in your hands. 🔒
