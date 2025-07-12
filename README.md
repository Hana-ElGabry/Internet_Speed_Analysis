# Internet_Speed_Analysis

---

# **📊 Traffic Impact on Internet Performance in Istanbul**  

### **🔍 Project Overview**  
This project analyzes the relationship between **traffic congestion and internet performance** in Istanbul using datasets from **Ookla (internet speeds)** and **traffic density sources**. The study integrates geospatial data, applies **exploratory data analysis (EDA)**, and identifies key trends affecting connectivity and urban mobility.  

---

## **📌 Key Features**  
- **📍 Geospatial Data Integration** – Merged traffic and internet speed datasets using **Coordinate Reference System (CRS)** for spatial analysis.  
- **📊 Data Analysis & Visualization** – Used **heatmaps, scatter plots, and bar charts** to uncover disparities in **urban vs. rural connectivity**.  
- **📉 Correlation Insights** – Found a **weak negative correlation (-0.3)** between traffic congestion and internet speed.  
- **⚡ Urban vs. Rural Trends** – Identified that **urban areas (e.g., Istanbul) had 30+ Mbps speeds**, while rural areas had **<10 Mbps**.  

---

## **📂 Dataset & Preprocessing**  
- **Data Sources**:  
  - **Ookla Internet Speed Data** (Download/Upload Speeds).  
  - **Traffic Density Data** (Traffic congestion levels across Istanbul).  
- **Data Cleaning & Transformation**:  
  - Converted geohashes into **latitude & longitude** for accurate mapping.  
  - Standardized datasets into a **unified CRS** for geospatial analysis.  
  - Applied **feature engineering & normalization** for better comparisons.  

---

## **📈 Data Analysis & Techniques Used**  
- **📊 Exploratory Data Analysis (EDA)**:  
  - **Heatmaps** – Visualized internet speed distribution & congestion intensity.  
  - **Scatter Plots** – Examined the relationship between congestion levels & speed.  
  - **Bar Charts** – Compared urban vs. rural internet performance.  
- **📉 Statistical Analysis**:  
  - Calculated a **correlation coefficient (-0.3)** between traffic congestion & internet speed.  
  - Found **peak-hour congestion reaching 85% in Istanbul**, doubling travel times.  

---

## **🛠 Technologies Used**  
- **Python** (Pandas, Matplotlib, Seaborn, Geopandas)  
- **Jupyter Notebook**  
- **Geospatial Data Processing** (CRS, Geohashes)  

---

## **📊 Key Findings**  
✔ **Urban Areas** (e.g., Istanbul, Ankara) had **higher internet speeds (30+ Mbps)** but severe congestion.  
✔ **Rural Regions** had **lower speeds (<10 Mbps)**, highlighting infrastructure gaps.  
✔ **Weak Negative Correlation (-0.3)** suggests **infrastructure** plays a bigger role in connectivity than traffic congestion.  
✔ **Istanbul’s peak-hour congestion hit 85%**, doubling travel times.  

---

## **💻 How to Run the Project**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```
### **3️⃣ Run the Jupyter Notebook**  
Open **Jupyter Notebook** and execute `traffic_internet_analysis.ipynb`.  

---

## **📌 Future Improvements**  
🔹 Expanding dataset to cover **longer time periods** for better trend analysis.  
🔹 Incorporating **more predictive modeling** to forecast congestion’s impact on speed.  
🔹 Enhancing geospatial visualizations with **interactive dashboards (Plotly, Folium)**.  

---

## **🤝 Contributors**  
- **Hana El Gabry**  
- Nada Zaki
- Mona Gomaa
- Noor Akram
- Hamsa elfeky 
