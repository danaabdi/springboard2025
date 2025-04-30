# springboard2025
# 🏥 Farm Insurance Co — Medical Insurance Cost Analysis

This project explores a dataset from **Farm Insurance Co**, aiming to understand the key drivers behind medical insurance charges across demographic groups.

## 📊 Objectives

- Analyze the influence of **age**, **BMI**, **region**, **smoking status**, and **gender** on insurance costs
- Identify and remove **outliers** for cleaner insights
- Visualize key patterns using **matplotlib** and **seaborn**
- Compute **correlation metrics** to identify top predictors
- Use **boxplots and histograms** to explore variable relationships

## 📁 Key Files

- `insurance_analysis.ipynb`: Main Jupyter Notebook with data cleaning, EDA, and visualizations
- `cleaned_data.csv`: Final version of the dataset after outlier removal

## ✅ Tools Used

- Python, Pandas, NumPy
- Seaborn & Matplotlib for visualization
- Jupyter Notebook
## 💡 Key Insights: 

### 🔺 Strongest Positive Correlations
- **Smoker (0.79)** → The highest correlation; being a smoker has the strongest impact on increasing medical insurance charges.
- **Age (0.30)** → Older individuals tend to have higher insurance costs.
- **Senior (0.20)**, **BMI (0.20)**, and **BMI_Overweight (0.20)** → Older age and higher BMI are strongly associated with increased charges.

### 🟠 Moderate Positive Correlations
- **Mature Age Adult (0.14)** → Middle-aged adults have moderately higher costs.
- **Southeast (0.07)** and **Gender (0.06)** → Minor positive impact on insurance charges.

### ⚪ Near Zero Correlations
- **Northeast (0.01)**, **Northwest (-0.04)**, **Southwest (-0.04)** → Regional impact is negligible.
- **BMI_Underweight (-0.04)** → Minimal impact on charges.

### 🔻 Negative Correlations (Lower Charges)
- **BMI_Healthy (-0.11)** and **Adult (-0.11)** → Healthy BMI and general adult population tend to have lower insurance costs.
- **BMI_Slightly_Overweight (-0.12)** → Lower charges than overweight individuals.
- **Young Adult (-0.19)** → Young adults have significantly lower costs, likely due to lower health risk.

---

👩‍💻 Created by [Dana Abdirakhym] | 📫 [abdirakhymd@gmail.com]  

