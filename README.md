# HR Analytics Dashboard with Attrition Prediction

This project combines **HR analytics** and **machine learning** to analyze employee attrition trends and predict future attrition risks. It uses **Google Colab** for data preprocessing and modeling, and **Power BI** for interactive visualizations.

---

## 📁 Files Included

- `HR_Analytics.csv` – The main dataset containing employee records.
- `HR_Attrition_Analysis.ipynb`: Google Colab notebook for EDA, preprocessing, and ML modeling.
- `HR Analytics Dashboard.pbix`: Power BI dashboard file for interactive insights.

---

## 📊 Dashboard Insights (Power BI)

**Key Metrics:**
- **Employees:** 1,470  
- **Attrition Count:** 237  
- **Attrition Rate:** 16.1%  
- **Avg Age:** 37  
- **Avg Salary:** 6.5K  
- **Avg Tenure:** 7 years  

**Notable Trends:**
- Highest attrition: Age group 26–35  
- Males show more attrition than females  
- Life Sciences and Medical grads have higher attrition  
- Employees earning under 5K are most likely to leave  
- Laboratory Technicians and Sales Executives are top roles in attrition  

---

## 🤖 Prediction Model

A machine learning model was created to **predict employee attrition** using classification algorithms. The following models were tested:

| Model               | Accuracy | Precision | Recall   | F1-Score |
|--------------------|----------|-----------|----------|----------|
| Logistic Regression| 0.8581   | 0.6667    | 0.2128   | 0.3226   |
| Random Forest      | 0.8682   | 1.0000    | 0.1702   | 0.2909   |
| KNN                | 0.8378   | 0.4286    | 0.0638   | 0.1111   |

📌 **Best Model (Accuracy-wise):** Random Forest (86.82%)  
⚠️ **Note:** Despite high accuracy and precision, all models show low recall—suggesting underperformance in identifying true attrition cases. Future improvement could involve class balancing or boosting methods.

---


### Models Used:
- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)


---
## 🔧 How to Use

### 1. Google Colab Notebook
- Open `HR_Attrition_Analysis.ipynb` in Google Colab.
- Ensure libraries (`pandas`, `sklearn`, `matplotlib`, `seaborn`) are installed.
- Run the code to explore data, preprocess it, and evaluate models.

### 2. Power BI Dashboard
- Open `HR Analytics Dashboard.pbix` in Power BI Desktop.
- Explore attrition trends using slicers and interactive charts.

---

## 🛠️ Tech Stack

- **Google Colab (Python)** – EDA, preprocessing, ML model building  
- **Power BI** – Interactive dashboard and insights  
- **Libraries Used:** Pandas, Scikit-learn, Seaborn, Matplotlib

---

## 🚀 Future Work

- Improve model recall with SMOTE or other resampling techniques
- Deploy prediction model with a web interface
- Add live data streaming to Power BI dashboard

---

## 📬 Contact

For any queries or collaborations, feel free to reach out at: [samvit.acharya05@gmail.com]
