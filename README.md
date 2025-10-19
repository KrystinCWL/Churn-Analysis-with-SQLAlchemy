# Customer Churn SQL Analysis

This project demonstrates how to analyze customer churn data using **SQL**, **Python**, **Pandas**, and **SQLAlchemy**.  
It simulates a real-world data analysis workflow — from importing CSV data into a database to running analytical SQL queries.
<!It simulates a real-world data analysis workflow — from importing CSV data into a database, running analytical SQL queries, and visualizing insights.>
---

## 📊 Project Objectives
- Practice SQL query writing for business-driven data analysis
- Use Python and SQLAlchemy to execute and analyze queries
- Explore customer churn patterns (contract type, payment method, dependents, etc.)
- Demonstrate data querying and reporting automation

---

## 🧠 Technologies Used
- **Python 3.10+**
- **Pandas**
- **SQLAlchemy**
- **SQLite (Local database)**
- **Jupyter Notebook**
- **Google Colab**

---

## 📂 Project Use Case in Marketing: Customer Churning
Customer churn (customer attrition) is the percentage of customers who stopped using the company's product/ service during a certain time frame. It is calculated by dividing the number of customers lost during a particular time period by the total number of customers in the beginning of that time period. For example, if there were 1000 customers at the start of the year and 900 remained at the end, the churn rate is 10% because 10% of the customers were lost. The organization would always aim for a churn rate as close to 0% as possible and would consider churn rate as a top priority. Hence, it is one of the most important measures for evaluating a growing business.  

The organization will face a problem if the customer churn rate is higher than the new customer acquisition rate. The full cost of customer churn includes both lost revenue and the marketing costs involved with replacing those customers with new ones. Hence, churn is expensive because organizations spend heavily to acquire new customers through sales and marketing efforts. Besides, it's always better to keep an existing customer than to acquire a new customer, as it is much easier to save a customer before they leave than to convince the customer to come back. Hence, reducing customer churn is the major goal of every business, and it directly impacts a company’s bottom line, with increased revenue and reduced acquisition costs.  

Different organizations can determine these indicators of churn, then use the data to predict the likelihood of customer churn. In a product-based industry, declining repeat purchases, reduced purchase amounts, and customer experiences from the relational feedback can be considered as important measures to predict churn. For example, a customer who has declined in recent visits and gives a lower rating after their latest shopping experience has an increased probability of churning.  

Thus, understanding customer churn will enable organizations to understand customer behavior properly, predict the risk of customer churn, and identify customers who can discontinue, etc. The accuracy of these techniques will be beneficial to the organization for implementing efforts related to retaining customers because the organization will not take any action if it is unaware of customer churn. These special retention efforts will result in increasing revenues for the organization.  

Considering the customer churn dataset, execute the following queries in Python

- **Q1**   Consider senior citizen, male, and churned customers whose tenure is greater than 60.  
      What is the average monthly charge for customers having a “DSL” Internet connection?  

- **Q2**    Consider the customers who have dependents and a partner and have opted for the call service.  
      What is the average amount for customers having “Mailed Check” as a payment method and “One year” as an agreement?  

- **Q3**    Consider the male and senior citizen customers whose tenure is less than 20 and who have multiple connections.  
      What is the total Monthly Service Charges of customers for each billing method (Yes/No)?  

- **Q4**   Consider the customers who have monthly service charges greater than 100.  
      How many male and female customers have dependents and no dependents?  

- **Q5**   Consider only female customers who have no dependents and have used the call service, and have preferred the electronic check method.  
      How many customers have churned and not churned?  

- **Q6**   Consider the customers who have call service and have preferred either the  electronic check method or the mailed check method.  
      How many male and female customers have no dependents and have multiple connections?  

- **Q7**   Consider the customers who have call service and have preferred either the electronic check method or the mailed check method.  
      What is the average tenure of male and female customers who have no dependents and have partners?  

- **Q8**   Consider only those customers who have an agreement for one year or two years only.  
      What are the maximum monthly service charges of customers who have made payments by the electronic check method?  

- **Q9**   Consider only those customers who have no internet connection, no online security, no online backup, and no device protection service.  
      What is the minimum total number of male and female customers who have a one-year or two-year agreement type?  

- **Q10**  What is the average total amount of male and female customers having a partner and a partner?
