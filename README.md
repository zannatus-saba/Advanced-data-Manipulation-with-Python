# Advanced-data-Manipulation-with-Python

COVID-19 Pandemic in the United States
In my repository for Advanced Data Manipulation with R programming (https://github.com/zannatus-saba/Advanced-Data-Manipulation-with-R-programming), I scraped data from Wikipedia. This data came from a statistical summary with various data including job levels, umemployment rate, inflation rate. I will not scrape data for this work. Instead, import the data I exported in my repository for Advanced Data Manipulation with R programming (https://github.com/zannatus-saba/Advanced-Data-Manipulation-with-R-programming). So yes, I will copy the file from the other work over to this work. I will need to create a data directory.

Rename Columns 
Imported scraped_data.txt. Once imported, renamed columns like so: 

jobs_lvl change to jobs_lvl_1000

jobs_mth change to jobs_month

unemp_rate change to unemploy_rate

unemp_mil change to unemploy_mil

emp_pop change to employ_pop

infl_rate change to infl_rate_perc

snp500_mean change to snp500_mean_lvl

public_debt change to public_debt_tril

month leave it as is

Data Wrangling and Manipulation 

It is time to practice data wrangling skills with Python. 

Calculate the mean of jobs_lvl_1000. 

Calculate the median of jobs_lvl_1000. 

Select all columns that start with a j (i.e., (^j)) or contain an a (i.e., (a)). Save it as a new data frame named jobs_data_alt.

Using your newly created data frame jobs_data_alt, select months in which jobs_lvl_1000 was greater than 135,000.

Using Pandas piping notation, perform the previous two operations together and save it as a new data frame jobs_data_alt2. This means you should select columns that start with a j or contain an a and select months in which jobs_lvl_1000 was greater than 135,000. 

Please perform the following tasks. Do not use jobs_data_alt or jobs_data_alt2, but use the original data frame you initially created from the text file.

Using Pandas piping notation, select all columns that end with the letter l (i.e., l$) or contain the letter o (i.e., o). Additionally, select rows in which snp500_mean_lvl is greater than or equal to 3000. 

Using the query just performed, calculate the mean and median of jobs_lvl_1000. 
