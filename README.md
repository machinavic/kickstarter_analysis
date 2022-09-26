# Kickstarter_analysis
# Editing this README
# **Kickstarting with Excel**

Kickstarting with Excel is intended to apply all we learned to a dataset in order to get insights and translated to the final customer, in this case to Louise.

## **Overview of Project**

This project has two parts: the first one involves the usage of different tools in Excel as Pivot Tables, Pivot Charts, formulas among other ones to be applied to a Kickstarter dataset, and the second one to be applied to the Module 1_Kickstarter Challenge.

## **Purpose**

Taking into account that Louise wanted to know how different campaigns fared in relation to their launch dates and funding goals; for the new deliverables the workbook was renamed as Kickstart Challenge and the following actions were taken for the Deliverable 1:
- New column named "Year" was created based on data from "Date Created Conversion" column.
- A pivot table was inserted into a new worksheet filtering by "Parent Category" and "Years", on Rows the "Date Created Conversion" was entered followed by "Outcomes" in the Columns. All of these work showed the "Outcomes" value for the different type of Parent Category by months.
- The other step was to create a Pivot Chart- line chart to graph the Theater Outcomes based on the Launched Date.
- Chart was saved as .png format and data was analyzed.

However,  a similar job was developed for the deliverable 2, but specifically setting a range under the "Goal" column and applying the COUNTIFS formula to retrieve data from the dataset such as % of Successful, % Failed, and % Canceled, among other info. After this data manipulation, a line chart was created showing "Outcomes Based on Goals" for the different ranges.

## **Analysis and Challenges**

During this exercise, the only challenge gotten was to apply the COUNTIFS formula on the deliverable 2 because a little bit of info needed to be set up into its argument, but anything else other than that was difficult.
 
### ***Analysis of Outcomes Based on Launch Date***

For this analysis, these table and graph were gotten from the data provided in the Pivot Table:

![Theater_Outcomes_vs_Launch_table]

![Theater_Outcomes_vs_Launch]

As we can see in these images, only the Theater category was displayed showing almost everything had successful outcome during all collected years, however it had a peak on May, which gives Louise an idea on when to launch a successful play of this kind. On the other hands, other analysis could have been made here adding Descriptive Statistics parameters to expand this analysis a little bit more.

### ***Analysis of Outcomes Based on Goals***

The outcomes were split into 11 goals ranges, and applying COUNTIFS formula, then all results were gotten for the different scenarios requested such as % of Successful, % of Failed and % of Canceled. From all of these insights, we can see in the graph below, the Successful outcome has more likelihood when a goal is less than $4999, however Failed outcomes had bigger percentage of failure when the goal increased.
There is a curious case here, since the goal between $15000 to 19999 the successful and failed outcomes had the same percentage, so in this specific case Louise has to know that requests made on this range has 50% of probability to be successful or failed. See graph and table below:

![Outcomes_vs_Goals]

![Outcomes_vs_Goals_table]

### **Challenges and Difficulties Encountered**

Any difficulty was encounter, except the application of the COUNTIFS formula.


## **Results**

>- What are two conclusions you can draw about the Outcomes based on Launch Date?

*For the Theater category, the best month to launch the play is in May according to the dataset provided.*
*Theater has the lowest amount of canceled plays when all outcomes are compared throughout the whole year.*

>- What can you conclude about the Outcomes based on Goals?

*Plays with goals greater than $45000 has a big likelihood to be failed, and the most successful rates are on lower goals, less than $4999.*

>- What are some limitations of this dataset?

*This is not a limitation, but this dataset has a lot of categorical data that should be converted to a numerical for a better manipulation.*

>- What are some other possible tables and/or graphs that we could create?

*Tables and graphs are made according to the info the customer wants to know or the research's objective; but in this specific case a box plot could be applied as well.*
