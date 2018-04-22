# SSAS-Finance-Tabular
Creating a SSAS tabular model using SSAS and the AdventureWorksDW2016

Using a modified version of the AdventureWorksDW2016 data warehouse, I have created a Tabular model in SSAS called Finance.  Modifications made to the data warehouse:
1. Created a new schema called "Analytics" using SSMS
2. Created views (using SSMS) under the "Analytics" schema that were used as the staging area for the Tabular model.
3. Using Visual Studio Data Tools (SSDT), created a Tabular model and then deployed it to Sql Server Analysis Services (SSAS)

The model was built as a learning exercise after taking a course that taught some Tabular model basics.
