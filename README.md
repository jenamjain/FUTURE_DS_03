# 🎓 Task 3 — College Event Feedback Analysis  
### Future Interns | Data Science & Analytics Internship

This repository contains **Task 3** of my **Data Science & Analytics Internship** with **Future Interns**, focusing on analyzing student feedback from college events.  
The objective of this task is to perform **data cleaning, preprocessing, exploratory analysis, and sentiment labeling**, leading to a structured result file:  
📁 `College_Event_Feedback_Result.csv`

---

## 🧩 Project Overview

College events are an important part of student life, and collecting feedback helps institutions improve future experiences.  
This project aims to **analyze feedback provided by students** to determine whether the sentiment is **Positive**, **Neutral**, or **Negative**.

### 🎯 Objectives
- Clean and preprocess raw feedback text  
- Explore data and visualize overall feedback sentiment trends  
- Perform **Sentiment Analysis** using the TextBlob library  
- Classify feedback into **Positive**, **Neutral**, or **Negative**  
- Export the final structured dataset into `College_Event_Feedback_Result.csv`

---

## 🧠 Workflow Summary

### 1️⃣ Data Cleaning
- Removed null values and duplicates  
- Processed text data for uniformity  

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized overall feedback sentiment  
- Analyzed patterns and trends within the data  

### 3️⃣ Sentiment Analysis
- Applied **TextBlob** polarity scoring  
- Mapped polarity results to three categories:
  - Positive  
  - Neutral  
  - Negative  

### 4️⃣ Export Final Results
- Final processed data with sentiment results saved to:  
  ✅ **`College_Event_Feedback_Result.csv`**

---

## 📊 Result Example (Preview)

| Feedback | Sentiment |
|-----------|------------|
| “The event was fantastic and very well organized.” | Positive |
| “It was okay, could have been better.” | Neutral |
| “I didn’t like the arrangements at all.” | Negative |

---

## ⚙️ Tools & Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, TextBlob  
- **Environment:** Jupyter Notebook  

---

## 📁 Project Files

| File Name | Description |
|------------|-------------|
| `feedback student.csv` | Original dataset |
| `College_Event_Feedback_Result.csv` | Final processed dataset with sentiments |
| `College_Event_Feedback_Analysis.ipynb` | Jupyter Notebook containing full analysis |
| `requirements.txt` | Required Python dependencies |
| `README.md` | Project documentation |

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/jenamjain/FUTURE_DS_03.git
   cd Task-3
