# fall-temperature-trends-twin-cities
## Research Question
Are the number of days where the maximum temperature exceeds 75F increasing over time?
## Data
The daily data is from Minnesota DNR, spanning all the way from 1880 to the present day. I manually downloaded the data off of the DNR website, the data is provided in chuncks of decacdes. 
#Statistic
The annual number of fall days with maximum temperature greater than or equal to 75F.
#Hypothesis: Permutation
Null: The mean number of days greater than 75F fall days is the same both before and after 1950.
Alternative: The mean number of days greater than 75F is higher after 1950.
#Hypothesis: Bootstrap
Null: The long term trend in days greater than 75F fall days is 0.
Alternative: The long term trend is greater than 0.
#Methods
Data cleaning in python with pandas.
Exploratory data analysis and visualization. 
Permutation and bootstrap tests. 
#Results
The permutation test failed to reject the null yielding a p value of .99. There is no detectable increase in warm fall days after 1950. The bootstrap confidence interval for the slop eincludes 0, suggesting there is a small upward trend, but the trend is small and uncertain. 
#Limitations
Results are from one single station in minnesota. Temperature recording methods may have changed over time, starting maual in 1900 to likely automatic detection these days. 
