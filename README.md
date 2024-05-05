# Customer Churn Analysis

### Project Overview
In this Excel case study, I investigate Databel's customer churn rates as a subscription-based business. Reducing customer churn is a top priority for Databel, and my task is to explore the data and provide insights to help the company understand and mitigate customer churn.

### Data Source
I will be working with two datasets from the telecom company Databel: the 'Databel - Aggregate' file and the 'Databel - Customer' file. By analyzing these datasets, my goal is to gain insights into Databel's customer churn rates, as reducing churn is a critical priority for this subscription-based business. Through exploring and combining data from these two files, I aim to provide actionable recommendations to help Databel better understand and mitigate customer churn.

### Tools (Excel)
- Data Cleaning
- Exploratory Analysis
- Pivot Table
- Dashboard

 ### Data Cleaning/Preparation
  In the intial data preparation phase, we performed the following tasks:
  1. Data Loading/Inspection
  2. Handling Missing Values
  3. Removing Duplicate Values
  4. Data Cleaning and Formatting
 
### Results

![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/a91ddd65-1ed1-4b13-ac3b-ea771acf23ca)

The table above displays the customer churn rate for databel, the churn rate is 26.86%, which means that approximately 26.86% of the company's customers churned or discontinued their service during the analyzed period.
A churn rate of 26.86% is generally considered quite high and could be a cause for concern for the company. It suggests that over a quarter of the customer base discontinued their service, which could impact revenue and growth significantly.

#### Churn Reasons

  ![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/3e29f017-2a00-4461-8b7d-e0abce053d24)
  
  This is a visualization that shows the breakdown of churn rate based on the reason customers provided.
  Since competitor gets highlighted a lot in our previous visual we would be focusing on this category.
  
  ![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/13a9f818-ff96-4384-af79-35869be637c6)

This pie chart presents an analysis of the reasons why customers churned or switched to a competitor's service.
The chart highlights that the two most significant factors driving churn were competitors offering better devices and making better overall offers, which together account for over 74% of the churn. Network performance factors like download speeds and data allowances played a smaller but still notable role in influencing customers to switch to a competitor's service.
Overall, this analysis suggests that to improve customer retention and reduce churn, the company should focus on enhancing its device offerings, improving the overall value proposition of its plans and services, and ensuring that network performance meets customers' expectations for download speeds and data allowances.


#### Customer churn rate by demographics

![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/0d1bc8fa-10e3-4b5b-8542-b586d8b9ca1e)

This chart shows that the company experienced the highest churn rate among the senior customers, followed by the "Other" demographic group, and the lowest churn rate among customers under the age of 30 demographic.
This information could be valuable for the company to understand which demographic segments are more prone to churning and may require targeted strategies or offerings to improve customer retention within those specific groups.

#### Customer churn rate by age groups

  ![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/b1c814a4-c861-4b77-bbba-2db82a4e1fd3)

  The company is experiencing an alarmingly high customer churn rate of around 50% in the oldest age group of 79-88 years old, despite this group having the smallest customer base compared to other age ranges. There is a significant spike in the churn rate for the 69-78 age range, reaching nearly 50%, despite the number of customers in this group not being substantially lower than some of the younger age ranges. This indicates a significant retention problem specifically with senior customers over the age of 69.
While the churn rates for other age groups (19-28 to 59-68) are relatively lower at 20-30%, the spike in the 69-78 range is a major outlier and cause for concern.

#### Unlimited Data Plan

![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/e5507679-f937-4841-85e2-f38d5d8eac23)

The table above shows that the customers on unlimited plan are more likely to churn, with a churn rate of 32.11%.
To see if it is related to a certain amount of mobile data (GB) being used, an analysis was made

![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/e156811f-7e48-467a-894a-61c677103f69)


The churn rates for unlimited data plan customers vary significantly based on their data usage levels. Customers in the moderate usage range of 5-10 GB per month have the highest overall churn rate at 33.37%, followed by lighter users consuming less than 5 GB at 22.86% churn rate. Surprisingly, the heaviest data users consuming 10 GB or more have a relatively lower churn rate of 27.68%, closer to the overall average.
This suggests that customers with moderate to light data usage on unlimited plans are more prone to churning compared to the heaviest data users. 

#### customers' international activity and churn
Sum of Churn Rate %	International Plan

![image](https://github.com/Ayodeji199/CustomerChurnAnalysis/assets/155935474/617e85a2-2e93-456b-93a0-cbcc036a70c4)

Based on the table, many states seem to have a considerable percentage of customers on international plans who have churned or canceled their subscriptions. The churn rates for international plan customers are quite high across numerous states, with several states having churn rates above 50%, and many others having rates between 25-50%.


