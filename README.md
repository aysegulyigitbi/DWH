# Data Warehouse Architecture

Data warehouse architecture represents the design of an organization's framework for collecting and storing data. As data needs to be processed, cleaned, and organized to be usable, the design of a data warehouse focuses on discovering the most efficient method to extract valuable insights from raw sources and present them in a digestible system that provides valuable Business Intelligence (BI) insights.

There are three main types of architectures considered when creating a data warehouse for an organization, each with its own advantages and disadvantages:

1. **Single-layer Data Warehouse Architecture:**
   - Aims to create a compact data set and minimize the amount of stored data.
   - Useful in eliminating redundancies but not applicable to organizations with significant data needs and multiple streams.

2. **Two-layer Storage Systems:**
   - Physically isolates existing resources from the environment.
   - More efficient in processing and organizing data but lacks flexibility and requires a minimal number of end-users.

3. **Three-layer Architecture (the most popular type):**
   - Creates a more structured flow towards actionable insights from raw clusters.
   - The bottom layer is the database server itself, housing backend tools for data cleaning and transformation. (Database)
   - The middle layer uses OLAP and acts as an intermediary between end-users and the warehouse. OLAP can communicate with both relational and multidimensional databases, enabling the collection of more data based on broader parameters. (Data Warehouse)
   - The top layer serves as the frontend of a company's overall business analysis system, where developers can use queries, data visualizations, and analytics software to communicate with results. (Reporting)
