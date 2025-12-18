Gym Analytics Dashboard (Power BI)
📌 Project Overview

This project is an interactive Gym Analytics Dashboard built using Microsoft Power BI.
The dashboard helps gym owners and managers monitor member activity, revenue, attendance trends, and performance KPIs in a single view.
It also includes a live visual indicator to make the dashboard dynamic and modern.

🎯 Objectives

Track gym membership performance in real time

Analyze monthly and daily attendance trends

Monitor revenue and subscription status

Identify active vs inactive members

Provide quick insights using KPIs and visual indicators

📊 Dashboard Features

📈 Attendance Trends (Daily / Monthly)

💳 Membership & Revenue Analysis

👥 Active vs Inactive Members

🏷️ Subscription Type Breakdown

🧮 Key Metrics Cards (Total Members, Revenue, Avg Attendance)

🌤️ Live Status Icon / Indicator for dynamic UI

🎛️ Interactive Filters & Slicers

🛠️ Tools & Technologies

Power BI Desktop

Power Query (M Language) for data cleaning

DAX for measures and KPIs

Excel / CSV Dataset

OpenWeather API (Optional) for live icon feature

📂 Dataset

The dataset contains gym-related data such as:

Member ID

Join Date

Membership Type

Attendance Records

Payment / Revenue Details

Status (Active / Inactive)

(Dataset can be replaced with real or sample gym data.)

📐 Key DAX Measures (Examples)
Total Members = DISTINCTCOUNT(Gym[MemberID])

Total Revenue = SUM(Gym[Revenue])

Active Members =
CALCULATE(
    DISTINCTCOUNT(Gym[MemberID]),
    Gym[Status] = "Active"
)

Attendance Rate =
DIVIDE(
    SUM(Gym[Attendance]),
    [Total Members]
)

🔄 Data Refresh

Manual refresh in Power BI Desktop

Scheduled refresh supported in Power BI Service

Live indicator updates on refresh

📌 Business Impact

Helps gym management make data-driven decisions

Identifies low attendance periods

Improves member retention strategy

Provides a professional reporting system for fitness businesses

🚀 Future Enhancements

Integration with IoT gym devices

Real-time attendance tracking

Mobile-friendly Power BI report

AI-based member churn prediction

📸 Dashboard Preview

(Add screenshots of your Power BI dashboard here)

👤 Author

Udit Katiyar
Aspiring Data Analyst | Power BI | Data Analytics

📎 How to Use

Download the .pbix file

Open in Power BI Desktop

Update dataset path if required

Refresh data

Explore the dashboard using filters
