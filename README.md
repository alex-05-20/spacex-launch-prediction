# 🚀 SpaceX Launch Success Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Science-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-Data%20Analysis-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Power%20BI%20%2F%20Dashboards-Visualization-F2C811?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

This project aims to **predict the success of SpaceX Falcon 9 first-stage landings** using historical launch data.  

The ability to predict landing success is critical for reducing operational costs, improving mission planning, and enabling reusable rocket technology.

👉 This project demonstrates a **complete end-to-end data workflow**:
- Data collection  
- Data cleaning & preparation  
- Exploratory analysis  
- Data visualization  
- Machine learning modeling  

---

## 📊 Full Presentation

<p align="center">
  <a href="https://github.com/alex-05-20/IBM-Data-Science-Applied-Capstone/blob/main/SpaceX%20Launch%20Success%20Prediction%20%E2%80%93%20Data%20Science.pptx">
    <img src="https://img.shields.io/badge/View%20Presentation-PowerPoint-orange?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white"/>
  </a>
</p>

---
## 🎯 Business Problem

Reusable rocket systems are a major innovation in the aerospace industry.

Predicting whether a rocket will successfully land allows companies to:
- Reduce mission costs (up to ~$100M per launch)
- Improve planning and logistics
- Optimize operational decision-making
- Reduce technical risks

👉 The objective is to build a model capable of predicting:
**Will the first stage successfully land?**

---

## 📊 Data Sources

Data was collected from multiple sources:

### 1. SpaceX API
- Flight number  
- Booster version  
- Payload mass  
- Launch site  
- Orbit type  
- Landing outcome  
- Reuse indicators  

### 2. Wikipedia (Web Scraping)
- Launch records  
- Payload details  
- Customer information  
- Booster landing status  

---

## ⚙️ Methodology

### 1. Data Collection
- Extracted data using **SpaceX REST API**
- Performed **web scraping** using BeautifulSoup
- Combined datasets into structured DataFrames

---

### 2. Data Cleaning & Preparation
- Handled missing values (imputation)
- Created target variable (`class`: success/failure)
- Standardized features
- Applied **one-hot encoding** for categorical variables

---

### 3. Exploratory Data Analysis (EDA)

Performed using **SQL and Python visualizations**:

- Payload vs success rate  
- Launch site vs success  
- Orbit type vs success  
- Time evolution of landing success  

📈 Key techniques:
- Scatter plots  
- Line charts  
- Bar charts  

---

### 4. Interactive Data Visualization

Built interactive tools to explore data:

- 📍 **Folium Maps**
  - Launch sites visualization
  - Success vs failure mapping
  - Geographic insights

- 📊 **Plotly Dash Dashboard**
  - Success rate by launch site  
  - Payload vs success  
  - Dynamic filtering  

---

### 5. Machine Learning Modeling

Developed multiple classification models:

- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree  
- K-Nearest Neighbors (KNN)  

📌 Process:
- Train/test split  
- Feature scaling (StandardScaler)  
- Hyperparameter tuning (GridSearchCV)  

---

## 📈 Results

- All models achieved similar performance  
- 🎯 **Accuracy: ~83.33%**  
- Models slightly overpredict successful landings  
- Dataset size limits model performance  

---

## 🔍 Key Insights

- 🚀 Launch success rate improves significantly over time  
- 📍 Certain launch sites are more reliable  
- ⚖️ Payload mass influences success probability  
- 🌍 Geographic factors impact landing success  
- 🔁 Reusability features strongly correlate with outcomes  

---

## 🛠️ Tech Stack

### Languages
- Python  
- SQL  

### Libraries
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

### Visualization
- Plotly Dash  
- Folium  

### Data Collection
- REST API  
- BeautifulSoup (web scraping)  

### Tools
- Jupyter Notebook  
- GitHub  

---

## 📁 Project Structure
- data_collection/
- data_wrangling/
- eda_sql/
- eda_visualization/
- dashboards/
- machine_learning/
- notebooks/
- README.md

---

## 🚀 Future Improvements

- Increase dataset size  
- Handle class imbalance  
- Test advanced models (Random Forest, XGBoost)  
- Deploy model as an API  
- Build a web app interface  

---

## 📸 Example Outputs

👉 (Add screenshots here for maximum impact)
- Dashboard visuals  
- Maps  
- Model performance graphs  

---

## 👤 Author

**Alex Cabrel TSAPI KOUDJOU**

- 📧 koudjoualex2005@gmail.com  
- 🔗 LinkedIn: https://linkedin.com/in/alex-tsapi  
- 💻 GitHub: https://github.com/alex-05-20  

---

## ⭐ Conclusion

This project demonstrates my ability to:
- Work with **real-world multi-source data**
- Build **end-to-end data pipelines**
- Apply **machine learning models**
- Deliver **business-relevant insights**
