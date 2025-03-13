# Performance Testing with JMeter
#### This repository contains JMeter test plans for herokuapp and dmoney. These test plans were created to evaluate system performance under different loads using performance testing and stress testing.



## Technology I have used:
- Apache JMeter


## How to run:
- Clone this repository
- Open JMeter
- Load the Test Plan ( ```booking.jmx``` or ```dmoney.jmx```)
- Configure Thread Groups & Dataset (if needed)
- Run the Test and Analyze Results

## How to generate Report:
Use the following command:
- ```jmeter -n -t <test JMX file> -l <test log file> -e -o <Path to output folder>```


# 📌 Project Overview
## 1️⃣ booking.jmx
This JMeter test plan includes:


- Login
- Create Booking
- Search Booking

### ✅ Tests Performed:

 - Performance Testing
    - 5 minutes
    - 10 minutes
    - 20 minutes

  
- Stress Testing 
    - 20 minutes

##  This JMeter test plan simulates financial transactions with three different threads:

- Deposit _(Takes 10 Customers and 5 Agents data from deposit.csv)_
- Send Money _(Takes 15 Customer data from sendMoney.csv)_
- Payment _(Takes 5 Customers and 2 Merchant data from payment.csv)_

***The required datasets are in Resources/ folder***

# 📊 Test Results

## 1️⃣ booking.jmx

- Performance Test:
![image](https://github.com/user-attachments/assets/bc940ee3-8c14-40ba-98ed-9940e73d4a86)

- Performance Report:
![image](https://github.com/user-attachments/assets/01dc39bb-191f-4a72-9e16-b5c4902fd6b5)

- Stress Test:
![image](https://github.com/user-attachments/assets/a5cbc473-c959-4e33-9454-c1e0f5602d51)

- Stress Report:
![image](https://github.com/user-attachments/assets/c22d223e-ee4d-4be6-980b-f02d65d61a3b)



## 2️⃣ dmoney.jmx

- Performance Report:
![image](https://github.com/user-attachments/assets/b0f60f73-d62f-49eb-8a19-ffda10cb8386)

