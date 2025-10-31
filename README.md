# DSA210-Project
Data science project for DSA210: Digital habits &amp; productivity
# Impact of iPhone Notifications on Focus & Mood

## Motivation
Smartphones send frequent notifications which may reduce attention span and impact emotional well-being. I want to analyze how my daily iPhone notifications affect my productivity and mood. The goal is to understand digital habits and identify whether notification frequency has a measurable effect on my focus.

## Data Source
All data will be collected manually from my personal device (iPhone running iOS 18.5).

| Data | Source |
|---|---|
Daily notification count | Settings → Screen Time → See All Activity → Notifications |
Daily pickups (optional) | Settings → Screen Time |
Productivity score (1–10) | Self-logged |
Mood score (1–5) | Self-logged |
Notes (optional) | Short context notes per day |

## Data Collection Plan
I will collect data for approximately 14 days. Each night I will record:

- Total number of notifications from iOS Screen Time
- Productivity score (1–10)
- Mood score (1–5)
- (Optional) Daily phone pickups

Data will be stored in a spreadsheet and exported to CSV for analysis.

## Planned Analysis
- Exploratory Data Analysis (EDA)
- Summary statistics
- Time-series visualization
- Correlation analysis between:
  - Notifications and productivity
  - Notifications and mood
- Hypothesis testing
- (Optional) Linear regression model to predict productivity based on notification count

## Tools
- Python
  - pandas
  - numpy
  - matplotlib / seaborn
- Jupyter Notebook
- Google Sheets / CSV

## Goal
Determine whether higher iPhone notification frequency is associated with lower productivity and worse mood, and gain insight into personal digital behavior patterns.

## Future Work
- Include phone pickup frequency as an additional variable
- Analyze notification categories (social vs productivity apps)
- Test digital well-being interventions such as Focus Mode days

## Notes
This submission is the project proposal. Data collection will begin after the proposal deadline, following the course timeline.

## AI Assistance Disclosure

I used AI (ChatGPT) only to help format the README in Markdown and understand how the preview design works. No other parts of the project have been assisted by AI at this stage.


