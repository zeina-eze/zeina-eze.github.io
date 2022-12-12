### Ifood 

*The Brazilian ‘Doordash’ case study!* [**The Data Science Project Studio**](https://www.datacareerjumpstart.com/products/the-data-science-project-studio/categories/2150357707/posts/2158441592). 

### Introduction
A few weeks ago, I signed up for the Data Analytics Accelerator program hosted by Avery Smith. It is a project heavy program using a variety of Analytics tools including but not limited to Excel, SQL, Tableau. For my first project, I will play the role of a junior data analyst working with the marketing team for a real world company called ifood.

ifood, a leading Brazilian food delivery company founded in 2011, offers online food ordering and delivery to customers in both Brazil and Colombia. According to the book Business Despite Borders, "ifood became a synonym of food delivery in Brazil ''.

### Stakeholder Focus
The ifood Marketing department has run a variety of campaigns in the 2 year period specified. They have asked our analytics team to analyze the data provided using Microsoft Excel and provide insight to help them optimize their campaigns efforts & generate additional value to the company. Their department has set clear goals for the analytics team:
1. Determine which of ifoods campaign efforts proved to be the most successful in terms of customer response/retention.
2. Identify trends from this campaign that could possibly help to improve future campaigns and sales.

To realize this, I will first determine which campaign was most successful and then look for trends in 
1. Most popular products purchased
2. Highest purchase period. 
3. Income vs Spending.
4. Age groups.
5. Number of kids.

### The Dataset 
The dataset used was provided as a csv document by the Data Accelerator Bootcamp. It is a fictional dataset that spans a 24 month period from December 2014 through November 2016. It is provided for the purpose of this case study only.
 
The file was securely downloaded and stored with a clear file name in the format YYYYMM-ifood-data in Excel. 
 
The dataset contains 2205 Rows representing customers and 36 Columns representing information about customers (income, marital status, education level, date joined, number of kids and age), enrollment by campaign, products purchased and method used to place order (store, online, catalog order) as well as amounts spent. 

### Analysis
Dataset provided had already been cleaned. Before any effective analysis could be carried out, we had to do some data processing.
 
1. I inspected the dataset provided to verify  - it was relevant to business objectives and heading names were meaningful, clear and complete.
2. I created a copy of the dataset to ensure Raw data is not compromised during the cleaning and processing.
3. I tied each customer to a unique "CustomerID" for easy reference during calculations.
 
### Most successful Campaign effort
First we need to know which campaign effort was most successful.  
Using COUNTIF Statement to determine the number of Customers that signed after each campaign, we see that Campaign 6 was by far the most successful. Campaign 2 was least successful in comparison in terms of customer retention.
 
 
### Products purchased
Focusing on Campaign 6, Let us dive a little deeper to find a trend in terms of customer purchases. Wine and Meat were extremely popular with highest sales in Dollar amount. 
             
 
 
### Highest sign on period
 
Using Pivot Tables, I compared to see how many people joined in a given month of the year to those that joined after campaign 6. Notice that January shows the highest customer sign on period. There is a consistent decline in the last few months of the year.

 
### Spending based on Income
I used a scatter chart to determine if there is a relationship between customer spending and income. As expected, customers with higher income showed a higher spending tendency.
 
  
The R-Squared value is 86%, that means we can predict with 86% certainty, how much a customer will spend based on their income.
 
### Age Group
IF statement used to place the customers in one of four age groups (24-35, 36-50, 51-65, & 66+) based on the value in the "Age" column.       

 
### Marital Status. 
 Based on the spending pattern observed within age groups, I decided to filter down and focus on the group with the most spending potential (36-50) to understand why this group was spending SO much on Wine and meat products!          
         
As an extra, I Created a VLOOKUP tool that can take any Customer ID & provide the amount they spent.

### Data Insights  
Interestingly, Wine and meats were the most popular products purchased. Majority of the purchases were by Single people between 36-50 years of age. 
Most customers signed on in the month of January but there was a decline during the last few months of the year. This could possibly be attributed to the holiday season, where there are large family gatherings, more store visits and more cooking at home. 
Spending was proportional to income with 86% guaranteed predictability rate.

### Recommendations 
Based on observations during my analysis, my suggestions to the marketing team are as follows:
1. Strategies used during campaign 6 were most effective and the Marketing team should lean towards these strategies. 
2. Emphasis should be placed on advertising to people outside the 35-50 age groups to boost orders. 
3. Providing discounts to reward members during Holiday periods (e.g free delivery on orders over a certain amount) to attract customers to place larger orders. 

Thank you for taking the time to read through my analysis. I do hope it was informative and would love to hear back from you! Feel free to connect with me on LinkedIn, leave me a comment or email me at zeina.roz@gmail.com. 

More projects to follow!!

<img src="images/dummy_thumbnail.jpg?raw=true"/>

