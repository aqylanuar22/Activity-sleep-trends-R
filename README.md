# Activity-sleep-trends-R
Statistical analysis of physical activity and sleep patterns using R (hypothesis testing, t-tests, ANOVA, and visualisation).

# Exploring Activity and Sleep Trends Through Inferential Statistics in R

# Project Overview
This project investigates the relationship between daily step counts and sleep duration using fitness tracker data.  
Participants were classified into lifestyle groups (Sedentary, Moderately Active, Active) and analyzed using inferential statistics in R.

The study applied:
- One-sample Z-test
- Paired t-test
- Independent two-sample t-test
- One-way ANOVA

# Tools & Libraries
- R Programming  
- Packages: `dplyr`, `readr`, `lubridate`, `ggplot2`

# Methodology
1. Data Cleaning & Preparation – formatted dates, removed missing values, grouped participants.  
2. Lifestyle Classification 
   - Sedentary: < 5,000 steps/day  
   - Moderately Active: 5,000–9,999 steps/day  
   - Active: ≥ 10,000 steps/day  
3. Hypothesis Testing – conducted Z-test, t-tests, and ANOVA with visual validation (histograms, Q-Q plots, boxplots).  


# Key Results
- Active group significantly > 10,000 steps/day (p < 0.05).  
- No significant difference in step counts between weekdays & weekends.  
- No significant difference in sleep duration between Sedentary & Active groups.  
- ANOVA confirmed no lifestyle-based differences in sleep duration.  

Conclusion: Activity level predicts step counts but not sleep duration.
