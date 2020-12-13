# kickstarter-analysis

Kickstarter Data Analysis for Louise

Overview of Project
Louise is planning campaigns based off Kickstarter data to discover trends. We are conducting 2 analyses for Louise, first to visualize campaign outcomes (successful, failed or canceled) based on launch date and the second to visualize the percentage of outcomes of plays based on the funding goal amount on campaign launch. 



Purpose
The purpose of this analysis is to help Louise understand how different campaigns fared in relation to their launch dates and their funding goals.



Analysis and Challenges
The analysis was conducted through the use of various tools and functions within Microsoft Excel. First, we organized the data sets to include additional information to perform accurate analysis Louise is looking for such as Parent Category, Subcategory, Date Created Conversion, Date Ended Conversion and Years. This process required conversion of text to columns to break down Parent and Subcategories, customizing formula to output campaign created date and end date based on launched_at time stamp. The biggest challenge of the analysis was that there was plethora of rooms for mistakes when entering formulas manually. Once the data set was organized, we conducted the following as following.(Refer to the image below for the final visualization of the analysis)

/Users/ruihayashida/Documents/Bootcamp/Module 1/kickstarter-analysis/Resources/Reference1_ScreenshotForAnalysis.png
/Users/ruihayashida/Documents/Bootcamp/Module 1/kickstarter-analysis/Resources/Reference2_ScreenshotForAnalysis.png



Analysis of Outcomes Based on Launch Date
Analysis #1 (Theater Outcomes by Launch Date) broke down number of campaigns based on launch date. In order to meet Louise’s needs, the Pivot table was created to list the month of launch as rows, count of outcomes in columns and filters of Parent Category and Years. 
Note: “Live” outcomes were excluded from this analysis, which is simply filtered by column tables drop down on the pivot table. The final visualization looks like such as below. 
/Users/ruihayashida/Documents/Bootcamp/Module 1/kickstarter-analysis/Resources/Reference1_ScreenshotForAnalysis.png
 

Analysis of Outcomes Based on Goals
Analysis #2 (Outcomes Based on Goals) broke down number of plays that fell under bracket of dollar-amount ranges so projects can be grouped based on their goal amount. The ranges and the columns (refer to picture below) were manually created. Once the format of the table was set appropriately, we used =countifs() function to generate the count of campaigns that met specified ranges and the outcome. Lastly, we totaled number of plays that fell in each range using the =sum() function, then calculated percentage of each outcomes. The final visualization looks like such as below. 
/Users/ruihayashida/Documents/Bootcamp/Module 1/kickstarter-analysis/Resources/Reference2_ScreenshotForAnalysis.png

Challenges and Difficulties Encountered
Challenges and difficulties encountered throughout the analysis included accuracy of formulas and/or formatting of Pivot tables as a slightest mistake can cause the excel to generate erroneous data. We overcame these challenges by repeatedly reviewing the formulas and formatting of the Pivot table as well as double checking to see if the results matched the referenced screenshots in the module as a simple mistake such as missing a space or a comma could result in an error. Another difficulty we have encountered is that 



Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One of the conclusions one can draw about the Outcomes based on Launch Date is that June is the most reoccurring month of month the campaign is launched. Second conclusions one can draw from the analysis is that the month of October maintains 0% cancellation rate, although it has the second highest failure rate next to the month of December.Based on 


-What can you conclude about the Outcomes based on Goals?
Based on the analysis of Outcomes Based on Goals, we conclude that campaigns budgeted less than $1,000 tends to have the highest success rate comparative to other brackets of ranges while $45,000=$49,000 range marks the highest failure rate.Th overall success rate is skewed to the left, indicating that the success rate of the campaigns decrease as the goal increases.


- What are some limitations of this dataset?
One of the limitations of this dataset is that there is an outliers within the data. While the mean Goal marks $5,049, the maximum and the minimum of the data set ranges from $1,000,000 to $1. Another limitation this data set may include is that most campaigns were created between the years of 2009 through 2019 although the earliest created year goes back as far as 1970 which could skew the result of the analysis of these data sets. 


- What are some other possible tables and/or graphs that we could create?
Other possible tables and/or graphs that we could create include scattergrams for metrics such as "Goals" with a line of regression to forecast the outcome of an outcome for a potential campaign based on the historical data. Another graph that may be beneficial to the analysis of these datasets may be box plot, which will indicate variables and outliers. 
