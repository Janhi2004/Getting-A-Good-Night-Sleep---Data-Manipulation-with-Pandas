# Getting-A-Good-Night-Sleep---Data-Manipulation-with-Pandas

## Business Problem
SleepInc, through their SleepScope app, aims to understand how various lifestyle factors affect sleep quality and duration. By analyzing the data collected from the app users, I seek to uncover insights that can help improve sleep health and overall well-being. This project focuses on analyzing relationships between exercise, gender, occupation, and sleep quality to provide actionable recommendations.

## Research Questions
1. Which occupation has the lowest average sleep duration?
2. Which occupation has the lowest average sleep quality?
3. Are there any commonalities between the occupations with the lowest sleep duration and quality?
4. How does BMI category affect the rates of insomnia?

## Hypotheses
1. Occupations with higher stress levels have lower average sleep duration.
2. Occupations requiring physical labor have better sleep quality.
3. Higher BMI categories are associated with higher rates of insomnia.

## Analysis and Findings
### Occupation with the Lowest Average Sleep Duration
I identified the occupation with the lowest average sleep duration and stored it in a variable called `lowest_sleep_occ`.

### Occupation with the Lowest Average Sleep Quality
I determined the occupation with the lowest average sleep quality and stored it in a variable called `lowest_sleep_quality_occ`.

### Comparing Sleep Duration and Sleep Quality
I checked if the occupation with the lowest sleep duration also had the lowest sleep quality, resulting in a boolean variable `same_occ`.

### BMI Category and Insomnia Rates
I explored how BMI category affects insomnia rates by calculating the ratio of app users in each BMI category diagnosed with insomnia. The results are stored in a dictionary called `bmi_insomnia_ratios`.

### Key Findings
- **Occupation with the Lowest Average Sleep Duration:** 
  - `lowest_sleep_occ`: Sales Representative
- **Occupation with the Lowest Average Sleep Quality:** 
  - `lowest_sleep_quality_occ`: Sales Representative
- **Same Occupation for Lowest Sleep Duration and Sleep Quality:** 
  - `same_occ`: True
- **BMI Category Insomnia Ratios:**
  - `bmi_insomnia_ratios`: 
    ```python
    {
      "Normal weight": 0.04,
      "Overweight": 0.43,
      "Obese": 0.4
    }
    ```

## Suggestions
1. **Targeted Interventions for High-Risk Occupations:** Develop wellness programs and sleep improvement plans for occupations identified with the lowest sleep duration and quality.
2. **Stress Management Programs:** Implement stress management workshops for occupations with high stress levels to improve sleep duration and quality.
3. **Health and Fitness Campaigns:** Promote healthy lifestyle choices to manage BMI and reduce the prevalence of insomnia among users.
4. **Personalized Recommendations:** Use the findings to offer personalized sleep improvement tips based on occupation and BMI category through the SleepScope app.
