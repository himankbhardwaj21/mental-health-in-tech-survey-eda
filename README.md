# Mental Health in Tech Workplace – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a mental health survey dataset collected from professionals working in the technology sector.  
The goal of this analysis is to understand employee mental health trends, workplace support systems, treatment-seeking behavior, and their overall impact on productivity and organizational culture.

The project follows **EDA best practices**, includes **data cleaning**, **structured visual analysis using the UBM framework**, and provides **business-driven insights and recommendations**.

---

## 🎯 Problem Statement
Mental health issues in the tech industry are often underreported due to stigma, lack of awareness, and insufficient organizational support. These challenges can negatively affect employee productivity, engagement, and retention. There is a need to analyze real-world data to better understand mental health patterns and workplace attitudes.

---

## 🎯 Business Objective
- Analyze mental health trends among tech professionals  
- Identify factors influencing mental health treatment and work interference  
- Evaluate the role of organizational support and workplace policies  
- Provide actionable insights to help organizations improve employee well-being and productivity  

---

## 📂 Dataset Information
- **Dataset Name:** Mental Health in Tech Survey
- **Source:** Open Sourcing Mental Illness (2014 Survey)
- **Data Type:** Structured survey data
- **Key Features:**
  - Demographics (Age, Gender, Country)
  - Workplace environment (Remote work, Benefits, Wellness programs)
  - Mental health factors (Family history, Treatment, Work interference)
  - Employee perceptions and openness

---

## 🧹 Data Preprocessing & Cleaning
The following data wrangling steps were performed:
- Handled missing values using meaningful labels
- Removed duplicate records
- Filtered unrealistic age values
- Standardized inconsistent categorical values (e.g., Gender)
- Ensured the notebook is **deployment-ready** and runs in a single execution

---

## 📊 Exploratory Data Analysis (UBM Framework)

### 🔹 Univariate Analysis
- Age distribution of respondents  
- Gender distribution  
- Mental health treatment status  
- Family history of mental illness  
- Work interference due to mental health  
- Remote work adoption  
- Availability of mental health benefits  
- Awareness of wellness programs  

### 🔹 Bivariate Analysis
- Family history vs treatment
- Gender vs treatment
- Age vs treatment
- Work interference vs treatment
- Benefits vs treatment
- Supervisor & coworker openness vs treatment
- Mental vs physical health perception

### 🔹 Multivariate Analysis
- Gender × Family History × Treatment
- Age × Work Interference × Treatment
- Benefits × Care Options × Treatment
- Remote Work × Work Interference × Treatment

> A total of **20+ meaningful visualizations** were created with insights and business impact explanations for each.

---

## 💡 Key Insights
- Mental health issues significantly impact work performance
- Employees with family history are more likely to seek treatment
- Organizational support and benefits increase treatment-seeking behavior
- Lack of awareness about wellness programs reduces their effectiveness
- Supportive leadership and flexible work policies improve employee well-being

---

## ✅ Solution to Business Objective
Organizations should prioritize mental health by:
- Providing comprehensive mental health benefits
- Improving communication and awareness of care options
- Encouraging open discussions with managers and peers
- Implementing flexible or remote work policies
- Training leadership to handle mental health concerns sensitively

---

## 🏁 Conclusion
This EDA highlights the importance of mental health support in the tech industry. Data-driven insights show that organizations investing in employee well-being can improve productivity, retention, and workplace culture. The findings can help decision-makers design effective mental health strategies and policies.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab
