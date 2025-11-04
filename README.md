# 🚗 Vehicle Insurance EDA | Data Analysis Project

## 📘 Overview
This project performs **Exploratory Data Analysis (EDA)** on a large **Vehicle Insurance dataset** containing over **381,000 records**.  
The goal is to uncover **key demographic and behavioral patterns** that influence vehicle insurance claims, enabling better decision-making and policy strategies within the insurance domain.

---

## 🎯 Objective
The main objective of this project is to:
- Explore, clean, and analyze a real-world vehicle insurance dataset.
- Identify trends, relationships, and factors that impact insurance claims.
- Derive actionable business insights to improve marketing, pricing, and customer targeting strategies.

---

## 🧰 Tools & Libraries Used
- **Python**
  - `pandas` → Data cleaning and manipulation  
  - `numpy` → Numerical computations  
  - `matplotlib`, `seaborn`, `plotly` → Data visualization and statistical graphics
- **Google Colab** → Coding and analysis environment
- **Power BI (optional)** → For visual dashboards (if extended)

---

## 🧾 Dataset Description
**Total Records:** 381,109  
**Total Columns:** 12 (9 numerical, 3 categorical)

### Key Columns:
| Feature | Description |
|----------|-------------|
| `Gender` | Gender of the insured person |
| `Age` | Age of the applicant |
| `Driving_License` | Whether the person holds a valid driving license |
| `Region_Code` | Geographic region of the customer |
| `Previously_Insured` | If the person had prior insurance |
| `Vehicle_Age` | Age of the insured vehicle |
| `Vehicle_Damage` | Whether the vehicle has past damage |
| `Annual_Premium` | Yearly premium amount |
| `Policy_Sales_Channel` | Channel through which the policy was sold |
| `Vintage` | Customer association period |
| `Response` | Target variable – 1 if interested in insurance, else 0 |

---

## 🧹 Data Preprocessing
- Checked for **missing and duplicate values** → None found  
- Detected **outliers** in `Annual_Premium` using the **IQR method** and removed extreme values for better visualization  
- Converted categorical columns for effective analysis  

---

## 📊 Key Insights

### 👥 Demographics
- **Majority of applicants are male**, indicating higher male participation in vehicle insurance.
- **Age group 25–50** dominates claim interest — the most active vehicle-owning segment.

### 💰 Premium & Claims
- Most customers opt for **mid-range premium plans (₹20,000–₹60,000)**.  
- High premiums correlate with **lower interest**, suggesting the need for balanced pricing strategies.

### 🚘 Vehicle Factors
- **Newer vehicles (1–2 years old)** show the highest claim interest.
- **Previously damaged vehicles** have significantly higher claim response rates.

### 🌍 Regional & Channel Analysis
- A few **regions and policy sales channels** dominate most policy sales.
- Indicates the need for **region-specific marketing strategies**.

### 🔁 Customer Loyalty
- **Previously insured** individuals are more likely to respond positively.
- Claim interest remains consistent across new and long-term customers.

---

## 📈 Final Summary
This EDA provided a data-driven understanding of customer behavior and insurance claim dynamics.  
It revealed how factors such as **age, vehicle age, premium
