# Hotel Bookings Analytics – Data Cleaning, KPI Analysis, and Visualization

## 📌 Overview
This project is a **data analytics pipeline** for processing, cleaning, and analyzing hotel booking datasets to derive actionable business insights.  
It uses **Python, Pandas, and Matplotlib** to merge multiple datasets, compute key performance metrics, and visualize booking trends across different dimensions such as cities, months, and booking platforms.

The analysis focuses on:
- Data cleaning to ensure accuracy
- Occupancy percentage & revenue KPIs
- Trend and performance analysis by time and location
- Visual insights for better decision-making

---

## 🛠 Tech Stack
- **Languages & Tools:** Python, Jupyter Notebook
- **Libraries:** Pandas, Matplotlib
- **Data Format:** CSV datasets

---

## 📂 Dataset Structure
The project uses the following CSV files:
- `fact_bookings.csv` – Detailed booking transactions  
- `fact_aggregated_bookings.csv` – Aggregated booking and capacity data  
- `dim_hotels.csv` – Hotel property details  
- `dim_rooms.csv` – Room type and classification  
- `dim_date.csv` – Date dimension with month/year/day classification  
- `new_data_august.csv` – New monthly data appended for trend updates  

---

## 🚀 Features
### Data Integration
- Merge multiple CSV datasets for a unified analysis framework.

### Data Cleaning
- Removed invalid guest entries (zero or negative guests)  
- Handled missing values using median imputation  
- Detected and removed statistical outliers using mean ± 3*std deviation  

### KPI Calculation
- Occupancy percentage (`occ_pct`) by property, room category, and city  
- Revenue generated and revenue realized metrics  
- Capacity utilization tracking  

### Trend Analysis
- Monthly performance by city and booking channel  
- Seasonal patterns by day type (weekday vs weekend)  

### Visualizations
- Booking platform distribution  
- City occupancy ranking  
- Monthly revenue trends  

---

## 📊 Example Insights
- Cities with highest and lowest occupancy percentages  
- Most popular booking platforms by volume  
- Room categories with best utilization rates  
- Monthly performance variations for targeted marketing decisions  

---

## ▶️ How to Run
1. **Clone the repository**
   git clone https://github.com/your-username/hotel-bookings-analytics.git
   cd hotel-bookings-analytics
2. **Install required libraries**
   pip install pandas matplotlib
3. **Open the file in Jupyter Notebook**
4. **Run cells sequentially to reproduce the analysis and visualizations.**
