
# **Athlete Injury Analysis & Prediction**  

📌 **Project Overview**  
This project analyzes athlete injury data to identify patterns, trends, and risk factors using data science and machine learning techniques. By leveraging **K-Nearest Neighbors (KNN), Decision Tree, and Random Forest**, we aim to predict injury risks and provide insights to help athletes and coaches take preventive measures.  

---

## **📂 Dataset Information**  
The dataset contains historical injury records of athletes, including:  
- **athlete_id** → Unique identifier for each athlete  
- **date** → Date of recorded injury (YYYY-MM-DD format)  
- **Other relevant features** that contribute to injury analysis  

🔹 **Total Records:** 137  
🔹 **Unique Athletes:** 30  
🔹 **Unique Injury Dates:** 126  

---

## **📊 Data Analysis & Insights**  
### ✅ **Key Findings from Exploratory Data Analysis (EDA):**  
✔️ **Identified High-Risk Athletes** → Some athletes had significantly higher injury counts.  
✔️ **Detected Seasonal Injury Trends** → Certain periods showed spikes in injury occurrences.  
✔️ **Found Most Frequent Injury Dates** → Helps in scheduling injury prevention programs.  
✔️ **Feature Importance Analysis** → Determined key risk factors using ML models.  

### 📈 **Visualizations Used:**  
- Injury trends over time  
- Distribution of injuries per athlete  
- Heatmaps & correlation analysis  

---

## **🤖 Machine Learning Models Used**  
1️⃣ **K-Nearest Neighbors (KNN)** → Classifies athletes based on past injury patterns.  
2️⃣ **Decision Tree** → Provides an interpretable model to identify key risk factors.  
3️⃣ **Random Forest** → An ensemble model improving accuracy and reducing overfitting.  

📌 **Goal:** To predict injury risks and recommend preventive actions for athletes.  

---

## **🛠️ Tech Stack**  
🔹 **Programming Language:** Python  
🔹 **Libraries Used:**  
   - `pandas`, `numpy` → Data processing  
   - `matplotlib`, `seaborn` → Data visualization  
   - `scikit-learn` → Machine learning models  
   - `datetime`, `warnings`, `re` → Data cleaning  

---

## **📌 How to Use This Project?**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/Athlete-Injury-Analysis.git
cd Athlete-Injury-Analysis
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**  
```bash
jupyter notebook
```
Open `Athlete_Injury_Analysis.ipynb` and execute the cells.  

---

## **🔮 Future Improvements**  
🔹 Incorporate **Deep Learning models** (e.g., Neural Networks) for enhanced predictions.  
🔹 Expand dataset with **more injury-related factors** (age, training load, etc.).  
🔹 Deploy a **web dashboard** for real-time injury risk assessment.  

---
