# Consumer Complaints - Excel Dashboard

## Introduction

Using Excel, I analyzed a U.S. consumer complaints dataset to uncover patterns in complaint volume, issue type, and company responses. The purpose of this dashboard was to simulate a real-world business case where a **concise, static report** would be delivered to decision-makers who need quick, actionable insights.

Unlike exploratory dashboards filled with filters and slicers, this version focuses on one central finding, delivered with clarity and minimalism—ideal for **executive summaries** and presentations.

## Dashboard File

Check out the Excel dashboard here:  
👉 [Consumer_Complaints_Dashboard.xlsx](https://github.com/user-attachments/files/20644391/Consumer_Complaints_Dashboard.xlsx)


## Excel Skills Used

This project demonstrates a range of Excel skills including:
- 🔄 Power Query 
- 🧮 Power Pivot
- 🎯 Formulas and functions  
- 📊 Pivot Tables  
- ✅ Conditional Formatting  
- 📈 Data Visualization (Charts and Conditional Formatting)  

## Consumer Complaints Dataset

The dataset contains records of consumer complaints submitted to U.S. federal agencies. After cleaning and organizing the data, I focused on key fields relevant to systemic trends:

- Complaint Issue  
- Company Name  
- State  
- Product Type  
- Date Received  
- Company Response
- Submission Method

## Dashboard Build

### Evolution of complaints sent, by year

In order to find a way of reducing the number of complaints sent, I first needed to find out the total number of complaints.

![evolution](https://github.com/user-attachments/assets/ade759c4-761c-4c6c-839b-5e897a7ac7c1)

### 🧭 Complaint Distribution by Product

Using Pivot Tables and bar charts, I summarized how complaints are distributed **product involved**. This revealed disproportionate volumes in certain product categories, which gave me valuable information : the two top products made the majority of the total complaints sent. This needed further investigation.

![percentage](https://github.com/user-attachments/assets/264c07cc-374d-4718-97de-a798530d2787)


### Finding the weekness

This way, I found the four issues, most common among the two products with the most complaints. This way, I made the following statement: if we find a way to reduce the number of complaints sent for these four issues, the total number will reduce drastically.

![complaints](https://github.com/user-attachments/assets/71dab403-c3cb-499c-8933-25a434ef2ee6)

### 🚩 Highlighting another Important Component

Not ony was the number of complaints sent enough a reason for concern, but the majority of them were solved by companies with monetary means, meaning that companies were constantly losing money.

![monetary_relief](https://github.com/user-attachments/assets/1e9ae671-fd85-4473-b5ab-6e7f84d8a241)

### Solution?

The most common submittion method used is the **Web**. This means that most customers use the web in order to solve their problems. Thus, if we communicate relevant information about the most complaint about issues via the web, the number of total complaints will be reduced.

![sent_via](https://github.com/user-attachments/assets/1971af31-e7ca-4ee9-a20f-9d53c19db973)


### 🎯 Why No Slicers or Filters?

The absence of slicers or interactivity was **intentional**. The goal was to simulate a static presentation slide or report—something that executives can understand in under a minute. While being capable of building interactive dashboards, the design priority here was **clarity, not complexity**.

## 📊 Estimated Impact

A failure to address the highlighted issue could result in:

- Decreased consumer trust in services  
- Increased regulatory scrutiny on companies with poor complaint handling  
- Missed opportunities for service improvement and customer retention  

The dashboard proposes focusing corrective action on the most frequently reported issue within the most affected product category.

## ✅ Conclusion

Through this project, I was able to:

- Build a clean Excel pipeline from raw data to insights  
- Apply analytical reasoning to uncover a recurring issue  
- Use effective visual storytelling in a static dashboard format

This project showcases how even simple Excel tools, used intentionally, can provide **clear and actionable insights** from messy real-world data.





