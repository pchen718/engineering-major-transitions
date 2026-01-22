# Engineering Major Transitions in CEAS

## Overview
This project analyzes major-switching behavior within the College of Engineering and
Applied Science (CEAS) at the University of Colorado Boulder using longitudinal
student records from 2013–2025.

The goal is to identify common academic pathways, predictors of major switching,
and structural patterns that can inform enrollment planning and retention strategies.

## Data
- Institutional CEAS student records (≈21,000 students)
- Term-level enrollment histories (up to 12 terms per student)
- Academic performance metrics (term GPA, cumulative GPA)
- Major and college transitions over time

## Methods
- **Hierarchical logistic regression** to model the probability of major switching
- **Transition matrices** and cohort-based analyses
- **Interactive visualizations** including:
  - Alluvial (flow) plots
  - Network diagrams
  - Term-based bar charts
- Data cleaning and modeling in **R**
- Interactive app built using **Shiny**

## Key Findings
- Lower term GPA is associated with higher probabilities of major switching
- Switching behavior varies substantially by engineering discipline
- Many transitions occur early in students’ academic timelines
- Certain majors act as common entry or exit points within CEAS

## Output
- Statistical modeling for interpretability and inference
- Interactive visualization tools designed for non-technical administrators
- Results intended to support resource allocation and advising decisions

## Full Report
A complete technical report detailing methodology, models, and results is available here:
[Capstone Paper (PDF)](STAT_Capstone_Team_Tuna.pdf)
