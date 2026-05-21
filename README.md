# 📱 Social Media Impact on Teenagers – Data Analysis Project

DASHBOARD URL (Claude): https://claude.ai/public/artifacts/994e3ad3-df40-4df7-ab3e-8ea9f2abcae6

DASHBOARD URL (Netlify):impacts-on-teenager-dashboard.netlify.app

## 📌 Project Overview
This project analyzes the impact of social media usage on teenagers’ mental health, lifestyle, sleep quality, and academic performance using Python data analysis techniques.

The main objective of this project is to understand how excessive social media usage affects:
- Stress levels
- Anxiety levels
- Addiction behavior
- Sleep quality
- Academic performance
- Overall wellness

The dataset contains behavioral, psychological, and lifestyle-related attributes of teenagers.

---

# 🎯 Objectives
- Analyze teenagers’ social media usage patterns
- Identify relationships between screen time and mental health
- Study the effect of sleep and physical activity on wellness
- Create engineered features for deeper analysis
- Prepare the dataset for machine learning and predictive analysis

---

# 📂 Dataset Features

| Column Name | Description |
|---|---|
| age | Age of teenager |
| gender | Gender of student |
| platform_usage | Preferred social media platform |
| daily_social_media_hours | Daily social media usage hours |
| screen_time_before_sleep | Screen usage before sleeping |
| usage_category | Categorized social media usage |
| sleep_hours | Daily sleeping hours |
| sleep_category | Sleep quality category |
| physical_activity | Physical activity level |
| social_interaction_level | Social interaction level |
| academic_performance | Academic performance score |
| stress_level | Stress score |
| anxiety_level | Anxiety score |
| addiction_level | Social media addiction score |
| mental_health_score | Combined mental health indicator |
| wellness_score | Overall wellness indicator |
| depression_label | Depression prediction label |

---

# 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🧹 Data Cleaning & Preprocessing
The following preprocessing steps were performed:
- Removed duplicate records
- Checked missing values
- Standardized categorical data
- Validated logical ranges
- Handled outliers using IQR capping
- Created engineered features
- Organized and structured dataset columns

---

# ⚙ Feature Engineering

## Created Features

### 1. mental_health_score
Combined:
- stress_level
- anxiety_level
- addiction_level

Used as an overall psychological health indicator.

---

### 2. sleep_category
Categorized sleep quality into:
- Poor
- Average
- Good

---

### 3. usage_category
Categorized social media usage into:
- Low
- Moderate
- High

---

### 4. wellness_score
Combined:
- sleep_hours
- physical_activity
- academic_performance

Used as an overall wellness indicator.

---

# 📊 Exploratory Data Analysis (EDA)

The project includes:
- Correlation analysis
- Heatmaps
- Scatterplots
- Boxplots
- Regression plots
- Platform comparison analysis
- Gender-based analysis
- Mental health trend analysis

---

# 🔍 Key Insights
Some expected insights from the dataset:
- Higher social media usage may increase stress and anxiety levels
- Excessive screen time before sleep may reduce sleep quality
- Higher addiction scores may negatively affect academic performance
- Physical activity may help reduce depression indicators

---

# 🤖 Future Scope
This dataset can further be used for:
- Depression prediction models
- Mental health risk classification
- Behavioral analytics
- Dashboard creation
- Machine learning projects

---

# 📈 Possible Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Linear Regression

---

# 📌 Conclusion
This project demonstrates how social media usage patterns can influence teenagers’ mental and physical well-being. By analyzing behavioral and psychological factors, the project helps in understanding the growing impact of digital lifestyles on modern teenagers.

---

# 👨‍💻 Author
**Alikaif JAfri**

Data Analysis & Behavioral Analytics Project using Python.
