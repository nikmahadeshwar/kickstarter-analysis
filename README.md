# Kickstarting with Excel
Name: Nikhil Mahadeshwar
## Overview of Project
In this project, we aimed to analyse Louise’s play Fever campaigns using the Kickstarter dataset by visualising outcomes based on the launch date and funding goals.
### Purpose
We are using graphical representation and analysis explaining how different campaigns fared in relation to their launch dates and their funding goals.
## Analysis and Challenges
We are visualizing campaign outcomes based on their launch dates and their funding goals. The Kickstarter data set has 4115 rows and 21 columns containing campaign categories, countries, outcomes, pledged, currency, creation date etc. In this project we have analysed Outcomes Based on Launch Date and Outcomes Based on Goals.
### Analysis of Outcomes Based on Launch Date
![alt text](https://github.com/nikmahadeshwar/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
* The above line graph demonstrates the Theater Outcomes based on Launch Date.
* X axis represents the months and Y axis represents the outcome of the months which are successful, failed and canceled.
* We filtered the Theater data from the Parent category and retrieved the outcomes which are successful, failed and cancelled for our Analysis.
* The graph depicts that in the month of May and June the outcome was most successful and there was no cancellation in the month of October. 
  Also, the graph shows that there were more failure in the months of May to August.
### Analysis of Outcomes Based on Goals
![alt text](https://github.com/nikmahadeshwar/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
* The above line graph illustrates the percentage of successful, failed, and canceled plays based on the funding goal amount.
* X axis represents the goal amount which ranges from 1 to 200,000 and Y axis represents percentage of plays outcomes which were successful,     failed and canceled.
* It highlights that 75% of the plays outcomes were successful when the goal amount was less than 1000.
* Maximum numbers of plays were successful when the range amount was below 20000.
* On the other hand, the graph shows that 50% of the plays were successful for the goal amount range 15000 to 19999.
  The graph also demonstrates that 80% of the plays were unsuccessful for the range amount of 25000 to 29999.
  
### Challenges and Difficulties Encountered
The Unix timestamps were converted into a day-month-year format.
The Category and Subcategory column was split into Parent Category and Sub Category.
Through the descriptive Analysis we were able to find: Mean, Median, Std Deviation, Upper Quartile and Lower Quartile of Goal and Pledge.
## Results
### Outcomes based on Launch Date
We can conclude from the line graph that theater outcomes were most successful in the Month of May and June.
Also, the most failed plays were in between the months of May to August and October.
### Outcomes based on Goals
The most successful group of Goal amount was less than 1000 and 1000 to 4999. It was almost 75% successful.
### Limitations of this dataset
The size of the dataset was limited as compared to the categories and subcategories depicting statistically irrelevant results.
## Conclusion and Future Work 
Finally, from this  project we can conclude that we have successfully analysed and visualised the kickstarter dataset for outcomes based on launch date and goal amount. In future we can explore and analyse the dataset according to the different  countries, categories, currencies and years.  
