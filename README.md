# vanguard_project# Vanguard Digital Experiment Analysis

## Project Overview

This project analyzes Vanguard's digital A/B experiment to evaluate whether a redesigned onboarding interface improved customer completion rates, reduced errors, and enhanced the overall user experience.

The analysis combines customer demographics, experiment assignments, and web interaction data to understand user behavior throughout the digital journey and provide business recommendations based on data-driven insights.

---

## Business Problem

Vanguard introduced a new digital onboarding interface and wanted to determine whether the redesign provided a meaningful improvement over the existing experience.

The key question addressed in this project is:

> **Did the new digital interface improve completion rates and user experience enough to justify a full rollout?**

---

## Objectives

* Analyze customer demographics and behavior.
* Compare the performance of the Control and Test groups.
* Measure completion rates, error rates, and time spent at each process step.
* Identify bottlenecks in the customer journey.
* Perform statistical hypothesis testing to validate the results.
* Provide actionable business recommendations.

---

## Datasets Used

The project combines three datasets:

### 1. Client Data

Contains customer demographic information, including:

* Age
* Gender
* Account balance
* Number of accounts
* Client tenure

### 2. Experiment Data

Contains:

* Client IDs
* Assignment to Control or Test groups

### 3. Web Data

Tracks user interactions throughout the onboarding process, including:

* Process steps
* Timestamps
* Visit information

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Tableau
* Jupyter Notebook
* Git & GitHub

---

## Project Workflow

### Data Cleaning and Preparation

* Merged datasets using client identifiers
* Removed duplicates and missing values
* Converted timestamps into datetime format
* Created additional metrics for analysis

### Exploratory Data Analysis (EDA)

* Customer age distribution
* Gender analysis
* Client tenure analysis
* Account balance patterns

### Funnel Analysis

Measured customer retention across the onboarding journey:

* Start
* Step 1
* Step 2
* Step 3
* Confirm

### Time-on-Step Analysis

Calculated:

* Average time spent per step
* Bottlenecks in the process
* Differences between Control and Test groups

### KPI Analysis

Compared:

* Completion Rate
* Error Rate
* Average Time per Step

### Hypothesis Testing

Performed statistical tests to determine whether improvements observed in the Test group were statistically significant.

---

## Key Findings

### Completion Rate

* Control Group: 62.2%
* Test Group: 65.9%
* Improvement: +3.7%

### Error Rate

* Control Group: 7.8%
* Test Group: 6.4%
* Improvement: -1.4%

### Average Time per Step

* Control Group: 2.3 minutes
* Test Group: 2.0 minutes
* Improvement: -0.3 minutes

### Funnel Insights

* The Test group retained more customers at every stage.
* The largest drop-off occurred between Start and Step 1.
* Step 3 was identified as the primary bottleneck for both groups.

---

## Business Recommendations

1. Improve Step 3 to reduce customer friction.
2. Conduct a follow-up experiment with a larger sample size.
3. Segment customers by age and tenure for targeted improvements.
4. Delay a full rollout until stronger business gains are achieved.

---

## Tableau Dashboard

An interactive Tableau dashboard was developed to visualize:

* Customer demographics
* Funnel performance
* Completion rates
* Time-on-step analysis
* KPI comparisons

The dashboard helps stakeholders quickly understand the experiment outcomes and business implications.

---

## Conclusion

The redesigned interface demonstrated statistically significant improvements in completion rates, error reduction, and overall efficiency. However, the practical business impact remains relatively modest. Further optimization and additional experimentation are recommended before implementing a full-scale rollout.

---
## Project Management

The project was planned, organized, and tracked using Trello to manage tasks, timelines, responsibilities, and project progress throughout the analysis.

**Trello Board:**
[Vanguard A/B Test Project Board](https://trello.com/b/W1HJvsvx/vanguard-a-b-test-project?utm_source=chatgpt.com)

The board includes:

* Project planning and milestones
* Task assignments for team members
* Data cleaning and EDA activities
* Hypothesis testing tasks
* Tableau dashboard development
* Presentation preparation and final recommendations


## Team Members

**Durgadevi Nagarajan (DD)**

**Saurabh**

---

## Repository Structure

```text
Vanguard-Digital-Experiment/
│
├── data/
├── notebooks/
├── visuals/
├── tableau/
├── presentation/
├── README.md
└── requirements.txt
```
