# 🌍 AQI Understanding & Pollution Pattern Analysis

## 📌 Project Overview
Air Quality Index (AQI) is a standardized measure used to communicate the quality of air in a specific region based on pollutant concentration levels. This project focuses on analyzing air pollution patterns, visualizing AQI trends, and making insights accessible through an interactive Power BI dashboard integrated with a Streamlit web application.

The solution bridges the gap between static AQI reports and dynamic, user-driven insights for better environmental decision-making.

---

## 🎯 Objectives
- Analyze historical AQI and pollution data
- Identify pollution trends across regions and time
- Provide interactive and customizable dashboards
- Enable web-based access to AQI insights

---

## 🔄 Workflow of the Project

### 1. Data Collection
- Collected air quality data from open-source platforms
- Extracted key pollutants:
  - PM2.5
  - PM10
  - NO₂
  - SO₂
  - O₃
- Included meteorological parameters

### 2. Data Preprocessing
- Dataset size: **27,000+ rows and 15 columns**
- Removed duplicates and inconsistencies
- Handled missing values using **median imputation**
- Detected and treated outliers using statistical techniques

### 3. Exploratory Data Analysis (EDA)
- Analyzed pollution trends over time
- Identified seasonal and regional variations
- Visualized peak pollution periods

### 4. Dashboard Development
- Built interactive **Power BI dashboards**
- Implemented:
  - Dynamic filters
  - Trend charts
  - Heatmaps
  - Pollutant-wise insights

### 5. Web Application Development
- Embedded Power BI dashboards into a **Streamlit web application**
- Designed an intuitive and responsive user interface

---

## 🚀 Key Features
- 📊 Interactive AQI trend analysis  
- 🌍 Regional pollution comparison  
- 🔍 User-driven filters for deeper insights  
- 🔄 Automated data refresh  
- 🌐 Web-based accessibility  

---

## 🧠 Existing AQI Monitoring Systems

### Current Systems
- Government platforms such as **CPCB** and **WHO**
- Mostly static AQI reports and summary tables

### Limitations
- Limited real-time interactivity
- Lack of customized regional analysis
- Minimal user-friendly web integration

---

## 💡 Innovations in This Project
- Dynamic dashboards using **Power BI + Streamlit**
- User-controlled exploration of AQI data
- Improved accessibility for technical and non-technical users

---

## 📈 Key Findings
- Growing demand for interactive AQI dashboards
- Data visualization improves public understanding of air quality
- Python and Power BI enhance environmental data accessibility

---

## 👥 Target Users
- Environmental Researchers
- Policymakers & Urban Planners
- Health Organizations & Public Authorities
- General Public & Communities

---

## 🌱 Real-World Impact
- Supports clean-air policy planning
- Helps assess health impacts of air pollution
- Empowers citizens with actionable AQI insights

---

## 🛠️ Technologies Used

### Data Handling & Processing
- **Pandas** – Data preprocessing and manipulation  
- **NumPy** – Numerical operations and outlier handling  

### Data Visualization
- **Matplotlib** – Statistical visualizations  
- **Seaborn** – Enhanced exploratory analysis  

### Dashboard & Web App
- **Power BI** – Interactive dashboards  
- **Streamlit** – Web application integration  

---

## 📂 Project Structure
```text
├── app.py
├── preprocessing code.ipynb
├── AQI understanding pollution patterns.pbix
├── Preprocessed_city_day(final).csv
├── city_data.csv
├── feedback.csv
├── Home Page.png
├── Dashboard Page.png
├── Login page.png
├── Register Page.png
├── feedback page.png
└── README.md
