# titanic_visualizations
Python-generated summary statistics visualizations regarding deaths of Titanic passengers

The Titanic was an infamous cruise liner which sunk in the North Atlantic Ocean in 1912. 1,500 of the roughly 2,222 people died in a horrific drowned ship. The data of these deaths are available online for statistics.

Summary statistics are used by data analysts to make sense of data. Python visualization libraries are used to find associations between two variables.
The following are possible:

 - evaluating mean and median, as well as differences
 - side-by-side plts
 - overlapped histograms
 - pair-wise comparisons for different variable types

Project:

Data is available online for the fare of each passenger and whether or not they survived. The fare is a quantitative value, and whether they survived or not is a binary value. 

titanic_summary.py does the following things:

- calculate mean diff of fares from survivors and victims
- calculate med diff of fares from survivors and victims
- generate a side-by-side boxplot comparison to show fares by survival
- generate overlapping histograms to show fares by survival.

Box Plots Data Summary:

The median fare of the survivors is higher than those of the victims. Median is a more accurate representation of the middle of the data as it is not affected by an increased number of outliers. Mean will change if there are many outliers and skewed data.

The upper quartile for survivors covers much more than the victims. Additionally, there are far more outliers in the surviving group than victim group. This suggests that the people who paid the most were more likely to be saved. That is a tragedy.

Histogram Data Summary:

This data shows the proportion of the passengers paying for each tiered fare amount. The highest proportion of passengers paid for the cheapest ticket options. This means that most of the passengers on board the Titanic paid for general fare, or the most basic ticket price. The number of deaths surpassed the number of surviving passengers in two bins: ~0-10 and ~25-45. The number of people who paid less than $10 were twice as likely to die. That is horrifying.

We see that the number of survivors is greater than deaths once ticket prices are greater than $50. This could be that those who paid for a more expensive ticket had access to amenities that saved them. 

Those who paid less than $45 for their ticket were more likely to die. Perhaps it is because they were in bunks that were disadvantageously located in the ship. The ship was so large, perhaps it is also possible that the news and orders to evacuate came slowly, with a lot of distorted messages, and they could not help everyone in time. 

Very few of the passengers in the highest paying group died. Almost none of the passengers who paid some of the highest amounts died. 

Conclusion:

It is not known where each of these people were on or around the ship when being saved or not. It could be that those who were rescued were in a better position to be saved because they paid a higher ticket price. 
