# Practical-Application-Mod-5
This is the Practical application in which a survey data is analyzed to determine which drivers will accept what type of coupon

## Files:
1. **pa5_1.ipynb** - jupyter notebook used for anlyzing the coupons data  
2. **data/coupons.csv** - data file having survey data


## EDA (Exploratory Data Analysis):
### 1. Investigating the dataset for missing or problematic data
<img width="574" alt="Screen Shot 2024-10-07 at 11 47 22 PM" src="https://github.com/user-attachments/assets/a6ac2f39-e047-47c2-83f3-e4be305e646e">  
  
* Dropped 'Car' column since it had 99.14% missing records

### 2. Visualizing coupon column data
<img width="581" alt="Screen Shot 2024-10-07 at 11 56 55 PM" src="https://github.com/user-attachments/assets/8fc58bbb-4704-45aa-991d-839e17640f42">

### 3. Histogram of Temperature data
<img width="593" alt="Screen Shot 2024-10-08 at 12 01 52 AM" src="https://github.com/user-attachments/assets/efa54f92-36c6-41f8-8902-2dc5128bfb19">


## Bar coupon analysis:

### 1. Bar coupon acceptance ratio
![bar_coupon_acceptance_pie_chart](https://github.com/user-attachments/assets/9b6131bb-ffab-4076-83d1-2f840668990d)

### 2. Bar coupon acceptance rate of "drivers going to bar 3 or fewer times a month" VS "drivers going to bar more than 3 times a month"
<img width="612" alt="Screen Shot 2024-10-08 at 12 05 05 AM" src="https://github.com/user-attachments/assets/9cec6e0b-8a89-45fe-b83d-6d485b04f572">

### 3. Bar coupon acceptance rate of "drivers who go to a bar more than once a month and are over the age of 25" to the "all others"
<img width="654" alt="Screen Shot 2024-10-08 at 12 07 00 AM" src="https://github.com/user-attachments/assets/c5d94ced-c16d-4995-a4eb-3be0620f5d14">

### 4. Bar coupon acceptance rate of "drivers who go to a bar more than once a month and had passengers that were not a kid" VS "drivers who go to a bar more than once a month and had occupations other than farming, fishing, or forestry" 
<img width="320" alt="Screen Shot 2024-10-08 at 12 09 21 AM" src="https://github.com/user-attachments/assets/921bf9d8-af30-4ee3-91b9-0b14a32ee302">

### 5. Bar coupon acceptance rate of "drivers who go to a bar more than once a month, had passengers that were not a kid, and were not widowed" VS "drivers who go to bars more than once a month and are under the age of 30" VS "drivers who go to cheap restaurants more than 4 times a month and income is less than 50K"
<img width="321" alt="Screen Shot 2024-10-08 at 12 12 52 AM" src="https://github.com/user-attachments/assets/98f649c1-f588-4d44-916f-7bdc3190b1ae">

## Insights based on Bar coupon data analysis
* Bar coupon acceptance rate of drivers who went to a bar more than 3 times a month is **39.82% higher** than than the drivers who went to bar less than than 3 times a month  
* Bar coupon acceptance rate of drivers who went to a bar more than once a month and are over the age of 25 is **36.08% higher** than other drivers

## Coffee House coupon analysis

### 1. Coffee House coupon acceptance ratio
<img width="195" alt="Screen Shot 2024-10-08 at 2 29 30 PM" src="https://github.com/user-attachments/assets/7e6ab7df-c0f3-4d44-9f59-bca5db29c5bc">

### 2. Coffee House coupon acceptance rate of "drivers who go to a Coffee House more than 3 times a month" VS "drivers who go to a Coffee House 3 or less times a month"
<img width="327" alt="Screen Shot 2024-10-08 at 2 30 22 PM" src="https://github.com/user-attachments/assets/8a699de8-6a7d-4812-b2e9-9b8145969df1">

### 3. Coffee House coupon acceptance rate of "drivers who go to a Coffee House more than 3 times a month and whose destination is work" VS "drivers who go to a Coffee House more than 3 times a month and whose destination is No Urgent Place"
<img width="329" alt="Screen Shot 2024-10-08 at 2 31 05 PM" src="https://github.com/user-attachments/assets/f78c7a07-6691-4375-b42b-4d7ff30509d6">

### 4. Coffee House coupon acceptance rate of "drivers who go to a Coffee House more than 3 times a month" VS "drivers who go to a Coffee House more than 8 times a month"
<img width="329" alt="Screen Shot 2024-10-08 at 2 31 51 PM" src="https://github.com/user-attachments/assets/2ff3eb16-a60c-4dde-9f19-2e4915344ffa">

## Insights based on Coffee House coupon data analysis
* Coupon acceptance rate of drivers who went to a coffee house more than 3 times a month is **22.56% more** than drivers who went to a coffee house less than or equal to 3 times a month  
* Coupon acceptance rate of drivers who went to a coffee house more than 3 times a month and had destination as 'No Urgent Place' have **7.36% more** than drivers who went to a coffee house more than 3 times a month and had destination as 'Work'  
* There is a very small difference of **1.71%** between Coupon acceptance rate of drivers who went to a coffee house more than 3 times a month VS Coupon acceptance rate of drivers who went to a coffee house more than 8 times a month
