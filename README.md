Gym Analytics Dashboard (Power BI)
📌 Project Overview

This project is an interactive Gym Analytics Dashboard built using Microsoft Power BI.
The dashboard helps gym owners and managers monitor member activity, revenue, attendance trends, and performance KPIs in a single view.
It also includes a live visual indicator to make the dashboard dynamic and modern.

🎯 Objectives
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/89b67d0d-5953-4eb7-b74e-7d9ca83ae43b" />

Track gym membership performance in real time

Analyze monthly and daily attendance trends

Monitor revenue and subscription status

Identify active vs inactive members

Provide quick insights using KPIs and visual indicators

📊 Dashboard Features

📈 Attendance Trends (Daily / Monthly)

💳 Membership & Revenue Analysis

👥 Active vs Inactive Members<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/1a2a072a-bea6-4c64-be81-98c0babc2694" />


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


The dataset contains gym-relate<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/d605f6b9-8227-4f5e-a412-4fba0d60df52" />
d data such as:

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
<img width="451" height="407" alt="Screenshot 2025-12-17 230552" src="https://github.com/user-attachments/assets/1fa84360-1178-44e1-a865-bda182d66b84" />
<img width="445" height="414" alt="Screenshot 2025-12-17 230633" src="https://github.com/user-attachments/assets/9e2efcef-b1e6-444e-a8d8-008dd3b0c003" />
<img width="422" height="258" alt="Screenshot 2025-12-17 230724" src="https://github.com/user-attachments/assets/83954ed3-c768-4cf0-a2d9-6f57e9d499e9" />
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/e784f6bd-b857-4376-b2a5-829f3169dbeb" />
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/ad5ad616-edf6-42d0-8436-155aa1f5331e" />
<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/5c4f11d6-5489-4a08-94bb-0e1bbbfd741b" />
<img width="270" height="720" alt="Screenshot 2025-12-16 133632" src="https://github.com/user-attachments/assets/dc284f6a-3c2f-48c2-9472-ae33e824dbbe" />
<img width="521" height="532" alt="Screenshot 2025-12-16 133648" src="https://github.com/user-attachments/assets/edc83fd2-570a-4eef-93b3-e2254a7fd5d9" />
<img width="1646" height="732" alt="Screenshot 2025-12-17 230427" src="https://github.com/user-attachments/assets/a1b0e493-6835-4eb1-85ed-9284cc070dc9" />
<img width="1460" height="771" alt="Screenshot 2025-12-17 230504" src="https://github.com/user-attachments/assets/9affb378-120b-493f-ae01-5ae0765f579f" />

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
