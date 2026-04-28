# Revenue Anomaly Detection Dashboard

##  Overview
This project focuses on building an end-to-end **Anomaly Detection System** using Python and Power BI to identify unusual patterns in revenue data.

The goal is to detect **spikes, drops, and irregular trends** in transactional data and present them through an interactive, business-friendly dashboard.


##  Dataset
- Source: UCI Online Retail Dataset  
- Records: ~540,000 transactions  
- Features: Invoice, Quantity, Revenue, Customer, Timestamp  


##  Key Features

###  Data Preprocessing (Python)
- Handled missing values and cleaned raw transactional data  
- Identified and retained **returns and cancellations as anomaly signals**  
- Created revenue metrics and structured time-series data  

###  Feature Engineering
- Rolling Mean (7-day)  
- Rolling Standard Deviation  
- Z-Score for anomaly detection  
- Time-based features (Day, Month, Weekend)

###  Anomaly Detection Logic
- Implemented **Z-score model** to detect anomalies  
- Classified anomalies into:
  -  Spike (positive deviation)  
  -  Drop (negative deviation)

##  Power BI Dashboard

###  Key Components
- KPI Cards (Revenue, Anomalies, Trends)  
- Revenue vs Rolling Mean (Trend Analysis)  
- Anomaly Highlighting (Spike & Drop)  
- Monthly & Weekly Distribution Analysis  
- Drill-down table with Z-score insights  

###  Interactivity
- Filters for:
  - Years [2010 - 2011]  
  - Anomaly type - Drop, Normal & Spike 
  - Weekend vs Weekday  


##  Insights Generated
- Identified periods with **significant revenue spikes and drops**  
- Observed **seasonal trends (year-end surge)**  
- Analyzed anomaly distribution across **time dimensions**


##  Tech Stack
- Python (Pandas, NumPy, Matplotlib)  
- Power BI  
- DAX (for measures and modeling)


##  Project Highlights
- End-to-end data pipeline (Raw Data → Cleaned → Modeled → Visualized)  
- Real-world business use case (E-commerce analytics)  
- Focus on **interpretability and decision-making**


##  Dashboard Preview
- Overview - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Overview.png
- Year 2010 Data - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Year%20-%202010%20Data.png
- Year 2011 Data - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Year%20-%202011%20Data.png
- Anomalies on Spike - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Anomalies%20on%20Spike.png
- Anomalies on Drop - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Anomalies%20on%20Drop.png
- Normal Anomaly - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Normal%20Anomaly.png
- Weekend Data - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Weekend%20Data.png
- Weekday Data - https://github.com/Christopher-AR/Revenue-Anomaly-Detection/blob/main/Weekday%20Data.png

##  Connect
If you found this useful, feel free to connect with me on LinkedIn!
