# Python-Instacart-Project

Instacart, an online grocery store that operates through an app, wants to uncover more information about its sales patterns. They would like an exploratory analysis of some of their data to derive insights and form strategies for better customer segmentation. The Instacart stakeholders are most interested in the variety of customers in their database and their purchasing behaviors so that Instacart can launch a targeted marketing strategy.

## Key Questions

1. What are the busiest days of the week and hours of the day? What time is it best to schedule ads at?

2. What particular time of the day when people spend the most money? This might inform the type of products they advertise at these times.

3. Instacart has a lot of products with different price tags. Marketing and sales want to
use simpler price range groupings to help direct their efforts.

4. Are there certain types of products that are more popular than others? Which departments have the highest frequency of product orders?

5. Different types of customers and their ordering behaviors. 
    What’s the distribution among users in regards to their brand loyalty (returning customer)?
    Are there differences in ordering habits based on a customer’s loyalty status?
    Are there differences in ordering habits based on a customer’s region?
    Is there a connection between age and family status in terms of ordering habits?
    What different classifications does the demographic information suggest? Age? Income? Certain types of goods? Family status?
    What differences can you find in ordering habits of different customer profiles? 

## Key Python learnings from this project:

(4.3)

- Data Exploration

- Reviewing Data with DF.head(), DF.Tail() , DF.Describe(), DF.Intro()

(4.4)

- Data Wrangling :

- Dropping columns with df.drop()

- Searching for missing Variables with df.value_counts()

- Renaming columns with df.rename()

- Reviewing data types with  dtypes()

- Transposing data with DF'name'.T

- Formatting data dictionary: to_dict()

- Filtering for specific result

- Exporting data frame to CSV file

(4.5)

- Searching for mixed data types

- Missing Values: .isnull()

- Isolating for specific missing values

- Treating missing values: "Flagging" the variable, Replacing with mean or median, Remove or filter out data

(4.6)

- Concatenate Data DF_long , DF_Wide

- Joining Data

- Merging Data (Inner, Left, Right, Outer Joins)

- Exporting File with pkl format

(4.7)

- Creating new columns as a "flag". Ex: "if the item’s price is lower than or equal to $5, it will be labeled a “low-range product.”

- Limiting data shown to only a certain amount of rows. Ex: DF[:100] 

- Locate data with a particular result: DF.loc


(4.8)

- Viewing single columns

- Viewing These columns only

- Aggregating data: External table to show mean, min, max, mode

- Groupby - Simpler table than aggregating shown

- Transform function

- Frequency checks


(4.9)

- Renaming columns

- Checking for NaN (empty cells) - “Summing all empty cells within a column”

- View specific columns with NaN

- Replace all Null Values

- Creating bar charts, histograms, scatter plots, line charts

- Exporting charts

(4.10)

- Removing PII

- “If then statement”

- Filtering out data

- Create chart with ONLY this amount of data

- Customized Bar charts

- Organizing questions and answers all within a custom report that documents each step to get the information.




