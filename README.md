# 📊 Online Education Student Performance Analysis

## 📌 Project Overview
This project analyzes student data from an online education platform to explore how **student engagement and online learning activity** relate to academic performance. 

The analysis focuses primarily on key metrics such as **total clicks, engagement levels, pass status, and final results**. By applying Exploratory Data Analysis (EDA) and a **Logistic Regression model**, this project identifies key patterns in student learning behavior and predicts academic outcomes based on online engagement.

---

## 🎯 Objectives
* **Analyze Performance:** Evaluate student performance trends in an online learning environment.
* **Examine Engagement:** Measure the correlation between student activity (`total_clicks`) and pass rates.
* **Identify Behavioral Patterns:** Understand how learning habits impact academic success and risk levels.
* **Predict Outcomes:** Build a Logistic Regression model using `total_clicks` to predict student outcomes (`pass_flag`).
* **Visualize Insights:** Present findings clearly using detailed charts and data visualizations.

---

## 📂 Dataset Overview
The dataset contains **32,593 student records** across **14 features**:

| Feature | Description |
| :--- | :--- |
| `id_student` | Unique identifier for each student |
| `gender` | Gender of the student |
| `region` | Geographic region of the student |
| `highest_education` | Highest qualification prior to entry |
| `studied_credits` | Total number of credits currently being studied |
| `imd_band` | Socio-economic / deprivation band |
| `total_clicks` | Total number of interactions/clicks on the platform |
| `avg_score` | Average score across assessments |
| `engagement_level` | Categorical engagement metric (*Low, Medium, High*) |
| `performance_level` | Categorical performance metric (*Low, Medium, High*) |
| `risk_level` | Predicted student risk category |
| `pass_flag` | Binary indicator for passing the course (*1 = Pass, 0 = Fail*) |
| `dropout_flag` | Binary indicator for course completion status |

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Analysis & Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression)

---

## 🚀 Key Features & Workflow
1. **Data Cleaning & Preprocessing:** Handling missing values, categorical encoding, and feature scaling.
2. **Exploratory Data Analysis (EDA):** Visualizing distributions of `total_clicks`, pass/fail ratios across demographic bands, and engagement levels.
3. **Predictive Modeling:** Training a Logistic Regression model on student interaction metrics to forecast `pass_flag`.
4. **Model Evaluation:** Assessing accuracy, precision, recall, and ROC-AUC metrics.

---

## 📊 Key Insights
* Higher `total_clicks` directly correlate with increased pass rates, confirming online engagement as a strong indicator of success.
* Students in the **High Engagement** category exhibit lower dropout rates compared to those with sporadic activity patterns.

---

## 👤 Author
* **Kirithik**
