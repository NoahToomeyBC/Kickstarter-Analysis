# Kickstarting with Excel

## Overview of Project

### Purpose

In this project, we used different functions provided by Excel to pare down a rather large data set in order to gain a fuller understanding of what it takes to have a succesful Kickstarter campaign. First, we formatted the main "Kickstarter" sheet to make it more easily searchable for the following steps that we preformed. Through the use of filters we were able to better sort our data set for key variables that were most relevant to the project.  Using pivot tables, we were able to find ways to make our data more tabulated and readable for the common reader of the data set. Breaking it down further, we used multiple data charts that allowed an "at a glance" look at the data trends for some of the more important data sets.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To preform the analysis of the outcomes of Kick Starters based on the launch date, we used a pivot table in order to make the pertinent information more readily apparent we accomplished this through the use of the filters of parent category and years.

 We wanted to focus on the final out come of theater based Kickstarters per month so we added our outcomes to the columns section and again in the values section in order to have the counts for the different outcomes of the project. We further sorted that through adding the date created conversion into the rows section and removing "years2" and "quarters" to only show the relevant information of months. Since we already have a filter in place for the years it would have been unneccesary and cluttered to add that again. Also, quarters were unneccesary to have in as I would consider what months are in each quarter to be common knowledge.

![Pivot Table for Launch Date Analysis](C:\Users\noaht\Desktop\Class_Files\module1\lda.png)

### Analysis of Outcomes Based on Goals

In order to perform our analyis of outcomes based on goals, we had to take a different approach in how we first broke down the pertinent data. Using a string \(not sure if im using that right\) of COUNTIFS functions we were able to search data from the relevant column on the main sheet. This allows us to see relevant information with multiple qualifiers on it to make sure we are getting the correct answer. For each of the cells we needed have COUNTIFS check first if it was in the range of the goal we set. then whether or not it was succesful, failed, or canceled. Lastly, we had the function check the sub-category column to make sure we were only looking at plays and not any of the many other subcategories. Next, we used thew sum function to add up all the cells in a given goal range From there, we found the percentage of relevant projects per goal range using a simple division function.

![Function and Data Table for Outcomes Based on Goals](C:\Users\noaht\Desktop\Class_Files\module1\OBG.png)

### Challenges and Difficulties Encountered
A sore point for me in this was VLOOkUP which didn't click for me while I was going through the lesson on my own but made much more sense after seeing it in action in class. Also, having to manually enter the values of the COUNTIFS function was a bit annoying but I couldn't find a way to automate it.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

People are much more likely to find success in months closer with Kickstarters closer to Summer with May having the most successful. However, this could be due to the higher amount of Kickstarters in being started in May. Also, while there is a much higher amount of Kickstarters in May, later months might find similar success with much less competition.

- What can you conclude about the Outcomes based on Goals?

The data preforms about how you would expect. With a higher goal as your starting point, your chances of success are much lower. There is also a spike in success rate in the 35000 to 45000 range likely due to those being established IPs that can expect more eyes on their Kickstarter.

- What are some limitations of this dataset?

The data in this dataset is very much quantifiable and gives us a good idea on what to expect from different price points and dates. However, it is missing important qualitative data that could give us a better picture. For example, are the highly profitable Kickstarters from established playwrights? Also, it's missing key quantitative data such as how much was spent on advertising and marketting these products. Adding genre's to the main table for all the theater Kickstarters would give us another level of analytics to go through.

- What are some other possible tables and/or graphs that we could create?

First we could make a table that compares the projects that raised money above and beyond what their goal was and compare that to the projects that failed. Also, we could group the amount of succesful theater kickstarters by nation to see which would be most appropriate to push out advertising to.
=======

>>>>>>> 37f727e36b2b1dd542f79ca8cdc82cc40495f6af
