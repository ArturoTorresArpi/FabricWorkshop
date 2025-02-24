# FabricWorkshop
## Topics
The following outline will be the topics we will cover during these two days. Each folder contains the necessary files to carry out each workshop section. For specific topics, some pre-work needs to be done (e.g., deploying an Azure SQL Server), and you will find the instructions in each folder.

### Day 1
- SQL Mirroring*
- Medallion Architecture*
- Pipelines with Copy Job (Preview)*
- Shortcuts (External ADLS and Internal)*

### Day 2
Part 1
- Real-time Intelligence (Theory)
- Notebooks and Spark*
- CI Azure DevOps GIT*
- CD Deployment Pipelines*
- AI Skills

Part 2
- Fabric Databases
- Creating a Power BI Report with the Data from the Pipelines with the help of Copilot*
- Industry Solutions (Theory)
- Data Science (only the theory on Experiments, ML Models)
- OpenAI (Theory)


## Pre-work
## SQL Mirroring
Deploy an Azure SQL Server with 100 DTUs. Use the Sample AdventureWorks. Here are the instructions on how to do this:
https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms#deploy-new-sample-database

## Medallion Architecture
You don't need to do pre-work.

## Pipelines with Copy Job (Preview)
You don't need to do pre-work.

## Shortcuts (External ADLS and Internal)
* Create an Azure Storage Count and a container. 
* The storage account must have "Hierarchical Namespaces" enabled. 
* Upload the following two files to the container. The files are loaded in the "Day_1" Folder.
  * AdventureWorksLT_Customers.csv
  * AdventureWorksLT_Products.csv
