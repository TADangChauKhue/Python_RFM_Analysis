# Python_RFM_Analysis
Analyze segmentation customer bases on RFM model to help Marketing team to deploy suitable marketing program for each customer group.
## Introduction
SuperStore is a UK-based and registered non-store online retail. In this project, I use Pandas, Numpy to conduct Customer segmentation analysis by exploring Transactions dataset with the help of RFM Model. I also use Seaborn & Matplotlib to visualize insights into comprehensible charts.

**1.Business question**

•	SuperStore is a global retail companu. The Makerting Department wants to run makerting campaigns during the Christmas and New year holidays to thank customers for their pas support of the company. In addition, potential customers can be exploited to become loyal customers.

•	The makerting Director also proposed a plan to use the RFM model in Python to segment customers, and then launch appropriate marketing campaigns. Analyze the current situation of the company  and give suggestions to the Makerting team.

•	With the retail model of the Superstore company, which indicator should be most focused in the 3 indicators R,F and M?

**2.Dataset**

Dataset  is one table containing all the transactions occurring between 01/12/2010 and 09/12/2011 and RFM classification.

1.Transactional information dataframe

![image](https://github.com/TADangChauKhue/Python_RFM_Analysis/assets/151337392/96fe708d-510f-4831-8bab-96f2660a62e4)


2.Segmentation dataframe

![image](https://github.com/TADangChauKhue/Python_RFM_Analysis/assets/151337392/692511dd-561f-4483-b5da-6eef203fd27b)


We have to split each RFM score into single rows

**3.Method: RFM Analysis**
•	RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries

•	RFM stands for the three dimensions:

1.	Recency-How recently dis the customer purchase?
2.	Frequency – How often do they purchase?
3.	Monetary Value – How much do they spend ?

## Data Visualization
 
![image](https://github.com/TADangChauKhue/Python_RFM_Analysis/assets/151337392/70655b1f-edd4-4935-83ac-bc7b6ff211aa)


![image](https://github.com/TADangChauKhue/Python_RFM_Analysis/assets/151337392/f5b01fd5-aa1d-4c54-a834-9272dc568c3c)


 ![image](https://github.com/TADangChauKhue/Python_RFM_Analysis/assets/151337392/1c056807-f871-44b0-87a4-8743c00851fa)


## Insights

**1.Recency, Frequency and Monetary value of Superstore:**

•	As a retailer Superstore should prioritize Recency and Frequency over their Monetary since the  their most loyal shoppers may make many purchases throughout the year at lower Average Transaction Sizes. However Superstore’s recency and frequency do not have many positive signs.

•	Mean of Frequency is 4.2 times which is low for a retail company. This means customer loyalty is not high.

•	Mean of Recency ~112 days this represents a lot of high recency values. The larger this index the higher the customer’s tendency to leave.

**2.11 segments of Superstore:**

•	2 segments with the highest proportion of customers are Champions (19.22%) and Hibernating customers (15.97%).

•	Negative segments such as Hibernating and Lost accounted for a high proportion of customers, 15.97% and 9.77% respectively. However, thses two groups account less then 10% of revenue.

•	The two most positive segments account around 30% of the proportion of customer. Champions (the ideal segment) has the highest proportion of customers (19.22%à and it’s revenue proportion is 62.92% so marketing team has to focus the effort on this segment.
