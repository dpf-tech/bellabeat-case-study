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
**[Bellabeat_Final_Report.pdf](https://github.com/dpf-tech/bellabeat-case-study/blob/main/Bellabeat_Final_Report.pdf)**
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
- [Daily Steps Distribution](images/bellabeat_steps_hist.png)
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


