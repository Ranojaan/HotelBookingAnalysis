# 🏨 Hotel Booking Cancellation Analysis  

## 📌 Project Overview  
In recent years, **City Hotel** and **Resort Hotel** have seen high cancellation rates, leading to revenue loss and inefficient room utilization.  
This project analyzes hotel booking cancellations, identifies key factors influencing them, and provides data-driven business suggestions to reduce cancellations and improve revenue.  

---

## ❓ Business Problem  
High cancellation rates have resulted in:  
- Lower revenues  
- Poor utilization of hotel capacity  
- Difficulty in forecasting demand  

The **primary goal** is to uncover the drivers of cancellations and provide actionable recommendations for hotel management.  

---

## 🔍 Hypotheses  
1. More cancellations occur when prices are higher.  
2. Longer waiting lists increase the likelihood of cancellations.  
3. The majority of clients make reservations through offline travel agents.  

---

## 🎯 Research Questions  
1. What variables affect hotel reservation cancellations?  
2. How can hotels reduce reservation cancellations?  
3. How can data insights assist hotels in making pricing and promotional decisions?  

---

## 💡 Suggestions  
1. **Pricing Strategy** – Cancellations increase as prices rise. Hotels should optimize pricing and provide location-based discounts.  
2. **Resort Hotel Focus** – Resort hotels have higher cancellation ratios. Discounts during weekends and holidays can help.  
3. **Seasonal Campaigns** – January shows the highest cancellations. Hotels should run targeted campaigns to attract and retain customers.  
4. **Quality Improvements** – Enhancing hotel quality and service, especially in Portugal, can help lower cancellations.  

---

## 📂 Dataset  
**Source:** [Kaggle – Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/mojtaba142/hotel-booking)  

- **Observations:** 119,390 bookings  
- **Time Period:** July 2015 – August 2017  
- **Features:** Includes booking status (canceled/not canceled), booking method, lead time, average daily rate, and more.  

---

## 🛠 Tools & Technologies  
- **Python** (pandas, matplotlib, seaborn)  
- **Jupyter Notebook**  
- **Data Visualization & Exploratory Data Analysis (EDA)**  
- **Sentiment Analysis**  

---

## 📊 Process / Methodology  
1. **Data Extraction** – Import dataset from Kaggle  
2. **Data Cleaning** – Handle missing values, duplicates, and outliers  
3. **Exploratory Data Analysis** – Identify patterns, correlations, and cancellation trends  
4. **Visualization** – Graphical representation of findings  
5. **Insights & Recommendations** – Business suggestions based on analysis  

---

## 📸 Screenshots & Visualizations  

<img width="573" height="459" alt="Reservation Status Count" src="https://github.com/user-attachments/assets/e1faf712-4507-40c4-8d5f-faf2ddca0bf8" />

The bar chart shows the proportion of reservations that were canceled versus those that were not.  
Approximately **37% of bookings were canceled**, which represents a substantial revenue impact for both hotels.  

---

<img width="884" height="496" alt="Reservation status in different hotels" src="https://github.com/user-attachments/assets/ba7fba92-bc09-4f73-8071-449cf935b927" />

City Hotels receive a higher volume of bookings compared to Resort Hotels.  
This may be attributed to **price differences**, as Resort Hotels tend to be more expensive.  

---

<img width="1374" height="594" alt="Avg daily rate in City and resort hotel" src="https://github.com/user-attachments/assets/f750541a-6a2b-4a75-91d0-cfa2a6594379" />

The line graph highlights fluctuations in **average daily rates (ADR)** between City and Resort Hotels.  
As expected, **Resort Hotel rates rise during weekends and holidays**, making them costlier compared to City Hotels.  

---

<img width="1375" height="733" alt="Reservation status per month" src="https://github.com/user-attachments/assets/6c834324-b68e-4be6-82ed-e7b3e241c1aa" />

This grouped bar chart shows reservation patterns across months.  
- **August** records the highest number of both confirmed and canceled reservations.  
- **January** stands out as the month with the highest cancellation rate.  

---

<img width="1232" height="695" alt="ADR per month" src="https://github.com/user-attachments/assets/e1489d89-4842-4542-b0b0-37d2bfa681b2" />

The bar chart demonstrates a clear relationship between **price and cancellations**:  
- Higher ADR → Higher cancellations  
- Lower ADR → Lower cancellations  

This supports the hypothesis that **pricing directly influences booking cancellations**.  

---

<img width="694" height="709" alt="Top 10 countries with reservation cancelled" src="https://github.com/user-attachments/assets/64de631c-4d66-48af-8541-e80934d3531e" />

The top 10 countries with the highest number of cancellations are shown above.  
**Portugal** leads the list with the largest share of canceled reservations.  

---

<img width="1234" height="416" alt="Avg daily rate" src="https://github.com/user-attachments/assets/88cced4f-0f26-446a-932f-8072051723c9" />

The chart shows booking sources:  
- **46%** of clients book through online travel agencies  
- **27%** book as groups  
- Only **4%** book directly with the hotels  



