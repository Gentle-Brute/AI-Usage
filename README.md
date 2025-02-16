# Predicting Career Interest in AI among College Students

## Introduction
This project aims to analyze survey data collected from college students to predict their likelihood of pursuing a career in Artificial Intelligence (AI). The dataset was obtained from a survey conducted on-campus, focusing on students' educational background, AI knowledge, and career aspirations related to AI.

## Dataset
The dataset (`AI On-Campus Research Survey (Responses).xlsx`) includes various attributes collected from students. After preprocessing, the dataset was cleaned to remove unnecessary columns (such as timestamps) and prepared for analysis.

## Methodology
### Statistical Analysis
1. **Linear Regression Model (OLS)**:
   - Used to analyze the relationship between variables like educational background, AI knowledge, and career aspirations (`College_AI ~ Stream + AI_Knowledge + Career_AI`).
   - ANOVA (Analysis of Variance) was employed to assess the significance of these variables in predicting interest in AI careers.

2. **Tukey's Honest Significant Difference (HSD)**:
   - Conducted post-hoc tests using Tukey's HSD to identify significant differences between groups based on educational stream, AI knowledge level, and career aspirations.
   - Tested hypotheses to determine which combinations significantly affect students' likelihood of pursuing an AI career.

### Statistical Tests
- **T-tests**:
  - Utilized to compare means between groups identified by Tukey's HSD, focusing on identifying groups where career interest in AI is significantly higher.

## Results
The analysis identified specific combinations of educational stream, AI knowledge level, and career aspirations that strongly correlate with a higher interest in pursuing AI careers among college students. The findings provide insights into factors influencing career choices in AI and can assist educational institutions in tailoring programs to meet student interests.

## Conclusion
This project demonstrates the application of statistical methods to predict career interests based on survey data from college students. By understanding the variables influencing career decisions related to AI, institutions can better prepare and support students in pursuing careers in emerging fields like Artificial Intelligence.
