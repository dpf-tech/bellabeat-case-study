# Analyzing Consumer Fitness Behavior Using Bellabeat Data

This project explores consumer fitness patterns using publicly available Fitbit activity, calories, and sleep data.  
The goal is to understand daily behavior trends and provide insights that could support Bellabeat’s wellness-product strategy.

The analysis was performed in Python using a structured workflow that includes data cleaning, exploratory analysis, visualization, and interpretation.  
All final outputs—including the written report, executive summary, and charts—are included in this repository.

---

## Project Overview

This case study analyzes real consumer fitness data to answer three core questions:

1. What does the distribution of daily steps reveal about overall activity levels?
2. How strongly are daily steps associated with calories burned?
3. Is there any meaningful relationship between daily steps and sleep duration?

Using Python and pandas, the dataset was cleaned, merged, and transformed.  
Visualizations were produced to reveal patterns that can guide Bellabeat’s product and marketing decisions.

---

## Repository Contents

| File | Description |
|------|-------------|
| [Bellabeat_Final_Report.pdf](docs/Bellabeat_Report_Capstone_Project.pdf) | Full case study report with all findings and visualizations |
| [Executive Summary (PDF)](docs/bellabeat_executive_summary.pdf) | One-page summary of insights and recommendations |
| [Jupyter Notebook](docs/bellabeat_analysis.ipynb) | Complete Python workflow used for analysis |
| `docs/images/` | Folder containing all visualization files |

---

## Key Visualizations

Below are the main charts created during the analysis.  
Each thumbnail links to the full-resolution image stored in the repository.

<div align="center">

<a href="docs/images/bellabeat_steps_hist.png">
  <img src="docs/images/bellabeat_steps_hist.png" width="260"><br>
  <strong>Daily Steps Distribution</strong>
</a>

<br><br>

<a href="docs/images/bellabeat_steps_vs_calories.png">
  <img src="docs/images/bellabeat_steps_vs_calories.png" width="260"><br>
  <strong>Calories vs Total Daily Steps</strong>
</a>

<br><br>

<a href="docs/images/bellabeat_steps_vs_sleep.png">
  <img src="docs/images/bellabeat_steps_vs_sleep.png" width="260"><br>
  <strong>Daily Steps vs Minutes Asleep</strong>
</a>

</div>

---

## How to Run the Analysis

If you'd like to run or modify the code yourself:

1. Clone the repository:
   ```bash
   git clone https://github.com/dpf-tech/bellabeat-case-study.git


Analyzing Consumer Fitness Behavior Using Bellabeat Data

A Python-based case study exploring how daily steps, calorie expenditure, and sleep duration relate to consumer fitness behavior. This project uses public Fitbit data and replicates a real-world analytics workflow: cleaning, merging datasets, generating visual insights, and producing a polished final report.

📌 Project Overview

Bellabeat is a wellness technology company that designs smart devices for women.
This case study analyzes user activity patterns to help understand:

Typical daily movement levels

How steps influence calorie burn

Whether activity levels relate to sleep duration

The goal is to extract meaningful behavioral insights that can inform product positioning and user-engagement strategies.

📂 Included in This Repository

### • Full Report  
- [Final Report (PDF)](docs/Bellabeat_Report_Capstone_Project.pdf)**
Complete case study with all charts and written analysis.

### • Executive Summary  
**[bellabeat_executive_summary.pdf](https://github.com/dpf-tech/bellabeat-case-study/blob/main/bellabeat_executive_summary.pdf)**  
A one-page summary highlighting key insights and recommendations.

### • Jupyter Notebook  
**[bellabeat_analysis.ipynb](https://github.com/dpf-tech/bellabeat-case-study/blob/main/bellabeat_analysis.ipynb)**  
Notebook containing the Python code used for data processing and visualization.



🧠 Research Questions

What does the distribution of daily steps reveal about overall activity levels?

How strongly are daily steps associated with calories burned?

Is there a noticeable relationship between daily steps and sleep duration?

🛠️ Methodology (Python Workflow)

Imported and cleaned datasets: daily activity, daily steps, and sleep logs.

Standardized date formats and merged datasets on Id + Date.

Addressed missing values and ensured dataset consistency.

Generated visualizations using matplotlib and seaborn.

Interpreted results and consolidated insights for Bellabeat’s context.

📊 Key Visualizations

All generated charts are stored in:  
**[`/images/`](images/)**  
Direct image links:
- [Daily Steps Distribution](https://raw.githubusercontent.com/dpf-tech/bellabeat-case-study/main/images/bellabeat_steps_hist.png)
  Shows how frequently users hit low, moderate, and high step counts.
- [Calories vs Total Daily Steps](images/bellabeat_steps_vs_calories.png)
  Reveals a clear positive relationship between movement and energy expenditure.
- [Daily Steps vs Minutes Asleep](images/bellabeat_steps_vs_sleep.png)
  Explores whether more active days lead to longer sleep.(The correlation is weak.)


📝 Insights & Interpretation
Activity Patterns

Most users average 6,000–9,000 steps/day, below recommended levels.

A smaller group regularly exceeds 15,000 steps/day, showing high activity.

~15–20% record very low steps (<2,000), suggesting sedentary behavior or inconsistent device use.

Calories & Activity

Strong positive correlation between daily steps and calories burned.

Higher-activity users consistently burn more calories.

Sleep Behavior

No clear linear relationship between steps and sleep duration.

Most users sleep 5.5–7.5 hours, slightly below ideal ranges.

🎯 Recommendations

Encourage step-based challenges to promote daily movement.

Highlight calorie-burn tracking in Bellabeat's marketing materials.

Treat sleep metrics as a complementary feature rather than activity-dependent.

Help users focus on long-term habit trends, not short-term fluctuations.

▶️ How to Run the Analysis Notebook Locally

### **Requirements**
Make sure the following are installed:

- Python 3.10+
- pip (Python package manager)
- Jupyter Notebook or JupyterLab

### **1. Install dependencies**
pip install pandas matplotlib jupyter

### **2.Launch Jupyter Notebook**
 jupyter notebook

### **3.Then open**
bellabeat_analysis.ipynb

Open bellabeat_analysis.ipynb and run cells sequentially.


