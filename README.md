# US Honey Production Dashboard

Interactive Dashboard Link: https://jerilynms.github.io/Honey-Production-Dashboard/

This Power BI dashboard provides insights into the production of honey in the United States between 2010 and 2021. Located near the top of the dashboard are averages pertaining to the production of honey during the specified timeframe, which can be controlled via the filter in the top right corner. These cards provide quick details for the number of bee colonies, pounds of honey produced, selling price, and the value of the stock of honey. Below these data points, are two bar graphs visualizing the supply and demand of honey in each state. By selecting one or multiple bars (while holding ctrl), you can see the corresponding values in the data cards above and the other bar graph for the state/s selected. 

Based on the bar graphs, we can see that several Midwest states, plus California, are the largest producers of honey. The states with the most expensive honey include Virginia, New Jersey, and Illinois. As expected, the states with higher supplies of honey have lower demand for the product, driving prices lower. This is also true in the inverse. However, there is some minor variation. For example, although Wyoming, Idaho, Minnesota, and Mississippi have much smaller supplies of honey than the largest producer, North Dakota, they have a lower average price than North Dakota. A different dataset with other related variables would need to be studied if we wanted to explain this variation. 

To prepare this data for visualization, I examined it in Power Query for nulls and blanks. Finding none, I focused on the data types for each column. The index column had the correct data type but was missing a title so I renamed the column. I changed the columns for average price and value of stock from a whole number to currency. All other columns were listed as whole numbers; however, some required updating to decimals.

Data obtained from Kaggle: https://www.kaggle.com/datasets/mohitpoudel/honey-production-in-us-20102021
