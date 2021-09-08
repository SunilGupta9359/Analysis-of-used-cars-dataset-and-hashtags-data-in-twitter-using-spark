# Analysis of used cars data and hashtag data in twitter using spark in HDP and jupyter notebook.

# TECHNOLOGIES USED 
* APACHE 
* SPARK
* HDFS
* SPARK SQL
* JUPYTER NOTEBOOK
* PYTHON
* HIVE

# PROBLEM STATEMENT :
We are having a data set of used cars . We need some insights from the data set and the insights we needed are  given below. And also we some analysis on some hashtags data in twitter . The hashtags and the insights were given below.

# DESCRIPTION : 
* Took 'used cars' dataset from kaggele.
* Loaded the data set into sandbox as a CSV file.
* Loaded the data into a data frame and did some functions on the data set.
* By creating a temporary table performed some SQL queries on the table.
* Created our own data on hashtags data using tweepy library from twitter.
* Using jupyter performed some dataframe functions on the created dataset.
* Also used spark SQL on the created data to analyze.

# INSIGHTS : 
* The highest price and the lowest price of the cars.
* Region having the highest number of cars.
* Cars which are manufactured by Mercedes-Benz or Ferrari and  black in color.
* Cars whose manufacturer name starts with name ‘m’ and price more than 100000.
* We need a new column which has the fields two times of its price.
* Rename the column ‘odometer’ of our data set to ‘odometer value’.
* Count of cars from region “auburn” which covered a distance greater than  70000.
* Region where the models ‘f-150’ or ‘compass’ , ‘Tacoma’ were available in black color. 
* Data of manufacturer ,model , transmission where price is greater than 50000.
* Model of the car which was purchased mostly.
* Region which is having the highest number of cars.
* Region which is having the highest number of cars.
* In a particular year which color cars are the most sold.
* Count of cars posted in different years.
* count of cars according to their conditions for a particular manufacturer.
* We need our data to be partitioned on the basis of state.
* We need our data to be bucketed into 50 buckets based on id.
* Write our  data into a parquet file and using that give the count of cars year-wise.
* Write our  data into a json file.
* We are having some IPL data in hive . Get that data to here and give that to us in a csv file.
* We need our data to be partitioned on the basis of posting month.

# HASHTAGS FOR TWITTER DATA ANALYSIS
* #RohitSharma
* #Teachersday
* #SiddharthShukla

# Insights for hashtags data : 
* Get the count of locations from where the tweets came on #rohithsharma.
* Get the name of the user with high number of followers who gave #siddharthshukla.
* Get the count of locations from where the tweets came on #teachersday.
* To get the trending the topics of India in tweeter.
