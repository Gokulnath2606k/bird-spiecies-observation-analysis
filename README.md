# 🐦 Bird Species Observation Analysis

## 📌 Project Overview
This project analyzes bird species observations across **Forest** and **Grassland** habitats.  
The goal is to understand bird distribution, habitat preference, and environmental impact using data analysis.

---

## 🎯 Objectives
- Find which area has more birds  
- Understand which birds prefer forest or grassland  
- Study how weather affects bird activity  

---

## 📊 Dataset Description
- Source: Bird Monitoring Dataset  
- Format: Excel files with multiple sheets  
- Each sheet represents a different **location (Admin Unit)**  

### Key Columns:
- `Common_Name` → Bird species  
- `Date` → Observation date  
- `Habitat_Type` → Forest / Grassland  
- `Initial_Three_Min_Cnt` → Bird observed (True/False)  
- `Temperature`, `Sky`, `Wind` → Weather conditions  

---

## ⚙️ Data Processing Steps

### 1. Data Loading
- Loaded multiple Excel sheets using **pandas**

### 2. Data Combining
- Combined all sheets into one dataset  
- Added:
  - `Admin_Unit` (location)
  - `Habitat_Type` (Forest / Grassland)

### 3. Data Cleaning
- Removed duplicate records  
- Converted date column to datetime  
- Handled missing values carefully  

### 4. Feature Engineering
- Converted boolean observation to numeric:
  - True → 1  
  - False → 0  
- Created:
  - `Count` column  
  - `Month`, `Year`  

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Habitat Distribution
- Forest vs Grassland comparison  
- Nearly equal bird observations in both habitats  

### 🔹 Top Bird Species
- Identified most frequently observed species  

### 🔹 Location Analysis
- Found areas with highest bird activity  

### 🔹 Weather Impact
- Analyzed bird activity based on:
  - Sky condition  
  - Temperature  

### 🔹 Time Analysis
- Monthly trend of bird observations  

---

## 📊 Visualizations
- Bar Charts (Habitat, Location, Species)  
- Line Chart (Monthly Trend)  
- Pie Chart (Habitat Distribution)  
- Scatter Plot (Temperature vs Activity)  
- Heatmap (Advanced Analysis)  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- Power BI  

---

## 📁 Project Files
- `bird_analysis.ipynb` → Main analysis notebook  
- `cleaned_bird_data.csv` → Cleaned dataset  
- `README.md` → Project documentation  

---

## 📌 Key Insights
- Bird activity is almost equally distributed between forest and grassland  
- Some species show strong habitat preference  
- Weather conditions influence bird observations  
- Certain locations have higher bird density  

---

## 🚀 Conclusion
This project demonstrates how data analysis can help understand ecological patterns and support environmental planning.

---


## ⭐ GitHub
If you like this project, give it a ⭐ on GitHub!
