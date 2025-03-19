# Air Pollution Contingency Prediction  

## Project Overview  
This project aims to analyze historical air pollution data to determine whether we can predict environmental contingencies.  
We use the most recent **SEDEMA (Secretaría del Medio Ambiente) air quality standards** from Mexico City as a reference.  

## Data Sources  
The dataset can be accessed from:  
- [Mexico City Air Quality Monitoring System](http://www.aire.cdmx.gob.mx/default.php)  
- [Google Drive Link](https://drive.google.com/file/d/119-7fzTdKmC3PhMp3TzeDFhL_Wf6xlK8/view?usp=drive_link)  

## Key Considerations  
To develop a predictive model, we analyze:  
✔ **Temporal behavior** of air pollution data  
✔ **Spatial distribution** of pollutants across different monitoring stations  
✔ **Relationships between pollutant species** to identify key patterns  

---

## Methodology  

### **1. Data Exploration**  
- Analyze the **correlation between variables** (Ozone, NOx, etc.).  
- Identify key trends and dependencies.  

### **2. Data Preprocessing**  
- Handle **missing values** in the dataset.  
- Normalize data where necessary.  

### **3. Modeling**  
- Define **target variables** (e.g., ozone levels) and **predictor variables** (e.g., NOx, CO).  
- Implement **linear and non-linear regression models** for prediction.  
- Use **Support Vector Machines (SVM)** to classify contingency precursors.  

---

## Descriptive Analysis Requirements  

✔ **Plot the distribution of ozone levels** across different regions of the city.  
✔ **Compute the correlation matrix** for ozone data from multiple monitoring stations.  
✔ **Identify peak ozone hours** for each day in different areas of the city.  
✔ **Create scatter plots** to analyze relationships between ozone and NOx.  

---

## Technologies Used  
- **Python** (data analysis and modeling)  
- **Pandas & NumPy** (data manipulation)  
- **Matplotlib & Seaborn** (visualization)  
- **Scikit-learn** (machine learning models)

---

## Installation  
1️⃣ Clone the repository:  
```bash
git clone https://github.com/yourusername/air-pollution-prediction.git
cd air-pollution-prediction

pip install -r requirements.txt

jupyter notebook "air_pollution_analysis.ipynb"
