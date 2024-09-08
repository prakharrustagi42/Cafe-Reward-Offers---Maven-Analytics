# Maven-Analytics-Power-Bi-Project

PROJECT LINK : https://mavenanalytics.io/project/18985

**4) KEY OBSERVATIONS:**

**1)** The Customers were segmented into 3 age groups and 3 income groups as per their demographic information. Out of those groups the majority customer base was(the one with highest sales):

**Family Adults Males (Age: 36-59) with 60k-90k income and joined in 2016**

 a) Age Groups: Adults, Family Adults and Elderly
 b) Income Groups: Low(<60k), middle(60-90k) and High
 c) Customer Segment: New, Strong (2016-2017) and Loyal(2013-2015)

**2)** Almost 38% of the transactions were offer related, generating $680k in sales, with $162k worth of rewards being availed.

**3)** The sales peaked when offers were sent to the customers. The peak was better and effective after the first 14 days(2 weeks), indicating customers were ready to invest in cafe products again and complete offers. Additionally offers were sent every 3-5 days after the first 2 weeks.

**4)** Offer with DD ratio <=1 performed better and were converted with higher rates:
    **DD RATIO :**

    Going through the dataset I was able to see how customer's transactions were according to the different offers. One thing that came in front was that for offers where the difficulty was proportional to the       duration, the offer completion rate was higher i.e. those specific offers performed better.
    
    For example:
    
    Bogo offer - 9b98b8c7a33c4b65b9aebfe6a799e6d9:
    The difficulty here was $5 and the duration was 7 days, making DD ratio to be 0.7
    
    Discount Offer - fafdcd668e3743c1bb461111dcafc2a4:
    The difficulty here was $10 and the duration was 10 days as well making the DD ratio 1.0 .
    
    For offers where the DD ratio was less than or equal to 1, the offer's completion rate was higher (always over 50-60%)

**Hypothesis :**

For offers where DD ratio was <= 1, customers treated the offer as spending $1/day or even lesser. This triggered the thought of the transaction being reasonable/justifiable (as most customers are middle age) and the offer being an added bonus.

**5) RECOMMENDATION:**
**a)** Offers formulation for future should follow the DD ratio rule of the ratio being less than or equal to 1.

**b)**  For the first two weeks, only informational offers should be sent (as they have substantial view rate and no reward amount), and as we progress towards the 15th day, bogo and discount offers should be sent through all channels every 3 and 5 days.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


About this project

**1) Dataset :**

Data that simulates the behavior of Cafe Rewards members over a 30-day period, including their transactions and responses to promotional offers. The data is contained in three files: one with details on each offer, another with demographic information on each customer, and a third with the activity for each customer during the period. The activities are divided into offer received, offer viewed, offer accepted, and transaction. For a transaction to be attributed to an offer, it must occur at the same time as when the offer was "completed" by the customer.

**2) Objective :**

Given Cafe Rewards the objective was to identify key customer segments and develop a data-driven strategy for future promotional messaging & targeting.



