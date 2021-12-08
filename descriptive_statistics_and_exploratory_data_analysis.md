# Descriptive statistics and exploratory data analysis


  Calculate descriptive statistics
  Create pivot tables using different variables


What is exploratory data analysis?

  You can think of exploratory data analysis as an initial investigation of your dataset where you seek to understand and summarise its main characteristics. EDA is useful because it helps you to understand how your data is structured, to spot potential patterns and trends, and to catch any anomalies. EDA is also important for determining if the methods of analysis you are planning to use later on are actually appropriate for your dataset.


What are descriptive statistics?

    In a nutshell, descriptive statistics help you to summarise or describe the characteristics of your dataset in a meaningful way.

    Imagine you have a dataset containing hundreds or even thousands of values. It would be impossible to look at that raw data with the naked eye and make any sense of it.

    For example, if you collected data on the test scores of three hundred students, you might want to gauge their overall performance. You wouldn’t be able to do this simply by looking at a spreadsheet with all the raw data, but you could calculate the average (or mean) score. That’s an example of descriptive statistics!

    Descriptive statistics are also useful for spotting potential errors or strange occurrences within your dataset. For example, in calculating the minimum and maximum values for a certain variable, you might notice that the maximum value falls outside of what could be considered a reasonable range. Imagine you’ve collected height data for a group of school children and calculated a minimum value of 20cm. That doesn’t seem like a realistic height for a child. Based on that, you’d investigate further to see what’s going on (and make sure that your dataset is in a fit state for analysis)


What are the different types of descriptive statistics?

  The three main types of descriptive statistics are:

    * Frequency distribution, which tells you how frequently (i.e. how many times) a certain value occurs within your dataset.

    * Measures of central tendency, which estimate the middle or average values within your dataset. Measures of central tendency are the mean, median, and mode.

    * Measures of variability help you gauge how much variability or “spread” there is within your dataset; in other words, how spread out the values are. Measures of variability are range, standard deviation, and variance.


What is a pivot table?

    A pivot table summarises large amounts of data in a more digestible, at-a-glance format. It does this by grouping the data in a meaningful way, for example by showing the sum or average values of certain variables.


## Descriptive statistics and pivot tables


    1. What are the most popular locations across the city for Citi Bike rental?
    2. How does the average trip duration vary across different age groups, and over time?
    3. Which age group rents the most bikes?
    4. How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week?


    descriptive analysis using the following columns (variables) in our dataset:

    Start station name (this indicates where the bike was picked up from)—column D in your dataset
    Age (of the user)—column J in your dataset
    Month—column N in your dataset. Each month of the year is denoted by a number, so January is represented by 1, February by 2, and so on.
    Season (spring, summer, autumn, or winter)—column O in your dataset
    Trip duration in minutes—column M in your dataset
    Our analysis will consist of two parts:

    Calculating some of the descriptive statistics we covered earlier on: the mean, median, minimum, and maximum values for two variables of interest (trip duration in minutes and user age).
    Creating pivot tables to summarise our descriptive statistics.


**Create pivot tables**

    What are the most popular pick-up locations across the city for Citi Bike rental?
    How does the average trip duration vary across different age groups, and over time?
    Which age group rents the most bikes?
    How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week?


    In task 2.1, you created a pivot table to show the top 20 most popular pick-up locations for Citi Bikes. You looked at the frequency of the variable “Start Station Name.” Key finding: Grove St Path is the most popular pick-up station.

    In task 2.2, you created a pivot table to see how bike trip duration varies (a) across different age groups, and (b) over time. First, you looked at the average trip duration in minutes for each age group. Key finding: Over 75s took the longest trips on average. You then looked at the average trip duration in minutes for each month of the year. Key finding: On average, Citi Bike users took the longest trips in September and the shortest trips in January.

    In task 2.3, you created a pivot table to see which age groups rented the most bikes. You looked at the count of each individual bike ID across each age group. Key finding: 35-44 year olds rented the most bikes.

    In task 2.4, you created a pivot table to see how bike rental varies across the two Citi Bike user groups (one-time users vs. subscribers) on different days of the week. You looked at the variables “Weekday,” “User Type,” and count of “Bike ID.” Key findings: Most Citi Bike users are long-term subscribers. With this more complex pivot table, it’s not so easy to get the insights you need. This is where data visualization helps
