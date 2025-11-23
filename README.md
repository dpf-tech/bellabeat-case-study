Analyzing Consumer Fitness Behavior Using Bellabeat Data

This project explores activity, calorie expenditure, and sleep patterns using publicly available Fitbit data. The analysis was completed in Python and follows a typical data-analytics workflow: cleaning the data, merging datasets, generating visualizations, and summarizing insights in a final report.

Project Overview

Bellabeat is a wellness technology company focused on helping women better understand their daily habits through smart devices.
The purpose of this case study is to examine user behavior and identify patterns that could support product and marketing decisions.

The analysis focuses on three key questions:

What does the distribution of daily steps reveal about general activity levels?

How strongly do daily steps relate to calorie burn?

Is there any meaningful relationship between daily steps and sleep duration?

Repository Contents
File	Description
Bellabeat_Final_Report.pdf	Full formatted case-study report, including charts
bellabeat_executive_summary.pdf	One-page summary of the key findings
bellabeat_analysis.ipynb	Jupyter notebook containing all data processing and visualizations
images/	Folder with all generated charts
Methodology

Loaded and cleaned the datasets: daily activity, daily steps, and sleep logs.

Standardized date formats and merged the tables by participant ID and date.

Removed or corrected missing and inconsistent entries.

Explored the data visually through histograms and scatter plots.

Summarized findings and interpreted them in the context of Bellabeat users.

Visualizations
Distribution of Daily Steps

Shows typical activity ranges and highlights inactive vs. active groups.

Calories vs. Total Daily Steps

Illustrates the positive relationship between movement and calorie expenditure.

Daily Steps vs. Minutes Asleep

Explores whether more active days correspond to longer sleep duration.

Key Findings
Activity Levels

Most users fall between 6,000 and 9,000 steps per day.
A smaller segment regularly exceeds 15,000 steps, indicating higher activity.
Between 15–20% log fewer than 2,000 steps, suggesting low engagement or sedentary behavior.

Calories

There is a clear positive correlation between daily steps and calories burned.
More active days consistently show higher calorie expenditure.

Sleep

Daily steps and sleep duration do not show a meaningful correlation.
Most users sleep between 5.5 and 7.5 hours per night.

Recommendations

Introduce step-based challenges to help users increase daily movement.

Highlight calorie-burn insights in Bellabeat’s product messaging.

Present sleep tracking as a complementary wellness feature.

Encourage users to review long-term trends instead of single-day metrics.

Running the Notebook

To run the analysis locally:

pip install pandas numpy matplotlib seaborn
jupyter notebook


Open the notebook bellabeat_analysis.ipynb and execute the cells in order.

Notes

This project demonstrates practical data-analysis skills such as cleaning, merging, visualization, and communicating findings in a structured report. It serves as a comprehensive portfolio example for junior data analyst roles.
