# ✈️ Airline Loyalty Campaign Analysis | Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-Transformation-green?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-orange?style=for-the-badge)

---

## 📌 Project Overview

The Airline Loyalty Campaign Analysis Dashboard is an end-to-end Power BI project designed to evaluate the effectiveness of a customer loyalty promotion launched by a Canadian airline between **February 2018 and April 2018**.

The dashboard analyzes customer enrollment behavior, campaign adoption, flight activity, customer demographics, and retention patterns to help stakeholders understand how the campaign influenced customer acquisition, engagement, and long-term loyalty.

The project transforms raw customer and flight activity data into an interactive analytical solution focused on:

- 📈 Executive Performance Monitoring
- 👥 Customer Demographic Analysis
- ✈️ Flight Activity & Engagement Analysis
- 🔄 Retention & Churn Analysis

---

# 📸 Dashboard Preview

## 📈 Executive Overview

<img width="1532" height="862" alt="Overview" src="https://github.com/user-attachments/assets/e9bf001e-8e7d-475c-92e4-3e69b88252dc" />

---

## 👥 Customer Demographics Analysis

<img width="1531" height="859" alt="Customer Demographics" src="https://github.com/user-attachments/assets/1ded8ef8-32cd-44c6-b1c8-7056a95b07e6" />

---

## ✈️ Flight Activity Analysis

<img width="1533" height="861" alt="Flight Avtivity Analysis" src="https://github.com/user-attachments/assets/f52e89c4-4877-4355-8f8d-3f72622dc955" />

---

## 🔄 Retention & Churn Analysis

<img width="1530" height="859" alt="Retention and Churn Analysis" src="https://github.com/user-attachments/assets/300b72ad-2c39-499b-a711-399c3c213344" />

---

# 🎯 Business Problem Statement

Airlines invest heavily in loyalty programs to attract and retain customers. However, measuring the effectiveness of promotional campaigns requires answering critical business questions:

- Did the campaign increase loyalty program memberships?
- Which customer segments responded most positively?
- Did newly acquired members become active travelers?
- Which regions generated the highest campaign adoption?
- How effectively did the airline retain acquired members?
- Which customer segments are most at risk of cancellation?

Without proper analysis, it is difficult to determine whether promotional spending generated meaningful business value.

This dashboard addresses these challenges by converting customer loyalty and flight activity data into actionable business insights.

---

# ✅ Key Business Questions Solved

| Business Question | Dashboard Solution |
|-------------------|-------------------|
| 📈 Did the campaign increase memberships? | Membership Growth Analysis |
| 🎯 How many customers joined through the campaign? | Promotion Enrollment Tracking |
| 🌎 Which provinces responded best? | Geographic Adoption Analysis |
| 👥 Which demographics adopted the campaign? | Customer Segmentation Analysis |
| ✈️ Did engagement increase after the campaign? | Flight Activity Analysis |
| 🎁 How actively did customers use loyalty points? | Points Accumulation & Redemption Analysis |
| 🔄 What is the customer retention rate? | Retention & Churn Dashboard |
| 💰 Which customer groups create the most value? | CLV & Loyalty Tier Analysis |

---

# 📂 Dataset Information

| Dataset | Description |
|----------|------------|
| Customer Loyalty History | Customer demographics, loyalty information, enrollments and cancellations |
| Customer Flight Activity | Monthly flight activity and loyalty point transactions |
| Calendar Table | Time intelligence and trend analysis |

---

# 📊 Dataset Summary

| Metric | Value |
|----------|----------:|
| 👥 Total Members | 16,769 |
| 🎯 Promotion Members | 971 |
| ✅ Active Customers | 14,697 |
| ❌ Cancelled Customers | 2,072 |
| ✈️ Total Flights | 509K+ |
| 🌍 Total Distance Travelled | 763M+ |
| 🎁 Points Accumulated | 796M+ |
| 💰 Redeemed Value | $2M+ |

---

# 🧹 Data Cleaning & Transformation

### Key preprocessing steps performed

