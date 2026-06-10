# Clustering of Countries for Strategic Aid Allocation

## Problem Statement
GIVE Foundation, an international humanitarian NGO, raised $10 million and needed a data-driven approach to identify countries requiring urgent financial aid. This project uses Machine Learning clustering techniques to group countries based on socio-economic and health indicators and prioritize countries most in need of assistance.

## Objectives
- Perform Exploratory Data Analysis (EDA) on country-level socio-economic data.
- Conduct outlier detection and analysis.
- Apply feature scaling and standardization.
- Implement K-Means Clustering.
- Implement Hierarchical Clustering (Single & Complete Linkage).
- Compare clustering approaches and select the most effective model.
- Identify underdeveloped countries requiring immediate humanitarian aid.
- Generate actionable recommendations for NGO fund allocation.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Project Workflow
1. Data Inspection & Cleaning
2. Exploratory Data Analysis
3. Outlier Analysis
4. Data Standardization
5. K-Means Clustering
5. Hierarchical Clustering
6. Cluster Evaluation
7. Country Prioritization
8. Business Recommendations

## Key Findings
- Optimal number of clusters identified using the Elbow Method: K = 3
- Countries were categorized into:
  - Developed Countries
  - Developing Countries
  - Underdeveloped Countries
- K-Means provided more interpretable cluster separation compared to Hierarchical Clustering.
- Low GDP, low income, and high child mortality were strong indicators of countries requiring aid.

## Countries Identified for Priority Aid
- Haiti
- Sierra Leone
- Chad
- Central African Republic
- Mali

## Business Impact

The analysis enabled strategic allocation of humanitarian funds by identifying countries facing severe socio-economic challenges, helping maximize the impact of the NGO's $10 million aid program.
