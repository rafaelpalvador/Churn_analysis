# Churn_analysis

## The database evaluated is a company that provides services, the aim is to try to understand why or what the profile of the customer with the highest churn is. 

# First, upload the dataset to python to be able to evaluate it
![image](https://github.com/user-attachments/assets/1795901f-211a-4a8a-9d17-186fd3f29645)

# After the first analysis, remove the null data
![image](https://github.com/user-attachments/assets/36d7fb76-27f3-4c5b-b8ed-3ef72b786425)

## As the number of nulls was negligible compared to the number of correct lines, I swapped null lines for more frequent ones, taking into account the statistical mode option. 
![image](https://github.com/user-attachments/assets/e67f9036-1857-4ecd-bdc9-9eb0cd498e62)

# The first piece of data to be analyzed was basically to understand the amount of churn. 
### The graph shows that the churn rate is considerably high.
![image](https://github.com/user-attachments/assets/44557fb8-8a12-45b1-98f4-8519ad06f8bb)

# Distribution of churn by age
### Higher churn in extreme age groups: A higher proportion of churn is observed in the younger (under 30) and older (over 60) age groups. 
### Lower churn in the 30 to 50 age group: The 30 to 50 age group has a considerable proportion of customers who have not canceled their service. 
![image](https://github.com/user-attachments/assets/81546d1d-988a-4cbb-91dc-1e2e60624b04)

# Comparison of churn by Ternure and Mounthly Charge
### Customers with shorter tenure: There is a significant proportion of customers with shorter tenure (less than 20 months) who have canceled their service. This suggests that younger customers tend to have a higher churn rate.
### Customers with longer tenure: As tenure increases, the proportion of customers who cancel tends to decrease. This indicates that customers with a longer contract period tend to be more loyal to the service.
![image](https://github.com/user-attachments/assets/f93dee77-338b-4e56-8709-7c35da8823bf)

# Relationship between Tenure, Monthly Costs and Age.
### Tenure and Monthly Costs: There is a positive correlation between tenure and monthly costs, i.e. the longer a customer stays with the service, the higher their costs tend to be.
### Age group with the highest costs: The age group between 30 and 50 concentrates most of the customers with higher monthly costs.
![image](https://github.com/user-attachments/assets/271b6fef-1f13-4211-b772-a2985a16b6f4)

# What is the relationship between Mounthly Charge and Age in relation to churn?
### Customer Profile with High Churn Risk: Customers aged between 40 and 60 and with monthly fees of more than 100 dollars have a high risk of churn.
![image](https://github.com/user-attachments/assets/21e0b0b0-91d5-4246-95c4-23daa496e2d7)

# And finally, understand which type of contract has the highest churn rate
### Concentration of churn in monthly contracts: Most customers who have canceled their service are concentrated in the “Month-to-Month” category. 
### Lower churn in long-term contracts: Customers with one-year and two-year contracts have a significantly lower churn rate.
![image](https://github.com/user-attachments/assets/e7a44d2a-21f4-4f82-956f-74cf1c89f62c)

# Conclusion
## Type of Contract: Customers with monthly contracts have a significantly higher churn rate compared to those with long-term contracts (annual or biennial). The flexibility of monthly contracts, while attractive to many, appears to be a contributing factor to higher churn.

## Tenure: Customers with shorter contract lengths tend to have a higher churn rate. Customer loyalty increases with the length of the relationship with the company.

## Age: Although age is not the most decisive factor, there was a tendency for higher churn rates in the younger and older age groups.

## Monthly Spending: The relationship between monthly spending and churn was not so clear, suggesting that price is not the main factor in the decision to cancel the service.





