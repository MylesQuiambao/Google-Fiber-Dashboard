# Google-Fiber-Dashboard

## Project Background

This project uses anonymized data from Google Fiber, a telecommunications company, and aims to improve customer satisfaction, reduce call volume, and improve operational optimization. The dashboard that will be created must demonstrate an understanding of these goals and provide valuable insight for stakeholders about repeat caller volumes in different markets and the types of problems they represent.

### Objectives

- Understand how often customers are calling customer support after their first inquiry; this will help leaders understand how effectively the team can answer customer questions the first time
- Provide insights into the types of customer issues that seem to generate more repeat calls
- Explore repeat caller trends in the three different market cities
- Design charts so stakeholders can view trends by week, month, quarter, and year.

### The Data

To anonymize and fictionalize the data, the datasets the columns market_1, market_2, and market_3 indicate three different city service areas the data represents.

The data also lists five problem types:

- Type_1 is account management
- Type_2 is technician troubleshooting
- Type_3 is scheduling
- Type_4 is construction
- Type_5 is internet and Wifi

Additionally, the dataset records repeat calls over seven-day periods. The initial contact date is listed as Day 0. The other call columns are “Day (#)” where # of days since the first call. For example, Day 6 indicates six days since the first contact.

### Dashboard Summary

![image](https://github.com/user-attachments/assets/f68f1895-596d-4216-9cde-2f8f84b63ce3)

The first tab of the dashboard features two bar charts. The first chart visualizes the number of repeat calls the customer support team handles each month. 
This graph shows that most repeated callers call just one day after their initial call. 
The second bar chart shows the percentage of callers who initially call on each day of the week.
Most callers engage in their initial call on Mondays, which is what we see for January and February. However, this is different for March, when Wednesday was the weekday on which most callers would have their initial call.

![image](https://github.com/user-attachments/assets/aa7ad8e8-8299-466d-ac26-666dc67a4d22)

The second tab of the dashboard features 2 tables. The first table lets the user explore repeat callers by call date. The second table groups the repeat callers by market and problem type to provide more specific information on what market and what type of problems the callers are prompting repeat calls.

![image](https://github.com/user-attachments/assets/d0c90a3e-3953-4b9e-ba08-93855899a96d)

The third tab of the dashboard uses data from previous tabs to visualize further the problem types that generate the most repeat calls for different markets. 

![image](https://github.com/user-attachments/assets/d2d85692-c564-4cde-a186-5040e543e2eb)

The final dashboard tab includes two charts to visualize the number of Day 0 calls across markets and problem types and the first repeat calls across markets and problem types. This helps users gain insight into what markets and problems are generating calls in the first quarter of the year, as well as which ones are prompting customers to call again after the first contact. 
