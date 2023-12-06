# Home_Sales

Brian Guenther

In this challenge, I read in a large csv data file, containing information about homes sales, into Spark and created a Spark dataframe.  SparkSQL was used to answer several questions regarding average price of homes, which were sorted on differing criteria.  Additionally, the runtime of the query was compared using uncached, cached, and partitioned data.  Arguably due to the size of this dataframe, the runtime differences between the different approaches feel within the differences of runtime seen when running the notebook at different times with different resources available in Google Colab.  Although partitioning the data on different column, such as view in this analysis, should have more of an effect on runtime.

Regarding completion of the assignment, I did review SQL concepts and order of operations with the tutor.  Otherwise this assignment was completed based upon class material.