# Student Performance Analysis

A data analysis project examining the factors that influence student academic performance and placement outcomes, using Python and Power BI.

---

## Project Structure

```
student-analysis/
├── data/
│   └── student_dataset.csv     # Dataset (10,000 students, 8 columns)
├── notebooks/
│   └── student_analysis.ipynb  # EDA & analysis notebook
├── dashboard/
│   └── StudentAnalysis.pbix    # Power BI dashboard
└── README.md
```

## Dataset

The dataset contains **10,000 student records** with the following features:

| Column | Description |
|---|---|
| `study_hours` | Number of hours spent studying per day |
| `attendance` | Attendance percentage |
| `sleep_hours` | Average hours of sleep per day |
| `internet_usage` | Hours of internet usage per day |
| `assignments_completed` | Number of assignments completed |
| `previous_score` | Score from the previous exam |
| `exam_score` | Final exam score (target variable) |
| `placement_status` | Whether the student was `Placed` or `Not Placed` |

## Key Questions Explored

- Which factors most strongly correlate with exam scores?
- Does study time and attendance improve placement chances?
- How does sleep and internet usage affect academic performance?
- What distinguishes placed vs. non-placed students?

## Analysis & Visualizations

The Power BI dashboard (`StudentAnalysis.pbix`) includes:

- Exam score distribution across students
- Placement rate breakdown
- Correlation between study hours, attendance, and scores
- Impact of sleep and internet usage on performance

## Tools Used

- **Python** (pandas) — data exploration and preprocessing
- **Jupyter Notebook** — analysis and visualization(google colab)
- **Power BI** — interactive dashboard


## Dataset Source

> Kaggle
