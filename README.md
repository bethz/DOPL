# Do you want to prevent data from being an obstacle in your project?

Everyone has always heard about data being one of the biggest challenges and time consuming parts of a Data Science project.
Data does not lie, but it certainly can be ugly and uncooperative. This list identifies typical data issues to consider so that you can possibly prevent obstacles in your project. 

# 1. Data Plan
Do not  plan to make predictions for outcomes that are not measured or are not relevant.

Gaining an intuition about your data will help you generate the best outcomes and how the data moves is the ultimate indicator for how a business actually works. **Before** you begin  your project, identify some trends you would expect to see. Check the trends after you run some models and determine if the model seems to run correctly and if different, identify why it's incorrect. Identify if it's your assumption or incorrect outcomes in  the model.

Consider injecting and leveraging business intelligence into your data to derive improved outcomes. On more than one occasion, the data science team has determined how businesses processes work better than those running  the official process. 

# 2. Data Stewardship

Data Stewardship includes data as well as any models created from the data.
This is separate from the Data Plan so that it is given due consideration. Test data, POC data, pilot data and more must be considered according to the owner.  Find out requirements and timelines for each type of data to plan for and accomodate before the project begins.
PII, Personally Identifiable Information, can be a beast if not planned for. Make sure you have the appropriate logins and sufficient permission to access the data.  Note that this isn't only about being able to connect to the data, it is about the ability to access the fields as well as content.  Additionally, confirm rules tied to how you want to use that content.  For instance, there could be specific regulatory requirements for access.  In order to prevent audit exposure, it may be necessary to mask or exclude certain fields.

The timeframe for using the data is critical. Define the dates for the end of data access.  

Reminder: All of the data needed as well as the model created from the data must be considered.

Define source and incremental locations of the data.
Are there royalties associated with the data? Who manages and tracks?
Ensure awareness of relevant regulation, ie GDPR, Cookie regulations, etc


# 3. Data Acquisition

Data does indeed go stale. Frequently, historic data can become incompatible with current data even if the column names are the same. Incremental monitoring as well as regular outcome review are invaluable to prevent poor outcomes.

# 4. Data Ingestion
Check if your data fits in your tools.
Example: Data  was too wide to import into a SQL table. Best fix: Determine feature selection  that will fit in a SQL  table.

Ingest from  on-prem to cloud has issues with a number of tools
- Large data sizes require physical disks to be shipped.  That requires planning and takes more time than expected.
- Azure has new capabilities for ingesting large amounts of data and documentation is easily available.

# 5. Data Preparation
Cleaning and understanding data directly impacts all subsequent work and outcomes.

Plan for issues with naming data columns when data is being sourced from different groups, companies or tools.
Correllating feature names, columns, between groups or tools can  not be expected to match. At one company I worked at, because of historic and disconnected tools, we had over 25 variations on the name "HP", "H.P.", "Hewlett-Packard", etc. And that was just ONE company and one data issue. Correllating data from more than one company is even harder.

Document missing data and how it was massaged. Same for inaccuracies and structural issues.

Identify the amount of data needed to perform an analysis.

Identify other data impacts and methods to address.

Is there a way to tell if data is stale?

# 6. Data Analysis
Beware of automated feature selection! Although unrelated features may seem to have causality,  

# 7. Data Publication
Running data in a model  locally will result in very different team behavior from using your data in an operationalized model.



Other items to consider for a successful project:



