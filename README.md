# Kickstarting with Excel

## Overview of Project 

### Purpose
	The purpose of this project is to perform analysis on kickstarter data to uncover trends.

## Analysis and Challenges


Performed analysis of kickstarter data set to determine Theater Outocmes by Launch Date and Outcomes Based on Goals. 



### Analysis of Outcomes Based on Launch Date


Cancelled launches remained constant below 10 for the entire calendar year.  



### Analysis of Outcomes Based on Goals



### Challenges and Difficulties Encountered
	
	When calculating the percentage of failed and successful goals, value of #N/A were returned for some cells. By applying the IFERROR function to those cells was able to return a value of 0%.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	From May to June successful launches spiked then continued to decline by the end of the year. 

	Failed launches followed the same trend as successful launches being off by 20% differential between the two, except in the month of December they were almost exact. 

- What can you conclude about the Outcomes based on Goals?
	
	Percentage of Successful Goals in ranges less than 1,000, 1000 to 4,999, 10,000 to 14, 999 and 15,000 to 19,999 were almost double the percentage of failed Goals. 

	The Percentage of Successful Goals equaled the Percentage of Failed Goals for the range 30,000 to 34,999. For Goals greater than 50,000 the percentage failed was almost 9x greater than the percentage successful. For Goals ranging from 25,000 to 49,999 there could be multiple factors contributing to the disparity, inconclusive data trend.    

- What are some limitations of this dataset?

	The Theater Based on Goals dataset is only for plays in the US, not including spaces or musicals. If the dataset included theater goals from other countries then possibly find global trends in theater launches for each subcategory across the calendar year.

- What are some other possible tables and/or graphs that we could create?
	
	We could create a histogram of Theater Outcomes by Launch Date comparing US to Great Britain \(GB)\. 


