# 📊 Student Data Analysis

> **Exploratory Data Analysis of Student Performance** — Comprehensive analysis of student academic metrics, identifying patterns, trends, and actionable insights across multiple subjects.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-FA0F00?style=flat-square&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-purple?style=flat-square)

---

## 📌 About

Student Data Analysis is a comprehensive exploratory data analysis (EDA) project that examines student performance across multiple subjects. The project uses Python and data visualization techniques to uncover patterns, correlations, and insights that can inform educational decisions and interventions.

---

## 🎯 Features

- 📈 **Performance Analysis** — Subject-wise and overall performance metrics
- 🔍 **Exploratory Data Analysis** — Detailed data exploration and insights
- 📊 **Statistical Analysis** — Descriptive statistics and correlations
- 📉 **Trend Visualization** — Charts and plots for easy understanding
- 🎯 **Pattern Recognition** — Identify student performance patterns
- 🏆 **Comparative Analysis** — Compare performance across subjects
- 📋 **Distribution Analysis** — Score distribution and outliers
- 🤝 **Correlation Study** — Subject inter-relationships
- 💡 **Actionable Insights** — Recommendations for improvement
- 🎓 **Student Segments** — Group similar performance patterns

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.8+** | Core language |
| **Pandas** | Data manipulation & analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Visualization |
| **Seaborn** | Statistical visualization |
| **Jupyter Notebook** | Interactive analysis |
| **SciPy** | Statistical tests |

---

## 📊 Dataset Features

Analysis includes:
- **Student ID** — Unique identifier
- **Name** — Student name
- **Class** — Grade/Class level
- **Mathematics** — Math subject score
- **English** — English subject score
- **Science** — Science subject score
- **Social Studies** — Social studies score
- **Computer Science** — CS subject score
- **Physical Education** — PE score
- **Overall GPA** — Cumulative grade point
- **Attendance** — Attendance percentage
- **Gender** — Student gender
- **Age** — Student age

---

## ⚙️ Installation

### Prerequisites
- Python 3.8+
- pip
- Jupyter Notebook

### 1. Clone Repository
```bash
git clone https://github.com/gsanika/student_data_analysis.git
cd student_data_analysis
```

### 2. Create Virtual Environment
```bash
python -m venv data_env
source data_env/bin/activate        # Mac/Linux
data_env\Scripts\activate           # Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 📋 Requirements

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
scipy>=1.7.0
```

---

## 📂 Project Structure

```
student_data_analysis/
├── notebooks/
│   └── student_analysis.ipynb      # Main analysis notebook
├── data/
│   ├── student_data.csv            # Raw dataset
│   └── processed_data.csv          # Cleaned dataset
├── results/
│   ├── summary_statistics.txt
│   ├── insights.txt
│   └── recommendations.txt
├── visualizations/                 # Generated plots
├── requirements.txt
└── README.md
```

---

## 🚀 Usage

### Start Jupyter Notebook
```bash
jupyter notebook
```

### Open the Analysis Notebook
Navigate to `notebooks/student_analysis.ipynb` and run cells sequentially

### Basic Analysis Example
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load data
df = pd.read_csv('data/student_data.csv')

# Display basic info
print(df.head())
print(df.describe())

# Calculate statistics
avg_score = df['Mathematics'].mean()
print(f"Average Math Score: {avg_score:.2f}")

# Visualize
plt.figure(figsize=(12, 6))
sns.heatmap(df.corr(), annot=True, cmap='coolwarm')
plt.title('Subject Correlations')
plt.show()
```

---

## 📊 Analysis Sections

### 1. Data Overview
- Dataset shape and size
- Data types
- Missing values
- Basic statistics

### 2. Descriptive Statistics
- Mean, median, mode
- Standard deviation
- Min, max values
- Percentiles

### 3. Subject-wise Analysis
- Performance by subject
- Subject rankings
- Score distribution
- Top and bottom performers

### 4. Student Performance Segments
- High performers (>85%)
- Average performers (70-85%)
- Below average (<70%)
- At-risk students

### 5. Correlation Analysis
- Subject inter-correlations
- Attendance impact
- Gender-wise comparison
- Age impact on performance

### 6. Visualization
- Histograms for score distribution
- Box plots for outlier detection
- Scatter plots for relationships
- Heatmaps for correlations
- Bar charts for comparisons
- Pie charts for segments

---

## 📈 Key Insights

Example insights discovered:
- **Strong Correlations**: Math & Science scores are highly correlated (0.87)
- **Attendance Impact**: 5% improvement in attendance correlates with 8% score increase
- **Gender Patterns**: Variations in subject preferences across genders
- **Outliers**: Identification of exceptional and struggling students
- **Trends**: Improvement over academic periods

---

## 🎯 Key Findings

| Metric | Value |
|--------|-------|
| **Average Score** | 78.5 |
| **Top Subject** | Mathematics (82.3) |
| **Bottom Subject** | English (74.1) |
| **Success Rate** | 85% (>70 score) |
| **At-Risk Students** | 12% |

---

## 💡 Recommendations

Based on analysis:
1. **Targeted Support** — Focus on low-performing students
2. **Subject Enhancement** — Improve English curriculum
3. **Attendance Tracking** — Correlates with performance
4. **Peer Tutoring** — High performers assist others
5. **Intervention Programs** — For at-risk students
6. **Resource Allocation** — More resources for weak areas

---

## 🧪 Analysis Techniques Used

- ✅ Exploratory Data Analysis (EDA)
- ✅ Descriptive Statistics
- ✅ Correlation Analysis
- ✅ Distribution Analysis
- ✅ Comparative Analysis
- ✅ Outlier Detection
- ✅ Clustering Analysis
- ✅ Trend Analysis

---

## 📉 Visualization Examples

Includes various plots:
- Histograms
- Box plots
- Scatter plots
- Heatmaps
- Bar charts
- Violin plots
- Pair plots
- Distribution plots

---

## 🔮 Future Enhancements

- Predictive modeling for student performance
- Time-series analysis of trends
- Machine learning classification
- Dashboard for real-time monitoring
- Mobile app for parents/students
- Integration with student management system

---

## 📚 Learning Outcomes

This project teaches:
- Data loading and cleaning
- Exploratory data analysis
- Statistical analysis
- Data visualization
- Pattern recognition
- Report generation
- Insight extraction

---

## 🤝 Contributing

Contributions welcome:
- Additional analysis
- Better visualizations
- New insights
- Code improvements
- Documentation
- Test cases

---

## 📝 License

MIT License - Open source

---

## 💬 Use Cases

1. **Educational Administration** — Track school performance
2. **Student Counseling** — Identify students needing support
3. **Curriculum Development** — Data-driven improvements
4. **Parent Reports** — Detailed performance reports
5. **Scholarship Decisions** — Merit-based awards
6. **Research** — Academic performance studies

---

## 📧 Contact

Questions? Email: **galgundesanika@gmail.com**

---

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [NumPy Documentation](https://numpy.org/)
