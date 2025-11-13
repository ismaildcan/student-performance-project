# 📊 Student Performance Analysis  
*A Beginner Data Portfolio Project by İsmail Demircan*

## 📌 Project Overview
This project analyzes a public dataset containing exam scores and demographic information of middle school students.  
The main goal is to explore **which factors are most strongly associated with student performance**.

This project is designed as a **beginner-friendly portfolio project**, using Python, pandas, and matplotlib.

---

## 🎯 Objectives
- Understand the structure of the dataset  
- Perform exploratory data analysis (EDA)  
- Visualize important patterns  
- Identify factors that may influence student success  
- Summarize key insights and actionable recommendations  

---

## 📁 Dataset
**Dataset name:** Students Performance in Exams (Kaggle)  
**Rows:** 1000 students  
**Columns:**  
- `gender`  
- `race/ethnicity`  
- `parental level of education`  
- `lunch`  
- `test preparation course`  
- `math score`  
- `reading score`  
- `writing score`

Additionally, a new column was created:


This score was used as the main performance metric.

---

## ❓ Research Questions
1. What is the distribution of student exam scores?  
2. Do female and male students differ in overall performance?  
3. Does completing a test preparation course improve student performance?  
4. Does lunch type (standard vs. free/reduced) affect student scores?  
5. Is there a relationship between parental education level and student performance?  

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ Score Distribution  
Most students scored between **60 and 80**, indicating an overall medium–high performance level.  
A small group scored below 40, representing a risk group.

### 2️⃣ Performance by Gender  
| Gender | Average Score |
|--------|---------------|
| Female | 69.56 |
| Male   | 65.83 |

Female students show a slightly higher average performance (+3.7 points).

### 3️⃣ Test Preparation Course  
| Course Status | Average Score |
|---------------|---------------|
| Completed     | 72.66 |
| None          | 65.83 |

Students who completed the test preparation course performed significantly better (+7 points).  
This is one of the strongest effects observed.

### 4️⃣ Lunch Type (Socioeconomic Indicator)
| Lunch Type     | Avg Score |
|----------------|-----------|
| Standard       | 70.84 |
| Free/Reduced   | 62.19 |

Students receiving free/reduced lunch scored **8.6 points lower**, suggesting a strong socioeconomic impact on performance.

### 5️⃣ Parental Education Level  
Higher parental education is generally associated with higher student scores.

| Parent Education Level | Avg Score |
|------------------------|-----------|
| master's degree        | 73.59 |
| bachelor's degree      | 71.92 |
| associate's degree     | 69.56 |
| some college           | 68.47 |
| high school            | 63.09 |
| some high school       | 65.10 |

Students whose parents hold a **master's or bachelor's degree** tend to perform notably better.

---

## ⭐ Key Insights
- Completing a **test preparation course** has a strong positive effect on performance.  
- **Socioeconomic factors** (lunch type) play a significant role in student achievement.  
- **Parental education level** is positively correlated with student success.  
- Gender differences exist but are relatively small.  
- Most students fall into the mid-performance range (60–80 overall score).

---

## 🧭 Conclusion & Recommendations

### ✔ Conclusions
Student performance is influenced by multiple demographic and social factors, especially:  
- Academic support (test preparation)  
- Socioeconomic background  
- Parental education  

### ✔ Recommendations
- Provide additional **support programs** for low-income students.  
- Encourage participation in **test preparation courses**.  
- Offer **family engagement programs** to increase academic support at home.  
- Track students in the risk group (low scores) for early intervention.

---

## 🛠️ Technologies Used
- Python  
- pandas  
- matplotlib  
- Jupyter Notebook  

---

## ▶️ How to Run This Project
1. Clone the repository  
2. Install dependencies:  

3. Open the notebook:  

4. Run each cell in order.

---

## 👤 Author
**İsmail Demircan**  
M.Sc. Data Science Student – UE Germany