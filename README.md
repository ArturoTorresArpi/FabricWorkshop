# FabricWorkshop
## Topics
The following outline will be the topics we will cover during these two days. Each folder contains the necessary files to carry out each workshop section. For specific topics, some pre-work needs to be done (e.g., deploying an Azure SQL Server), and you will find the instructions in each folder.

### Day 1
- Medallion Architecture
- SQL Mirroring
- Pipelines with Copy Job (Preview)
- Shortcuts (External ADLS and Internal)

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
* Deploy an Azure SQL Server with the following specifications:
  * Size:
    * 100 DTUs
  * Data:
    * Use the Sample AdventureWorks. (https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms#deploy-new-sample-database)
  * Networking:
    * Allow Azure services and resources to access this server
    * Allow Public access
  * Authentication:
    * System Assigned Managed Identity = On

## Shortcuts (External ADLS and Internal)
* Create an Azure Storage Count and a Container. 
* The storage account must have "Hierarchical Namespaces" enabled. 
* Upload the following two files to the container. The files are loaded in the "Day_1" Folder.
  * AdventureWorksLT_Customers.csv
  * AdventureWorksLT_Products.csv
 
## AI Skills
* Configure settings to allow creation of AI Skills.
  * Setup a Temporary F64 Capacity (Trial capacities will not work)
* Fabric Tenant Admin Configurations:
  * Enabled: Users can use Copilot and other features powered by Azure OpenAI
  * Enabled: Users can create and share AI skill item types

## Notebooks
* Download the following files to your Desktop (TBD)
* Download the following Notebooks to your Desktop (TBD)

## CI with DevOps
* Create a DevOps Organization in the same Tenant as the Fabric Tenant
* Create a Private DevOps Project
