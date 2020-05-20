### Review the Data
As a Data Scientist you will be dealing with data day in and day out. In order to understand the data you will need to have the domain knowledge. Unfortunately many a times Data Scientists are technologists and have limited understanding of business domain. This is where the it is advised that DS partner with the Business SME to understand the data.

### Credits
- [“Discovering Knowledge in Data” by Daniel T."](https://www.amazon.com/dp/0470908742/)
- [Blog by Denis V. Batalov](https://aws.amazon.com/blogs/machine-learning/predicting-customer-churn-with-amazon-machine-learning/)

### Hypothetical Situation
You are Data Scientist working for a Mid-Size Cellphone povider - "Atizen". Market for cellphone services have become extremely competitive and your employer has started to lose out the customers to competition. An internal analysis has indicated that in the hyper-competitive *Atizen* MUST pro actively work on retaining the customers as once the customer has left it is virtually impossible to get them back due to the one year contracts they sign.

Business leadership has come up with a strategy that requires pro active customer reach out to prevent them from leaving *Atizen*. The customer care team was given the owner ship of the task to reach out to customers who are at a high risk of separation from *Atizen*. 

*Atizen* has roughly 7 Million customers. The customer care team is a 50 member team. It is practically impossible to call every customer to understand their risk of separation. A better strategy is needed!!!

You are given the task of understanding the historical data to come up with a report that will identify the current customers who have a high risk of separation. Here is how the data looks like.


### Task#1 Review the Test Data Set
-State:          the US state in which the customer resides, indicated by a two-letter abbreviation; for example, OH or NJ
-Account Length: the number of days that this account has been active
-Area Code:      the three-digit area code of the corresponding customer’s phone number
-Phone:          the remaining seven-digit phone number
-Int’l Plan:     whether the customer has an international calling plan: yes/no
-VMail Plan:     whether the customer has a voice mail feature: yes/no
-VMail Message:  presumably the average number of voice mail messages per month
-Day Mins:       the total number of calling minutes used during the day
-Day Calls:      the total number of calls placed during the day
-Day Charge:     the billed cost of daytime calls
-Eve Mins, Eve Calls, Eve Charge:       the billed cost for calls placed during the evening
-Night Mins, Night Calls, Night Charge: the billed cost for calls placed during nighttime
-Intl Mins, Intl Calls, Intl Charge:    the billed cost for international calls
-CustServ Calls:                        the number of calls placed to Customer Service
-Churn?:         whether the customer left the service: true/false

### Task#2. Open the file *churn.csv* to checkout the data & answer the questions?
- Do you think the data is balanced?  Meaning that number for Churn=True & Churn=False are somewhat comparable
- Do you think all of the columns play a role in determining if the customer will leave or not?

Was it easy to make out the nature of the data? Obviously no so in next steps we will analyze the data using Pandas and Matplotlib

### Task#3 Open the notebook  *data-analysis.ipnyb*
- Read the markup
- Execute the cell & try to understand what the visualization is revealing about the data



