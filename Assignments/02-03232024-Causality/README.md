---

## <center> Customer Segmentation-Case Study-Causal Inference using EconML and Dowhy</center>

---
![Alt Text](https://github.com/ShreyaJaiswal1604/EconML_Customer_Segmentation_Case_Study/blob/main/images/OIG4.Tv5iK0NH_UBWGMErZXZj.jpeg)

---

## Overview

Welcome to the Dynamic Business Insights project! This repository explores the application of fundamental concepts such as causality, causation, and causal inference in the realm of statistical analysis, with a specific focus on a real-world case study: Customer Segmentation at an Online Media Company.

## Key Concepts

### 1. Causality, Causation, and Causal Inference

- **Causality:**
  - Understanding the relationship between cause and effect.
  - Fundamental for making predictions, guiding interventions, and optimizing strategies.

- **Causation:**
  - Direct influence of one variable on another.
  - Classic "counterfactual" definition.

- **Causal Inference:**
  - Pivotal in understanding cause-and-effect relationships.
  - Goes beyond correlation, drawing conclusions based on observational or experimental data.

### 2. Customer Segmentation

Explore the strategic marketing approach of dividing a broad target market into smaller, manageable customer groups:

- **Purpose:**
  - Create personalized and targeted marketing strategies.
  - Design approaches resonating better with specific customer groups.

- **Types of Segmentation:**
  - Demographic, Geographic, Psychographic, Behavioral.

- **Benefits:**
  - Improved Targeting.
  - Increased Customer Satisfaction.
  - Resource Optimization.

- **Examples:**
  - Online clothing retailer campaigns.
  - Food delivery service promotions.

- **Implementation:**
  - Utilizing data analysis tools, surveys, and machine learning for pattern identification.

### 3. Case Study: Customer Segmentation at an Online Media Company

Explore the application of causal inference techniques and data-driven strategies in a dynamic online media company scenario:

- **Objective:**
  - Estimate individualized responses for personalized pricing strategies.

- **Approach:**
  - *Causal Inference:* DoWhy library for constructing and validating causal models.
  - *Estimation:* EconML's DML-based estimators leveraging user features.
  - *Interpretation:* SingleTreeCateInterpreter for summaries on responsiveness to discounts.

## Getting Started

To dive into this project and explore the dynamic business insights, follow these steps:

## 1. Clone the repository:
   ```bash
   git clone git@github.com:ShreyaJaiswal1604/EconML_Customer_Segmentation_Case_Study.git
   ```

## 2. Navigate to the project directory:
```bash
cd EconML_Customer_Segmentation_Case_Study
```

## 3.Set up the environment:
```bash
conda create --name econml_env python=3.8
conda activate econml_env
pip install -r requirements.txt
```


## 4.Explore the Jupyter Notebooks:

1_Data_Preparation.ipynb: Preprocesses the raw data.
2_Causal_Inference_Modeling.ipynb: Constructs and validates causal models using DoWhy.
3_EconML_Modeling.ipynb: Estimates individualized responses using EconML's DML-based estimators.
4_Results_Interpretation.ipynb: Summarizes responsiveness to discounts using SingleTreeCateInterpreter.
Execute the notebooks sequentially for a comprehensive understanding of the project.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---



