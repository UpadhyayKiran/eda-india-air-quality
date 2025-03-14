# **Exploratory Data Analysis (EDA) on Air Quality Data in India**

## **Project Overview**
This project performs **Exploratory Data Analysis (EDA)** on the **Air Quality Data in India** sourced from Kaggle. The objective is to identify pollution trends, analyze key factors affecting air quality, and visualize important insights.

## **Dataset Details**
- **Dataset Name:** Air Quality Data in India
- **Source:** Kaggle ([Link](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india))
- **File Format:** CSV
- **Key Features:**
  - **Date** - Timestamp of the air quality reading
  - **City** - Location of measurement
  - **PM2.5, PM10, NO2, SO2, CO** - Major air pollutants
  - **AQI** - Air Quality Index

## **Project Workflow**
### **1. Data Cleaning**
- Handled missing values:
  - Numerical columns filled with **mean** values.
  - Categorical columns handled via **mode imputation** or dropped (if necessary).
- Removed duplicate rows to maintain data integrity.
- Converted `Date` column to **datetime format**.

### **2. Exploratory Data Analysis (EDA)**
- **Descriptive Statistics**:
  - Summary statistics for numerical and categorical features.
  - Identified variance and distribution of pollutants.
- **Visualizations**:
  - **Histograms & Box Plots:** Distribution and outlier detection.
  - **Scatter Plots:** Relationships between pollutants.
  - **Heatmaps:** Correlation between air pollutants.
  - **Time-Series Analysis:** Pollution trends over months.

### **3. Advanced Python Techniques**
- **Lambda Functions:** Categorized PM2.5 levels into **Good, Moderate, Poor**.
- **User-Defined Functions:** Created a function to classify pollution severity.
- **List Comprehensions:** Identified columns with missing values efficiently.

### **4. Key Insights**
- **PM2.5 & PM10 are the strongest contributors to poor air quality.**
- **Seasonal variations** impact pollution levels (higher in winter, lower in monsoon).
- **Certain cities consistently show higher pollution levels.**

### **5. Future Work**
- Build a **machine learning model** to predict air quality trends.
- Conduct a **comparative study** with global pollution data.
- Explore **health impact correlations** with AQI data.

## **How to Run the Project**
1. Install necessary libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Open Jupyter Notebook and run `EDA_AirQuality.ipynb`.
3. Ensure the dataset `AirQualityIndia.csv` is in the same directory.
4. The notebook will generate visualizations and insights.

## **Files in the Project**
- `EDA_AirQuality.ipynb` → Jupyter Notebook containing the complete analysis.
- `city_day.csv` → Dataset file.
- `README.md` → Project documentation.
- `EDA_AirQuality_Presentation.pptx` → PowerPoint slides summarizing findings.

## **Acknowledgments**
This dataset is provided by **Rohan Rao** on Kaggle. Special thanks to the **Kaggle community** for making such datasets publicly available.

