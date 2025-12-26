# SQL-Students-Mental-Health
This project analyses the risk of mental health difficulties among students at a Japanese international university, with a focus on identifying predictors of depression.

## Key Questions
1. How does the length of stay relate to depression risk among international students?
2. What is the relationship between social connectedness, acculturative stress, and depression?

---

## Dataset Overview
The dataset contains anonymised student survey responses collected in 2018 and includes demographic, academic, and psychological indicators.

### Key Fields

| Field | Description |
|------|------------|
| inter_dom | Student type (international or domestic) |
| region | Region of origin |
| gender | Gender |
| academic | Academic level (undergraduate/graduate) |
| age | Age |
| stay | Length of stay (years) |
| stay_cate | Length of stay category |
| todep | Depression score (PHQ-9) |
| tosc | Social connectedness score |
| toas | Acculturative stress score |

---

## Analytical Approach
All analysis was conducted using **PostgreSQL**

Key steps include:
- Filtering and segmentation
- Grouped aggregation and comparison
- Calculation of average mental health indicators across relevant groups
- Sorting results in order

---

## Key Insights

- Higher acculturative stress is consistently associated with higher depression scores.
- Stronger social connectedness is associated with lower depression scores.
- Length of stay shows differences in mental health outcomes.
