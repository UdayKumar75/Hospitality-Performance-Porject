# 🏨 Hospitality Performance Dashboard – Power BI

This project is part of the [Codebasics Resume Project Challenge #1](https://codebasics.io/challenge/codebasics-resume-project-challenge), where the goal is to create an insightful and interactive Power BI dashboard using hotel booking and performance data. It demonstrates strong data modeling, DAX skills, and visual storytelling tailored for business users in the hospitality domain.

## 📊 Dashboard Overview

The final Power BI dashboard is structured into four pages:
1. **Overall Performance** – Key metrics like Total Revenue, Occupancy %, and Booking Status distribution.
2. **Revenue Analysis** – Insights on revenue generated vs. realized, broken down by room type and time.
3. **Booking Analysis** – Trends by platform, city, room category, and cancellations.
4. **Rating Analysis** – Customer satisfaction metrics by hotel, city, and room class.

## 🧩 Datasets Used

The project uses five interrelated CSV files:
- `dim_hotels.csv` – Hotel metadata (name, city, category)
- `dim_rooms.csv` – Room type and class mapping
- `dim_date.csv` – Calendar with week, month, and day type info
- `fact_bookings.csv` – Individual booking-level data
- `fact_aggregated_bookings.csv` – Room availability and booking status summaries

> Dataset provided by Codebasics as part of the public challenge.

## 🛠️ Key Features & Techniques

- Data modeling with star schema: connected dimension and fact tables
- DAX calculations for metrics like **Occupancy Rate**, **Revenue Realized**, and **Avg. Rating**
- Drillthroughs and slicers by city, hotel, platform, and room class
- Conditional formatting, tooltips, and user-friendly UI design
- Business insights on seasonal trends, cancellations, and high-performing segments

## 📁 Project Files

- `Hospitality Data Analysis.pbix` – The complete Power BI dashboard file
- CSV files – Raw data used in Power BI
- `README.md` – Project documentation

## 📌 How to Use

1. Clone the repository or download the `.pbix` file
2. Open the project in Power BI Desktop
3. Ensure the provided CSV files are in the same directory or adjust data source paths
4. Explore and interact with the visuals to derive insights

## 📬 Contact

**Uday Kumar**  
📧 udaykumar7928@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/uday-kumar-contact)

---

**⭐ If you found this project helpful or insightful, consider giving it a star!**
