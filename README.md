# 🎓 Student Feedback Analysis – Internship Project

## 📌 Overview
This project analyzes **student course feedback** collected via surveys.  
The dataset contains ratings (1–10 scale) across multiple teaching criteria such as subject knowledge, presentation usage, assignment difficulty, and overall course recommendation.  

The goal is to transform raw feedback into **actionable insights** for educators and organizers.

---

## 🎯 Objectives
- Clean and prepare survey data.
- Visualize distributions and averages of ratings.
- Identify correlations between teaching qualities.
- Highlight strengths and weaknesses in course delivery.
- Generate a professional PDF report with charts.

---

## 🛠 Tools & Libraries
- **Google Colab** – cloud-based notebook environment
- **pandas** – data manipulation
- **matplotlib / seaborn** – visualizations
- **numpy** – numerical operations
- **openpyxl** – Excel file support

Install dependencies in Colab:
```bash
!pip install pandas matplotlib seaborn openpyxl

---

## 📂 Dataset
File: student_feedback.xlsx

---

## 📂 Columns include:

Well versed with the subject

Explains concepts in an understandable way

Use of presentations

Degree of difficulty of assignments

Solves doubts willingly

Structuring of the course

Provides support for students going above and beyond

Course recommendation based on relevance

---

## 📊 Visualizations
The notebook generates the following charts:

Bar chart → Average scores per criterion

Count plot → Distribution of course recommendation ratings

Heatmap → Correlation between criteria

Boxplots → Spread of ratings

Histograms → Distribution for each question

Radar chart → Overall strengths/weaknesses

Violin plots → Density + variability

Pairplot → Relationships between criteria

Line chart → Trend across criteria

---

## 📁 Final Deliverable
A Google Colab Notebook with clean, well-commented code.

A PDF report (student_feedback_report.pdf) containing all charts.

Download in Colab:

python
from google.colab import files
files.download("student_feedback_report.pdf")

---

## 🚀 How to Run
Open the notebook in Google Colab.

Upload student_feedback.xlsx.

Run all cells to generate charts.

Export the PDF report for submission.
