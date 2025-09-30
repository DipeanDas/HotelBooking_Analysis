# 🏨 Hotel Booking Analysis

## 📌 Overview
This project analyzes hotel booking data from **City Hotels** and **Resort Hotels** to understand the factors affecting **reservation cancellations** and provide actionable insights to reduce them.  

High cancellation rates have been impacting hotel revenues and occupancy efficiency. The analysis explores booking patterns, pricing influence, seasonal trends, and customer booking sources to suggest strategies for improving profitability.

## 🎯 Business Problem
Both City and Resort hotels face:
- High **cancellation rates** leading to vacant rooms.  
- Loss of **revenue efficiency** due to cancellations.  
- Difficulty in **forecasting demand** and making pricing decisions.  

**Objective:** Identify the key drivers of cancellations and provide strategies to reduce them.

## 📊 Assumptions
1. Data from **2015–2017** is representative and unaffected by unusual events.  
2. Cancellation patterns in this dataset remain relevant for current hotel strategies.  
3. Cancellations directly translate into **vacant rooms** for the booked duration.  
4. Customers cancel bookings in the same year they are made.  
5. Hotels are not currently implementing the proposed solutions.  

## ❓ Research Questions
1. What variables affect hotel reservation cancellations?  
2. How can cancellations be reduced?  
3. How can this analysis assist in pricing and promotional decisions?  

## 📌 Hypotheses
1. Higher prices lead to higher cancellations.  
2. Longer waiting lists increase cancellations.  
3. Most bookings are made via **offline travel agents**.  

## 📈 Analysis & Findings

- **Cancellation Rates:**  
  - ~63% of reservations are confirmed.  
  - ~37% are canceled → a significant impact on revenue.  

- **City vs Resort Hotels:**  
  - City hotels receive more bookings.  
  - Resort hotels generally charge higher rates, especially on **weekends & holidays**.  
  - Resort hotels face higher cancellation ratios.  

- **Seasonality:**  
  - **August** → highest confirmed reservations.  
  - **December** → lowest confirmed reservations.  
  - **January** → highest cancellations.  

- **Price Sensitivity:**  
  - Cancellations strongly correlate with **higher average daily rates (ADR)**.  
  - Guests cancel more when room rates are higher.  

- **Booking Channels:**  
  - **46%** bookings from **Online Travel Agencies (OTAs)**.  
  - **27%** from groups.  
  - **4%** direct bookings at hotels.  

- **Geographic Trends:**  
  - **Portugal** has the highest number of cancellations compared to other countries.  


## 💡 Suggestions & Recommendations
1. **Dynamic Pricing:**  
   - Lower room rates during high-cancellation periods.  
   - Offer discounts on weekends & holidays, especially for resort hotels.  

2. **Targeted Promotions:**  
   - Run marketing campaigns in **January** to reduce seasonal cancellation spikes.  
   - Provide loyalty offers or flexible booking terms to retain customers.  

3. **Improve Quality in Key Markets:**  
   - Enhance hotel service quality in **Portugal** to reduce cancellations.  

4. **Customer Retention via OTAs:**  
   - Strengthen partnerships with **Online Travel Agencies**, since they account for the majority of bookings.  


## 🛠️ Tools & Techniques
- **Python** (Pandas, Matplotlib, Seaborn) for analysis & visualization  
- **Excel/CSV** data preprocessing  
- **Statistical analysis** for hypothesis validation  


## 📌 Insights Summary
- **Pricing is the most significant factor** influencing cancellations.  
- **Resort hotels** face more cancellations compared to city hotels.  
- **Seasonality matters**: Cancellations spike in January, while August has maximum confirmed bookings.  
- **Portugal** leads in cancellations, requiring targeted strategies.  


## 🚀 Future Work
- Build a **predictive model** to forecast cancellations.  
- Apply **machine learning classification** to identify high-risk cancellations.  
- Integrate with **hotel revenue management systems** for real-time insights.  

## Project By:
**Dipean Dasgupta** <br>
**Data Analyst and AIML Enthusiast**
