# Data Obstacle Prevention List

Everyone has always heard about data being one of the biggest challenges and time consuming parts of a Data Science project.

Data in the real world can be ugly and uncooperative. This checklist identifies typical data obstacles so that you can prevent them in your project. 

# 1. Data Plan
## Do not  plan to make predictions for outcomes that are not measured or are not relevant.

# 2. Data Acquisition

# 3. Data Ingestion
## Some tools can't hold wide tablesData  was too wide to import into a SQL table.Quickest fix: Put data in an Azure blob with  the goal of considering how to divide it into multiple SQL tables.Better fix: Determine feature selection  that will fit in a SQL  table.

## Ingest from  on-prem has issues with a number of tools
- Large data sizes require physical disks to be shipped.  That requires planning.
- Azure has new capabilities for ingesting large amounts of data and documentation is easily available.

# 4. Data Preparation
Cleaning and understanding data directly impacts all subsequent work and outcomes.

##Plan for issues with naming  from different groups, companies or tools
Correllating feature names, columns, between groups or tools can  not be expected to match. At one company I worked at, because of historic and disconnected tools, we had over 25 variations on the name "HP", "H.P.", "Hewlett-Packard", etc. And that was just ONE company and one data issue. Correllating data from more than one company is even harder.

# 5. Data Analysis


# 6. Data Publication





