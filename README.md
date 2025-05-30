# DP-3015 Demo Catalog

This repository contains a collection of demonstration files designed to showcase various features and capabilities of Azure Cosmos DB for NoSQL. Each demo is structured to provide hands-on experience with specific functionalities, ranging from setup and configuration to advanced query operations.


## Requirements

- [Dotnet SDK 9](https://dotnet.microsoft.com/download/dotnet/9.0)
- [Node.js 14 or higher](https://nodejs.org/)
- [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)

---

## M01: Getting Started with Azure Cosmos DB for NoSQL

### [Demo 1: Azure Cosmos DB Setup Script](./M01/Demo%201/Demo1.md)

Automates the provisioning of an Azure Cosmos DB environment, including the creation of a resource group, Cosmos DB account, SQL API database, and container. Ideal for quick setup and demonstration purposes.

### [Demo 2: Query Cosmos DB](./M01/ApolloDemo/Demo2.md)

Demonstrates various query operations in Cosmos DB, including filtering, projections, and joins. Includes sample documents for initial database loading.

### [Demo 3: Stored Procedure, Trigger, and Transaction Support in Cosmos DB](./M01/ApolloDemo/Demo3.md)

Explains how to use stored procedures, triggers, and user-defined functions in Cosmos DB. Provides examples of pre-insert/update triggers and stored procedures for partition-specific calculations.

---

## M02: Planning and Implementing Azure Cosmos DB for NoSQL

### [Demo 1: Explore RU Usage](./M02/Demo1-RUs/Demo1.md)

Illustrates the impact of query complexity on Request Unit (RU) consumption in Azure Cosmos DB. Includes examples of simple and complex queries with RU metrics.

---

## M03: Connecting to Azure Cosmos DB for NoSQL with SDKs

### [Demo 1 (.NET): Basic Operations with Azure Cosmos DB SDK for .NET](./M03/Demo1-SDK/Demo1-cs.md)

Demonstrates fundamental operations such as database creation, container creation, document insertion, querying, and deletion using the Azure Cosmos DB SDK for .NET.

### [Demo 1 (Node.js): Basic Operations with Azure Cosmos DB Node.js Client](./M03/Demo1-SDK/Demo1-js.md)

Showcases basic operations like database creation, container creation, document insertion, querying, and deletion using the Azure Cosmos DB Node.js SDK.

### [Demo 2: Logging and Basic Operations with Azure Cosmos DB SDK for .NET](./M03/Demo2-Log/Demo2.md)

Highlights logging configuration and basic operations using the Azure Cosmos DB SDK for .NET. Provides insights into monitoring and troubleshooting.

---

## M04: Accessing and Managing Data with Azure Cosmos DB for NoSQL SDKs

### [Demo 1: CRUD Operations with Azure Cosmos DB SDK](./M04/Demo1-CRUD/Demo1.md)

Demonstrates Create, Read, Update, and Delete (CRUD) operations using the Azure Cosmos DB SDK for .NET. Includes examples of document management and query execution.

---

## M05: Executing Queries in Azure Cosmos DB for NoSQL

### [Demo 1: Query Operations with Azure Cosmos DB SDK for .NET](./M05/Demo1-Query/Demo1.md)

Explores query operations and RU consumption using the Azure Cosmos DB SDK for .NET. Includes examples of filtering, projections, and RU optimization.

### [Demo 2: Advanced Query Operations with Azure Cosmos DB SDK for .NET](./M05/Demo2-Params/demo2.md)

Showcases advanced query techniques, including parameterized and paginated queries, using the Azure Cosmos DB SDK for .NET. Provides examples of efficient data retrieval and analysis.

---




## Key Notes

- Each demo is designed to provide practical insights into Azure Cosmos DB functionalities.
- Follow the instructions provided in each demo file to set up and execute the demonstrations effectively.
- Ensure prerequisites such as SDK installations and Azure credentials are configured before running the demos.