- Removed inconsistencies and validated customer records
- Created Enrollment Date and Cancellation Date fields
- Built Campaign Phase classification
- Created Customer Status segmentation
- Developed Salary Group segmentation
- Built retention and churn KPIs
- Developed campaign analysis measures
- Created a structured Power BI data model
- Implemented DAX measures for customer and flight analytics

---

# 🏗️ Data Model

The dashboard follows a star-schema design consisting of:

- Customer Loyalty History (Dimension)
- Customer Flight Activity (Fact)
- Calendar Table (Date Dimension)

The model supports:

- Time Intelligence
- Campaign Analysis
- Customer Segmentation
- Loyalty Program Analysis
- Retention & Churn Analysis

### Data Model Screenshot

> Add Data Model Screenshot Here

---

# 🧮 Key DAX Measures

- Total Members
- Promotion Members
- Active Customers
- Cancelled Customers
- Net Growth
- Cancellation Rate
- Active Customer Rate
- Total Flights
- Total Distance
- Points Accumulated
- Points Redeemed
- Redeemed Value

---

# 📄 Dashboard Pages

## 1️⃣ Executive Overview

### KPIs

- Total Members
- Promotion Members
- Active Customers
- Cancelled Customers
- Net Growth
- Total Flights

### Key Insights

- The campaign generated **971 promotional enrollments**.
- Ontario, British Columbia, and Quebec recorded the highest campaign participation.
- Flight activity increased significantly after the campaign period.
- Nearly **88% of members remained active**.

### Recommendations

✅ Focus future campaigns on high-performing provinces.

✅ Expand campaigns during historically high-engagement periods.

✅ Optimize marketing spend using campaign performance insights.

---

## 2️⃣ Customer Demographics Analysis

### Key Insights

- Campaign adoption was nearly evenly distributed across genders.
- Medium-income customers represented the largest promotional segment.
- Bachelor's degree holders formed the largest customer group.
- Star-tier members represented the largest share of the loyalty program.

### Recommendations

✅ Develop demographic-specific promotions.

✅ Target high-value customer segments.

✅ Use province-level segmentation to improve campaign performance.

---

## 3️⃣ Flight Activity Analysis

### Key Insights

- Loyalty members completed more than **509K flights**.
- Customers accumulated over **796M loyalty points**.
- Summer 2018 recorded peak flight activity.
- Ontario generated the highest redemption value.

### Recommendations

✅ Launch seasonal travel promotions.

✅ Encourage loyalty point redemption through personalized campaigns.

✅ Increase engagement initiatives for lower-activity customer segments.

---

## 4️⃣ Retention & Churn Analysis

### Key Insights

- Approximately **88% of customers remained active**.
- Churn was concentrated within specific customer segments.
- Active customers demonstrated stronger long-term customer value.

### Recommendations

✅ Build churn prediction and monitoring strategies.

✅ Provide retention incentives to at-risk customers.

✅ Strengthen loyalty benefits for lower-engagement members.

---

# 📈 Business Impact

This dashboard enables stakeholders to:

- Measure campaign effectiveness
- Identify high-performing customer segments
- Evaluate customer engagement trends
- Monitor retention performance
- Improve customer targeting strategies
- Optimize future marketing investments
- Support data-driven decision making

---

# 🔄 Project Workflow

Raw Data

⬇️

Power Query Transformation

⬇️

Data Modeling

⬇️

DAX Measures & KPIs

⬇️

Interactive Dashboard Development

⬇️

Business Insights & Recommendations

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|---------|
| 📊 Power BI | Dashboard Development & Visualization |
| 🔄 Power Query | Data Cleaning & Transformation |
| 🧮 DAX | KPI Measures & Calculated Columns |
| 📂 Data Modeling | Relationship Management |

---

## 📬 Connect With Me

### 🔗 LinkedIn

www.linkedin.com/in/rajdeepghosh2003

### 💻 GitHub

https://github.com/RdeepGhosh-2003

⭐ If you found this project useful, consider giving it a star.
