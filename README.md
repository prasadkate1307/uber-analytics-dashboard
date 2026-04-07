# 🚗 Uber Rides Analytics Dashboard — Delhi NCR

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=flat&logo=powerbi)
![Dataset](https://img.shields.io/badge/Dataset-43K%2B%20Records-orange?style=flat)
![Kaggle](https://img.shields.io/badge/Source-Kaggle-blue?style=flat&logo=kaggle)
![DAX](https://img.shields.io/badge/DAX-20%2B%20Measures-green?style=flat)

An end-to-end data analytics project analyzing 43,000+ Uber ride records for Delhi NCR. Built an interactive Power BI dashboard with 4 analytical pages to uncover actionable business insights across revenue, bookings, cancellations, and driver performance.

---

## 📌 Project Overview

This project performs comprehensive analysis of Uber ride data for the Delhi NCR region. Using Python for data preprocessing and EDA, and Power BI for interactive visualization, the dashboard enables data-driven decision making for business stakeholders.

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization (EDA) | Matplotlib, Seaborn |
| Dashboard | Power BI |
| DAX Measures | 20+ custom measures |
| Dataset Source | Kaggle |

---

## 📂 Project Structure

```
uber-analytics-dashboard/
│
├── notebooks/
│   └── uber_eda.ipynb          # Data Preprocessing & EDA
├── data/
│   └── uber_dataset_final.csv  # Cleaned dataset (43K+ records)
├── dashboard/
│   └── uber_dashboard.pbix     # Power BI Dashboard file
├── screenshots/
│   ├── revenue_page.png
│   ├── bookings_page.png
│   ├── cancellation_page.png
│   └── driver_insights_page.png
└── README.md
```

---

## 📊 Dataset

- **Size:** 43,000+ Uber ride records
- **Region:** Delhi NCR (Delhi, Gurgaon, Noida, Faridabad, Ghaziabad)
- **Source:** [Kaggle](https://www.kaggle.com)
- **Key Columns:** Booking Status, Vehicle Type, Pickup Location, Booking Value, Ride Distance, Driver Ratings, Customer Rating, Payment Method, Avg VTAT, Avg CTAT

---

## 🔑 Key Steps

1. **Data Preprocessing** — Handled null values, data type corrections, and inconsistencies
2. **Feature Engineering** — Created Hour of Day, Day Name, Is Weekend, Distance Bucket, Rating Category calculated columns
3. **Exploratory Data Analysis** — 15+ visualizations uncovering patterns in revenue, bookings, and cancellations
4. **DAX Measures** — Built 20+ custom DAX measures for KPIs across all pages
5. **Dashboard Design** — Uber-themed dashboard with sidebar navigation using brand colors (#000000, #06C167)

---

## 📋 Dashboard Pages

### Page 1 — 💰 Revenue Analysis
- Total Revenue, Avg Revenue/Ride, Total Rides, Completion Rate KPIs
- Revenue trend over time, by vehicle type, by zone, by hour
- Top 5 pickup locations by revenue

### Page 2 — 🚗 Bookings Overview
- Total Bookings, Successful Bookings, Cancelled Bookings, Avg Ride Distance KPIs
- Booking status breakdown, bookings by vehicle type
- Peak booking hours, weekday vs weekend analysis
- Avg VTAT vs CTAT by vehicle type

### Page 3 — ❌ Cancellation Analysis
- Total Cancellations, Cancellation Rate, Driver vs Customer Cancellations KPIs
- Revenue lost due to cancellations
- Top cancellation reasons by driver and customer
- Cancellation trend and zone-wise analysis

### Page 4 — 👤 Driver & Customer Insights
- Avg Driver Rating, Avg Customer Rating, Unique Customers KPIs
- Driver rating by vehicle type, ride distance distribution
- Payment method breakdown, VTAT vs CTAT comparison
- Repeat customer rate and high value customers

---

## 💡 Key Business Insights

### Revenue
- 📈 **Peak revenue window: 6PM–8PM** — highest earning period of the day
- 🚗 **Auto is highest revenue vehicle** contributing **25% of total revenue**
- 💰 **62% booking completion rate** across 43,000+ transactions

### Cancellations
- ❌ **24.85% cancellation rate** — primarily driven by **driver-side cancellations**
- 💸 Cancellations resulted in **₹2M revenue loss**
- 🔧 **Recommendation:** Implement targeted driver retention strategies and incentives during peak hours to reduce cancellation rate

### Driver & Customer
- ⭐ **Avg driver rating: 4.23** — indicating good overall service quality
- 📱 **UPI is dominant payment method** across all transactions
- 📏 **10–20 km is most common ride distance** — mid-range trips dominate demand

---

## 📸 Dashboard Screenshots


> <img width="1326" height="743" alt="revenue_analysis" src="https://github.com/user-attachments/assets/5310f87a-cd48-45e5-a502-19e54b886ad0" />
<img width="1312" height="736" alt="ride_and_booking" src="https://github.com/user-attachments/assets/49d4791a-4c3b-4938-b439-06803564fc61" />

> <img width="1311" height="732" alt="cancellationAnalysis" src="https://github.com/user-attachments/assets/9d44d78c-b71d-4db3-9784-1f3d6e5b4556" />
<img width="1322" height="741" alt="customer insights" src="https://github.com/user-attachments/assets/57296179-8da4-4ace-9bf6-8126391f8800" />


---

## 🎨 Dashboard Theme

Uber brand colors used throughout:

| Color | Hex | Usage |
|---|---|---|
| Black | `#000000` | Sidebar background |
| Uber Green | `#06C167` | KPI values, highlights |
| Dark Grey | `#1A1A1A` | Cards, buttons |
| Light Grey | `#F6F6F6` | Page canvas |
| White | `#FFFFFF` | Text, chart background |

---

## ▶️ How to Use

```bash
# Clone the repository
git clone https://github.com/prasadkate1307/uber-analytics-dashboard.git

# Navigate to project folder
cd uber-analytics-dashboard

# Install Python dependencies
pip install -r requirements.txt

# Run EDA notebook
jupyter notebook notebooks/uber_eda.ipynb

# Open Power BI dashboard
# Open dashboard/uber_dashboard.pbix in Power BI Desktop
```

---

## 👤 Author

**Prasad Kate**
- GitHub: [@prasadkate1307](https://github.com/prasadkate1307)
- LinkedIn: [prasad-kate](https://www.linkedin.com/in/prasad-kate)
- Email: prasadkate1307@gmail.com
