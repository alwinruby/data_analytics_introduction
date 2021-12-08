# An Introduction to Data Cleaning


1. What is data cleaning and why is it so important?

  You will receive data from a variety of sources. This data will come in all different formats and, more often than not, it will comprise what’s known as “dirty” data. In other words, it won’t be ready for analysis straight off the bat—you’ll need to clean it first.

  What is dirty data?


    Incomplete data—for example, a spreadsheet with missing values that would be relevant for your analysis. If you’re looking at the relationship between customer age and number of monthly purchases, you’ll need data for both of these variables. If some customer ages are missing, you’re dealing with incomplete data.

    Duplicate data—for example, records that appear twice (or multiple times) throughout the same dataset. This can occur if you’re combining data from multiple sources or databases.

    Inconsistent or inaccurate data—data that is outdated or contains structural errors such as typos, inconsistent capitalisation, and irregular naming conventions. Say you have a dataset containing student test scores, with some categorised as “Pass” or “Fail” and others categorised as “P” or “F.” Both labels mean the same thing, but the naming convention is inconsistent, leaving the data rather messy.

    [The 7 most common types of dirty data and how to clean them](https://www.ringlead.com/blog/the-7-most-common-types-of-dirty-data-and-how-to-clean-them/)

  Garbage in, garbage out: The importance of data cleaning

    GIGO stems from the world of computer science, and simply means that if you put flawed data in, you’ll get flawed results out.

    [data experts spend a good 60% of their time on data cleaning](https://www.forbes.com/sites/gilpress/2016/03/23/data-preparation-most-time-consuming-least-enjoyable-data-science-task-survey-says/#7db7a8926f63)


2. key steps in the data cleaning process

    do some or all of the following:

      Delete unnecessary columns. Chances are, your dataset will contain some values that aren’t relevant to your analysis. For example, in an analysis of students’ test scores compared to hours spent studying, things like student ID number and date of birth aren’t relevant. You could simply delete the columns containing this data.

      Identify and remove duplicates. Duplicate data tends to occur during the data collection phase, so it’s important to filter them out.

      Deal with missing data. In the case of missing data, you can either delete the entire entry associated with it (i.e. delete the whole row which contains the empty cell), impute the missing value based on other data, or flag all missing data as such by entering “0” or “missing” in the respective cell. Each method for handling missing data has implications for your analysis.

      Remove unwanted outliers. Outliers are values that differ significantly from other values in your data. For example, if you see that most student test scores fall between 50 and 80, but that one student has scored a 2, this might be considered an outlier. Outliers may be the result of an error, but that’s not always the case, so approach with caution when deciding whether or not to remove them.

      Fix inconsistencies. As already mentioned, inconsistencies in data include things like typos and irregular naming conventions. You can fix these manually (for example, using the “Find and replace” function in Google Sheets or Microsoft Excel to locate one spelling or convention and replace it with another) or by creating a filter.

3. Cleaning your dataset

    1. Identifying and removing duplicates
    2. Identifying and handling missing data points

    
