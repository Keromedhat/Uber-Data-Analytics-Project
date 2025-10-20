# 🚖 Uber Data Analytics Project  

A data analytics project exploring **Uber ride patterns** through Python data cleaning and interactive **Power BI dashboards**.  
This project provides key insights into customer behavior, driver performance, and trip trends across Cairo.  

---

## 🧠 Tech Stack  
- **Python** – Data cleaning & transformation (Pandas, NumPy)  
- **Power BI** – Dashboard design & visualization  
- **GitHub** – Version control and project sharing  

---

## 📊 Customer Dashboard  
![Customer Dashboard](Customer%20Dashboard.png)

### Dashboard Overview  
The **Customer Dashboard** highlights overall ride engagement, satisfaction, and payment behaviors.  
It shows KPIs like total customers, completion rates, cancellation rates, average CTAT, and booking value.  
Interactive filters allow users to view trends by **Payment Method**, **Vehicle Type**, and **Booking Status**.

---

### 🔍 Customer Insights  
1. **High Engagement:** Over **148K customers** used Uber, indicating strong platform adoption.  
2. **Completion Challenges:** Only **62% of rides** were completed — suggesting room to improve ride reliability.  
3. **Cancellations:**  
   - **Driver cancellations (27K)** are nearly triple customer cancellations (10K).  
   - Indicates possible driver availability or scheduling issues.  
4. **Payment Preferences:**  
   - **UPI** dominates (≈43M EGP), showing user trust in digital payments.  
   - **Cash** still relevant (13M), suggesting hybrid payment support is essential.  
5. **Vehicle Type Demand:**  
   - **Auto (24.9%)** and **Go Mini (19.8%)** are most popular — users prefer **affordable, compact rides**.  
6. **Customer Ratings:** All vehicle types maintain **~4.4 stars**, showing consistent satisfaction levels.  
7. **Seasonal Trends:**  
   - Bookings peak in **Q1 and Q4**, possibly linked to holidays or weather patterns.

---

## 🚗 Driver Dashboard  
![Driver Dashboard](Driver%20Dashboard.png)

### Overview  
The **Driver Dashboard** focuses on performance, efficiency, and operational challenges.  
It includes KPIs such as completion rate, driver cancellations, average driver ratings, and average vehicle travel & arrival times (VTAT).

---

## 📊 Driver Dashboard & Customer Dashboard Analysis  

### 🎯 Overall Insights  

| Metric | Driver Dashboard | Customer Dashboard | Observation / Analysis |
| :--- | :--- | :--- | :--- |
| **Completion Rate** | **62%** | **62%** | Identical across both dashboards — about 38% of trips remain incomplete, which is a major operational concern. |
| **Total Customers** | - | **148K** | A strong customer base that needs improved fulfillment performance. |
| **Driver Cancellation Rate** | **18%** | - | **High:** 18% of trips are canceled by drivers, the primary cause of low completion rate. |
| **Customer Cancellation Rate** | - | **6.6%** | **Relatively Low:** Much lower than driver cancellation, suggesting the issue is mainly driver-side. |
| **Avg Driver Rating** | **4.24** | **4.4** (by vehicle type) | **Acceptable:** but improvement needed to enhance overall service quality. |
| **Avg VTAT (Driver Arrival Time)** | **8.41 mins** | - | **High:** may cause customer cancellations and poor satisfaction. |
| **Avg CTAT (Customer Total Awaiting Time)** | - | **29.15 mins** | High total waiting time (including search time), potentially impacting the customer experience. |

---

### 🔍 Key Insights  

#### 1. High Cancellation and Incompletion Rates  
- **38% of all trips remain incomplete.**  
- **Driver cancellations (18%)** are nearly **three times higher** than customer cancellations (6.6%).  
- The **“No Driver Found”** category represents **27K cases** out of 148K bookings — a major supply shortage indicator.  
- **Longest Avg VTAT (12.1 mins)** occurs in **customer-canceled rides**, confirming that long driver arrival times lead to customer drop-offs.

#### 2. Customer Behavior & Payment Trends  
- **UPI payments dominate (≈43M EGP)**, followed by **Cash (13M EGP)** — indicating strong digital payment adoption.  
- **Q4** records the **highest booking value**, showing seasonal peaks (end-of-year demand).  

#### 3. Vehicle Preferences  
- **Auto (24.9%)** and **Go Mini (19.8%)** rides are most popular, showing customer preference for affordable options.  
- **All vehicle types average ~4.4 stars**, suggesting consistent satisfaction but potential micro-level service gaps.

---

## 🛠️ Recommendations  

### 1. Improve Driver Operations (Reduce Cancellations & No-Driver Cases)  

| Issue | Recommendation | Objective |
| :--- | :--- | :--- |
| **High Driver Cancellation (18%)** | Implement a **reward & penalty system** — bonuses for high-completion drivers, penalties (reduced priority or temporary suspension) for unjustified cancellations. | Reduce driver cancellation rate. |
| **“No Driver Found” (27K)** | Launch a **driver recruitment and retention campaign**, especially during peak hours and underserved areas. | Increase supply and reduce search failures. |
| **Avg Driver Rating (4.24)** | Provide **training programs** on communication, punctuality, and trip handling to improve driver professionalism. | Boost ratings and service consistency. |

---

### 2. Optimize Waiting Time (Improve Avg VTAT & CTAT)  

| Issue | Recommendation | Objective |
| :--- | :--- | :--- |
| **High Avg VTAT (8.41 mins)** | Use **AI-based demand forecasting** to guide drivers to predicted demand hotspots before actual surge. | Reduce waiting time and cancellations. |
| **Customer Cancellations due to delay (12.1 mins)** | Set a **maximum wait threshold (e.g., 7 mins)** — notify both parties when exceeded and offer alternative options. | Reduce cancellation caused by long waits. |

---

### 3. Maximize Booking Value & Seasonal Demand  

| Issue | Recommendation | Objective |
| :--- | :--- | :--- |
| **Q4 peak booking value** | Run **seasonal marketing campaigns and promotions** targeting end-of-year demand. | Maximize revenue during high-demand seasons. |
| **Strong UPI and Cash usage** | Strengthen **UPI partnerships** and offer wallet discounts to encourage digital payments over cash. | Increase loyalty and reduce cash handling costs. |

---

### 🧩 Final Note  
The main operational challenges lie in **driver-side cancellations** and **limited availability**, directly affecting the **completion rate** and **customer satisfaction**.  
Focusing on these two factors — alongside smart supply planning and digital payment growth — can significantly enhance Uber’s service reliability and profitability.

---

## 👨‍💻 Author  
**Kerolos Medhat**  
📍 Cairo, Egypt  
💼 Data Analyst | Python | Power BI  
🔗 [GitHub Profile](https://github.com/Keromedhat)
