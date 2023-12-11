# README for prompt.ipynb
---

## Overview:

<p>‘prompt.ipynb’ is a Jupyter Notebook file that uses data from the UCI Machine Learning repository. The data was collected through a survey that utilized Amazon Mechanical Turk. This survey data collected various details about drivers such as their age, income, education status, and relationship status, and their driving habits such as if they had passengers, what their destination was, etc. The drivers were also asked to accept a coupon for different types of establishments.  

The purpose of this notebook was to find which customers are more likely to accept a coupon. Specifically, I focused on coupons for a bar and a coffee house.  </p>
---

## Data Exploration:

<p>I explored a few variables for each coupon type to find the target audiences that would be more likely to accept a coupon.  </p>

### Bar

<p>At a high level, 41.19% of drivers accepted a coupon for the bar.  

As part of data exploration, I discovered the following:  
- Drivers who went to a bar fewer than three times per month accepted a bar coupon 89.91% of the time. Drivers who visited a bar more than four times per month accepted a bar coupon 10.08% of the time.
- Drivers over the age of 25 who visited a bar more than once per month accepted a bar coupon 21.07% of the time. Acceptance rates for this age group are highest (56.94%) when they visit less than once per month.
- Drivers who had a passenger who was not a kid, and had occupations other than Farming, Fishing & Forestry accepted the bar coupon 71.79% of the time.
- Drivers who visited a low-scale restaurant (less than $20) more than four times per month and who have an income of less than $50,000 accepted the bar coupon 45.35% of the time.
    </p>

### Coffee House

<p>At a high level, 49.63% of drivers accepted the coupon for the coffee house.  

As part of data exploration, I discovered the following:  
- Drivers who visited a coffee house fewer than three times per month accepted the coffee house coupon 77.75% of the time. Drivers who visited a coffee house more than three times per month accepted the coffee house coupon 22.25% of the time.
- Drivers over the age of 25 who visited a coffee house more than once per month accepted the coffee house coupon 35.12% of the time. Drivers over the age of 25 who visited a coffee house less than once per month accepted the coffee house coupon 39.02% of the time.
- Drivers between the ages of 21 and 29 who visited a coffee house less than three times per month were more likely to accept a coupon, however, accepted a coupon 24.49% of the time.
- Drivers with no urgent destination accepted a coupon for the coffee house 53.80% of the time, compared to drivers who were driving to work, and accepted the coffee house coupon 22.93% of the time.
- Drivers with no urgent destination who visited a coffee house less than three times per month were more likely to accept a coffee house coupon and accepted it 42.11% of the time.
- Drivers with some college experience (but no degree) or who have a Bachelor’s degree accepted the coffee house coupon 68.24% of the time.
- Drivers who were alone accepted the coffee house coupon 56.53% of the time.
- Drivers who visit a takeout (or carry-away) restaurant more than four times per month and who makes between $25,000 - $40,000 are 14.20% likely to accept the coffee house coupon.</p>
---

## Conclusions:

### Bar

<p>Drivers are more likely to accept a bar coupon if they:  
- Have a passenger who is not a kid
- Visit a bar fewer than three times per month
- Visit a low-scale restaurant more than four times per month
- Have an income less than $50,000  

Age did not impact marketability much, however, drivers over the age of 25 who never visit a bar are more likely to accept a bar coupon, and more specifically, drivers between the ages of 21 and 31 are more likely to accept a bar coupon if they visit a bar more than once per month.  </p>

### Coffee

<p>Drivers are more likely to accept a coffee house coupon if they:  
- Are over the age of 25
- Have some college experience or a Bachelor’s degree
- Do not have a passenger with them
- Do not have an urgent destination
- Visit a coffee house less than three times per month  </p>
---

## Use

<p>This data could be very beneficial for a marketing campaign in which the business intends to drive ads for a bar or coffee house in the area based on the driving habits of the population.  </p>
---

[Find this notebook here.](https://github.com/tzasquatch/tza-port/blob/main/prompt.ipynb)
