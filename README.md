# Health360: Comprehensive Healthcare Risk & Disease Analysis

## 1. Project Overview & Problem Statement
Healthcare providers face challenges in identifying high-risk patients early for chronic conditions—specifically **Heart Disease, Diabetes, and Stroke**—when relying on manual record reviews.

**Health360** is an interactive Tableau analytics solution analyzing 5,000 patient records across demographics, clinical indicators, lifestyle habits, and symptom patterns to support preventive care and risk assessment.

## 2. Live Interactive Demo
* **Tableau Public Dashboard & Story:** [PASTE_YOUR_TABLEAU_PUBLIC_LINK_HERE]

## 3. Scenarios Addressed
* **Scenario 1 — Dr. Michael Carter (Clinical Risk Assessment Officer):** Uses KPI cards and clinical risk charts (BMI, blood pressure, disease prevalence) to identify high-risk patients early.
* **Scenario 2 — Emily Rodriguez (Healthcare Data Analyst):** Explores lifestyle behaviors (smoking, alcohol consumption, exercise level) and their relationship with chronic illnesses using side-by-side comparisons and heatmaps.
* **Scenario 3 — Dr. Priya Nair (Public Health Researcher):** Examines population-wide distributions across age groups, BMI categories, and fatigue symptoms to guide public health initiatives.

## 4. Dataset Summary
* **File Included:** `smart_healthcare_dataset (1).csv` (5,000 patient records, 16 columns, 0 missing values, 0 duplicates).
* **Calculated Fields Created in Tableau:**
  * `Age Group`: Teenager (<=30), Young Adult (31–40), Adult (41–50), Middle Age (51–60), Senior (61–70), Old (>70)
  * `BMI Category`: Underweight (<18.5), Normal (18.5–24.9), Overweight (25.0–29.9), Obese (>=30.0)
  * `Exercise Level Category`: Sedentary (0), Moderate (1), Active (2)
  * `Total Patients`: `COUNT([Age])`

## 5. Key Visualizations & Findings (9 Unique Sheets)
1. **KPI Summary Banner:** 5,000 Total Patients | 1,746 Diabetes Cases (34.92%) | 1,499 Heart Disease Cases (29.98%) | 1,243 Stroke Cases (24.86%).
2. **Exercise Level Distribution (Donut Chart):** Moderate (33.54%), Active (33.52%), and Sedentary (32.94%).
3. **Average Blood Pressure Across Age Groups (Bar Chart):** Highest in the Old age group (135.67 mmHg) followed by Young Adults (134.67 mmHg) and Teenagers (134.50 mmHg), down to Adults (133.61 mmHg).
4. **Alcohol and Smoking Consumption Across Age Groups (Side-by-Side Bar Chart):** Compares lifestyle risk counts across all 6 age brackets.
5. **BMI Category vs. Heart Disease Rate (Bar Chart):** Heart disease prevalence rises sharply with BMI: Obese (39.98%), Overweight (32.91%), Normal (25.97%), and Underweight (20.54%).
6. **Heart Disease vs. Diabetes Prevalence by BMI (Side-by-Side Bar Chart):** Normal (660 Diabetes / 522 Heart Disease), Overweight (580 / 550), Obese (309 / 321), Underweight (197 / 106).
7. **Patient Distribution by Age Group (Pie Chart):** Teenager (20.38%), Senior (16.38%), Adult (16.26%), Middle Age (16.08%), Young Adult (15.86%), Old (15.04%).
8. **Heart Disease by BMI Category and Exercise Level (Heatmap):** Identifies the highest-risk segment as Obese + Sedentary (42.86% heart disease rate) vs. the lowest-risk segment, Underweight + Sedentary (18.79%).
9. **Age Group Distribution by Fatigue Condition (100% Stacked Bar Chart):** Compares fatigue symptom prevalence (0 vs. 1) across age cohorts.

## 6. Repository Files
* `Health360_arul_story.twbx` — Packaged Tableau Workbook containing all 9 worksheets, the interactive Dashboard, and the 9-point Story.
* `smart_healthcare_dataset (1).csv` — Source dataset.
