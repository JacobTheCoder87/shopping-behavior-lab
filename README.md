# shopping-behavior

In this project, I will assume the role of a junior data analyst at FlashFash, delving into the seasonal shopping behaviors of US consumers. The primary objective is to extract insights that will facilitate our company's expansion into the US market. The focus lies in identifying the most frequently purchased items and their associated attributes across different seasons. The project unfolds in three key phases: initial data exploration, followed by thorough data cleaning and transformation, and concludes with a comprehensive data analysis.

## Observations 

In our initial step, I explored our data using various methods such as printing out summary statistics, conducting univariate analysis using histograms and bar charts. I also performed bivariate analysis with box plots and kde plots. Throughout this exploration, I discovered many interesting facts about our data. For example, I found that the Winter season sees the most purchases, and our shoppers are generally quite young, falling between the ages of 28-32.

In the second step, I began cleaning and transforming our data. I identified and addressed null values, dropped columns with too many missing values, and created two groups within our review rating column to distinguish between missing and present reviews. This segmentation sets the stage for a more refined analysis in our third step.

In the third step, I delved deeper into our data. I created pivot tables to view our data based on specific parameters we chose. For instance, I explored the items people purchased the most during different seasons through a dedicated pivot table. I also split our data between promo code users and non-promo code users, forming new dataframes. I formulated hypotheses about the dollar amount spent by these two groups and, through analysis, made interesting discoveries. For instance, a T-test revealed potential differences in the dollar amount spent between promo code users and non-promo code users.

I encountered several challenges during this lab, particularly in the data cleaning phase where I had to replace values in our columns. This involved handling null values by replacing them with 'missing' and non-null values with 'present.' Additionally, in the third part of our analysis, I faced difficulties grouping various columns and values together.

As I move on to the next step of my project, I plan to explore how I can effectively communicate and apply my findings within the company. The goal is to identify areas where we can implement strategies to successfully penetrate the American market.