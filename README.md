Enis Norman

Coffee Shop Sales Dashboard Breakdown

This Excel project consists of 3 primary objects, each containing its own set of tasks that will display various Excel skills 
such as Column creation, data sorting/filtering, pivot tables, Pivot charts, and slicers.

Objective 1: Preparing the data for analysis
  The data was first assessed to familiarize myself with the various fields. Filters were then set in place for each 
  column to allow for proper sorting, and to make the raw data easier to work with.

  -A new column was first added to the calculation portion of the dataset to represent REVENUE [Price * Quantity]. 
  The fill function then carried the formula downward through the remaining cells. The values were then formatted to currency with 
  2 decimal places accordingly.
  
  -I then extracted the values of Month, Month Name, Weekday, Weekday Name, and Hour by utilizing the =MONTH, =WEEKDAY, =TEXT, and =HOUR functions
  and added them to the calculations portion of the data set. Filters were then added to the calculated fields, as well as a distinct blue color to distinguish them from the raw data.

Objective 2: Exploration of Data/Pivot Tables
 In objective 2, the data is used to create pivot tables on a new sheet labeled "Dashboard" that will help showcase revenue by month, number of transactions
    by day of week/hour of day, and number of transactions and revenue by product type/category

    -Transactions by product category have been sorted descending by transactions, while transactions and revenue by product type
    have been sorted descending and filtered to the top 15 transactions.

    -As seen in objective 1, the sum of revenue column was formatted into currency with two decimal places removed and a comma set
    in place to represent the thousandth place.

    -All transaction IDs were set to COUNT instead of SUM to represent how many transactions took place on which day/time of day.


Objective 3: Dynamic Dashboard
  In objective 3, the previously created pivot tables are then used to create the appropriate pivot charts that will make up our dynamic dashboard.

  -First, revenue by month was used to create a line chart, and transactions by day of week/hour of the day were represented as column charts,
  and transactions by product category were displayed as a bar chart respectively. These charts were then assembled into a cohesive
  layout, including space to display the top 15 product types through the means of...

  -Slicers were then included and connected to each of the available pivot tables, that way, whenever a selection was made within any of the 
  silcers, the change could be viewed within the pivot charts in real-time.

  -Gridlines were removed, bar thickness was increased, data markers were included and legends were removed from charts to promote readability.

  General Analysis of Data:

  - With the help of the visualizations featured on our new dashboard, I can perform several deliberations fairly easily such as,
    the overall popularity of coffee and tea in each location, with espresso normally taking the lead in sales, Monday and Friday acting as
    top-selling days of the week, as well as lower transactions being made during the evening on most days. This data can be used
    to further understand the trends and demographics of each customer, which location they frequent most, top-selling products, what time of day
    our operation is most efficient, and many more insights as the business continues to grow.
