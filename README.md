# 💄 Consumer Behavior Analysis for Cosmetic Products

## Overview

This project explores consumer behavior toward cosmetic products using survey data collected through **Google Forms**.

The objective was to identify purchasing habits, consumer preferences, and market segments through statistical learning and exploratory data analysis.

The project was carried out as part of the Statistics and Data Analysis curriculum at the Higher School of Statistics and Information Analysis (ESSAI).

---

## Objectives

- Design and distribute a consumer survey
- Collect and clean questionnaire data
- Analyze demographic characteristics
- Understand purchasing behavior
- Identify the main factors influencing cosmetic purchases
- Segment consumers into meaningful groups

---

## Dataset

The dataset was collected through a custom-designed **Google Forms questionnaire** covering topics such as:

- Age
- Gender
- Professional status
- Cosmetic usage habits
- Purchase criteria
- Brand loyalty
- Environmental awareness
- Price sensitivity
- Shopping preferences

---

## Methodology

The analysis was conducted using several statistical learning techniques.

### 1. Descriptive Statistics

- Age distribution
- Gender distribution
- Professional status
- Frequency analysis

---

### 2. Principal Component Analysis (PCA)

Two PCA analyses were performed to:

- Reduce dimensionality
- Identify latent behavioral dimensions
- Visualize relationships between respondents
- Interpret purchasing behaviors

Main dimensions identified:

- Consumer engagement
- Eco-friendly awareness
- Price sensitivity
- Brand influence
- Social influence

---

### 3. Multiple Correspondence Analysis (MCA)

Applied to categorical variables in order to:

- Explore relationships between qualitative variables
- Understand purchasing attitudes
- Identify associations among consumer profiles

---

### 4. Consumer Segmentation

Two clustering approaches were used:

- Hierarchical Clustering (HCPC)
- K-Means Clustering

The analysis revealed several consumer profiles, including:

- Traditional consumers
- Eco-conscious consumers
- Selective buyers
- Highly engaged cosmetic users

---

## Technologies

- R
- FactoMineR
- factoextra
- ggplot2
- Google Forms
- LaTeX

---

## Skills Demonstrated

- Survey Design
- Data Collection
- Exploratory Data Analysis
- Principal Component Analysis (PCA)
- Multiple Correspondence Analysis (MCA)
- Hierarchical Clustering (HCPC)
- K-Means Clustering
- Consumer Segmentation
- Data Visualization
- Statistical Learning

---

## Key Findings

- Young adults represented the majority of respondents.
- Purchasing decisions were influenced by price, brand reputation, environmental concerns, and social influence.
- Distinct consumer segments were identified using clustering techniques.
- Dimensionality reduction helped reveal hidden behavioral patterns.

---

## Repository Structure

```
.
├── report/
│   └── Consumer_Behavior_Analysis.pdf
│
├── questionnaire/
│   └── GoogleFormsQuestions.pdf
│
├── dataset/
│   └── cosmetics_survey.csv
│
├── figures/
│   ├── pca1.png
│   ├── pca2.png
│   ├── mca.png
│   ├── hcpc.png
│   └── kmeans.png
│
└── README.md
```

---

## Note

The original analysis code was developed in **R** during the project but is no longer available.

This repository preserves the project report, methodology, visualizations, and findings for documentation and portfolio purposes.

---

## Future Improvements

- Reimplement the project in Python using Scikit-learn
- Build an interactive dashboard
- Train predictive machine learning models on future datasets

---

## Author

- Hiba Zormati
