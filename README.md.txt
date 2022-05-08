# Kickstarting with Excel

## Overview of Project

### How different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Firstly I opened the Kickstarter workbook and added a 'Years' column using YEAR() based on the 'Date created conversion'. I created a pivot table to display the 'canceled, failed and successful' results in the columns. 'Parent Category' and 'Years' as filters. 

/Users/graemerennie/Desktop/Screen Shot 2022-05-05 at 10.11.38 PM.png

I filtered 'Parent Category' to theater and changed the row labels to months of the year. The count of outcomes has been sorted in descending order.

/Users/graemerennie/Desktop/Screen Shot 2022-05-05 at 10.14.13 PM.png

Using this data, I created a line graph showing the outcomes based on Launch Date over one year.

/Users/graemerennie/Desktop/DATA CLASS/Kickstarter_Challenge/Resources/Theater_Outcomes_vs_Launch.png


### Analysis of Outcomes Based on Goals

Using COUNTIFS ()I populated the number of canceled, failed and successful columns 

/Users/graemerennie/Desktop/Screen Shot 2022-05-05 at 10.26.28 PM.png

/Users/graemerennie/Desktop/Screen Shot 2022-05-05 at 10.27.01 PM.png

/Users/graemerennie/Desktop/Screen Shot 2022-05-05 at 10.27.31 PM.png

/Users/graemerennie/Desktop/Screen Shot 2022-05-05 at 10.27.51 PM.png

I used =SUM(B2:D2) to populate the 'total projects' column.

=SUM(B2/$E$2) to calculate columns F-H.

This line chart shows the goal amount on the x-axis and the percentage amount on the y-axis.

/Users/graemerennie/Desktop/DATA CLASS/Kickstarter_Challenge/Resources/Outcomes_vs_Goals.png



### Challenges and Difficulties Encountered

The main challenge I faced was creating the formula on the 'Outcome Based on Goals' sheet. Specifically the COUNTIFS formula for cells B2:D13. I overcame this difficulty with trial and error until I had a working formula.



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May and June are the 2 months where we can see a high amount of successful kickstarter projects with a 67% and 65% success rate, respectively. October is the month with the most failed projects and a reasonably low number of successful projects. 

- What can you conclude about the Outcomes based on Goals?

Generally speaking, the lower the goal, the higher the success rate.

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

We could include a table comparing the 'average donation' and month to spot any correlation.
