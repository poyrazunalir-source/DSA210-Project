# DSA210-Project  
Data science project for DSA210: Digital habits & productivity

## Impact of iPhone Notifications on Focus, Mood & Productivity

### Motivation
Smartphones constantly send notifications and these interruptions may negatively affect attention span, productivity, and emotional well-being. I want to analyze how my daily iPhone notifications relate to my productivity and mood. The goal is to understand my digital habits and see if notification frequency truly affects how I feel and work throughout the day.

---

## Data Source
All data is collected manually from my personal iPhone (iOS 18.5).

| Data | Source |
|------|--------|
| Daily notification count | Settings → Screen Time → See All Activity → Notifications |
| Daily pickups | Settings → Screen Time |
| Productivity score (1–10) | Self-logged |
| Mood score (1–5) | Self-logged |
| Notes (optional) | Daily notes for context |

---

## Data Collection Plan
I will collect data for **at least 14 days**, and continue gathering more data until the final project submission to increase statistical strength.

Each night I record:
- Total number of notifications  
- Phone pickups  
- Productivity score (1–10)  
- Mood score (1–5)  
- Optional notes  

Data is stored in a CSV file (`data.csv`) for analysis.

---

## Research Questions & Hypotheses

### 1. Notifications → Productivity
- **H₀:** Notifications do not affect productivity.  
- **H₁:** Higher notification counts are associated with lower productivity.

### 2. Notifications → Mood
- **H₀:** Notifications do not affect mood.  
- **H₁:** More notifications are associated with worse mood.

### 3. Pickups → Productivity (additional feature)
- **H₀:** Phone pickups do not affect productivity.  
- **H₁:** More pickups are associated with lower productivity.

These hypotheses will be tested using correlation analysis and simple regression methods.

---

## Planned Exploratory Data Analysis (EDA)

### Summary statistics
- Mean, median, min/max, standard deviation  
- Distributions of notifications, mood, productivity, and pickups  

### Visualizations
- Daily notifications line chart  
- Productivity & mood over time  
- Scatter plots:
  - Notifications vs Productivity  
  - Notifications vs Mood  
  - Pickups vs Productivity  
- Correlation heatmap (notifications, pickups, productivity, mood)

These help understand patterns and relationships before applying statistical tests.

---

## Hypothesis Testing Plan

### 1. Pearson Correlation
For approximately continuous variables (notifications, pickups, productivity).

### 2. Spearman Rank Correlation
For ordinal or non-normal variables (mood, productivity).

### 3. Simple Linear Regression

**Model:**
productivity = beta_0 + beta_1 * notifications + error

**Evaluation:**
- Regression slope (direction of effect)  
- R² value (explained variance)  
- p-value (significance)  

---

## Tools
- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scipy  
- scikit-learn  
- Jupyter Notebook  

All analysis is done in `analysis.ipynb`.

---

## Goal
Determine whether higher notification frequency and phone usage patterns are associated with lower productivity and worse mood, and gain insight into my personal digital behavior.

---

## Future Work
- Analyze notification categories (e.g., social, messaging, productivity)  
- Compare Focus Mode days vs normal days  
- Include screen time as an additional feature  
- Try more advanced models (e.g., multiple regression)  

---

## AI Assistance Disclosure
AI (ChatGPT) was used to help format this README and prepare the analysis structure.  
All data collection and final analysis will be done by me.


