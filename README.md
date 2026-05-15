# 📊 Student Performance — EDA & Data Visualization

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/Status-Complete-1D9E75?style=for-the-badge"/>

---

> 🔍 **"Performed Exploratory Data Analysis (EDA) on a real-world student performance dataset using Python, Pandas, and Matplotlib — uncovering hidden patterns through filtering, grouping, and powerful visualizations."**

---

## 🚀 What This Project Does

This project dives deep into a **real-world student dataset** of 1000 students to answer questions like:

- 📌 Do male or female students perform better in Math?
- 📌 Does lunch type affect student scores?
- 📌 Does test preparation course actually help?
- 📌 How does parental education level impact performance?

All answered using **data — not guesswork.** 📊

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| 📁 File | `StudentsPerformance.csv` |
| 👥 Records | 1000 Students |
| 📋 Columns | Gender, Race/Ethnicity, Parental Education, Lunch, Test Prep, Math Score, Reading Score, Writing Score |
| 🌐 Source | Real-world open dataset |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python 3 | Core Language |
| 🐼 Pandas | Data Loading, Filtering, GroupBy Analysis |
| 📊 Matplotlib | Charts & Visualizations |
| 📓 Jupyter Notebook | Interactive Development |

---

## 📋 Project Workflow

```
📂 Load CSV Data
      ↓
🔍 Understand Dataset (shape, columns, info, null check)
      ↓
📊 Basic Analysis (mean, max, min, top 5, bottom 5)
      ↓
🔎 Filtering (gender, score ranges, lunch type, test prep)
      ↓
📈 GroupBy Analysis (gender-wise, lunch-wise, education-wise)
      ↓
🎨 Visualizations (Histogram + Bar Charts)
      ↓
💾 Save Charts as PNG files
```

---

## 📈 Visualizations Created

| # | Chart Type | What It Shows |
|---|-----------|---------------|
| 1️⃣ | Histogram | Distribution of Math Scores across all students |
| 2️⃣ | Bar Chart | Average Math Score — Male vs Female comparison |

---

## 🔍 Key Analysis Done

**📌 Basic Stats:**
- Average Math Score across 1000 students
- Highest Reading Score & Lowest Writing Score
- Top 5 Math Toppers & Bottom 5 Reading Scorers

**📌 Filtering:**
- Female students only
- Students with Math Score > 90
- Students with Reading Score < 40
- Standard lunch students
- Test preparation completed students

**📌 GroupBy Analysis:**
- Gender-wise average Math & Reading scores
- Lunch type wise average Writing score
- Parental education level wise average Math score

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/priyanshupatel-tech/Student-EDA-Matplotlib.git
   cd Student-EDA-Matplotlib
   ```

2. Install required libraries:
   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Make sure `StudentsPerformance.csv` is in the same folder

4. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `student-performance-eda.ipynb` and **Run All Cells** ▶️

---

## 📂 Project Structure

```
Student-EDA-Matplotlib/
│
├── student-performance-eda.ipynb             # Main Jupyter Notebook
├── StudentsPerformance.csv                   # Dataset file
├── histogram_chart.png                       # Saved histogram chart
├── bar_chart.png                             # Saved bar chart
└── README.md
```

---

## 💡 Learning Outcomes

- Loading and exploring real CSV datasets with Pandas
- Performing filtering on multiple conditions
- GroupBy analysis to find category-wise patterns
- Creating and saving Matplotlib visualizations
- Writing clean, well-documented Jupyter Notebooks

---

## 🔮 Future Improvements

- [ ] Add Pie Chart for Gender Distribution
- [ ] Add Scatter Plot — Math vs Reading Score
- [ ] Add Box Plot for Score Distribution
- [ ] Add Parental Education vs Score Bar Chart
- [ ] Add Test Preparation Impact Analysis Chart
- [ ] Use Seaborn for advanced visualizations

---

## 👨‍💻 Author

**Priyanshu Patel**
- 🔗 [LinkedIn](https://www.linkedin.com/in/priyanshupatel-tech/)
- 💻 [GitHub](https://github.com/priyanshupatel-tech)

---

<p align="center">
  <i>⭐ If you found this project helpful, give it a star! It motivates me to build more! ⭐</i>
</p>
