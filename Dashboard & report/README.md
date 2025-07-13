
# 📊 Task 2 – Marketing Campaign Response Dashboard  
**Project Title:** Marketing Campaign Response Dashboard  
**Internship Program:** Intern Intelligence – Data Analytics Track

---

## 🎯 Objective  
Create an interactive dashboard to analyze customer behavior and campaign performance using demographic and marketing response data.

---

## 🧰 Tools Used  
- Power BI Desktop  
- marketing_campaign.csv (Kaggle)  
- Power Query Editor for cleaning and feature engineering

---

## 🧹 Data Preparation Summary  
- Created `TotalSpent` by summing product purchase columns  
- Calculated `CustomerAge` = 2025 - Year_Birth  
- Unpivoted `AcceptedCmp1` to `AcceptedCmp5` for campaign analysis  
- Cleaned and converted data types in Power BI

---

## 📈 Dashboard Visualizations & Insights

### 1️⃣ Customer Response Rate  
**Chart:** Donut Chart – `Response`  
**Insight:**  
Most customers did not respond to the campaigns. The overall response rate is low, indicating a need for better targeting or messaging.

---

### 2️⃣ Total Spending by Education Level  
**Chart:** Column Chart – `Education` vs `TotalSpent`  
**Insight:**  
Customers with higher education (PhD, Master, Graduation) spend significantly more, suggesting education is strongly linked to purchasing power.

---

### 3️⃣ Average Spending by Marital Status  
**Chart:** Bar Chart – `Marital_Status` vs `Average of TotalSpent`  
**Insight:**  
The “Absurd” and “Widow” categories show the highest average spending, which may require verification or highlight niche segments.  
"YOLO" and "Alone" groups have the lowest spending.

---

### 4️⃣ Customer Age vs Total Spending  
**Chart:** Scatter Plot – `CustomerAge` vs `TotalSpent`, color by `Education`  
**Insight:**  
High spending is concentrated between ages 30–60, especially among graduates and postgraduates.  
Spending declines sharply after age 65.

---

### 5️⃣ Campaign Response Breakdown (AcceptedCmp1–5)  
**Chart:** Column Chart – `Campaign` vs `Accepted` (after unpivot)  
**Insight:**  
Campaigns 3 and 5 received the most responses. Campaign 1 had the lowest engagement, suggesting it may require revision or removal.

---

### 6️⃣ Campaign Response by Segment

**a. By Education**  
**Insight:**  
Graduates show the highest response to all campaigns. Master and PhD follow, while Basic and 2n Cycle levels have weak engagement.

**b. By Age**  
**Insight:**  
Customers aged 30–50 respond most to campaigns. Campaign effectiveness drops significantly among customers aged 60+.

---

## 💡 Recommendations

- Focus campaigns on customers aged 30–50 with Graduation or higher education.  
- Phase out or redesign Campaign 1 due to low response rate.  
- Allocate more budget to Campaigns 3 and 5, which show strong results.  
- Re-express campaign messaging for low-responding education groups.  
- Consider data cleanup or segmentation around odd values like “Absurd”.

---

## 📎 Submission Notes  
- Task 2 completed using Power BI  
- Dashboard visuals built from cleaned dataset  
- Insights and recommendations are derived from real data trends
