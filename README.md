# 📊 Statistical Analysis: Work Location Impact on Isolation & Stress

![R](https://img.shields.io/badge/Language-R-blue) ![Analysis](https://img.shields.io/badge/Analysis-Statistical-green) ![University](https://img.shields.io/badge/Project-University-orange)

## 📝 Project Overview
This project analyzes a dataset of **3,500 professional employees** to investigate the critical relationships between **Work Location** (Remote, Hybrid, Office), **Social Isolation**, **Stress Levels**, and **Psychological Wellbeing**.

Using **R**, we applied rigorous statistical methods including descriptive statistics, regression modeling, probability theory (Bayes' Theorem), and sampling distributions to derive meaningful insights for HR and organizational psychology.

---

## 🎯 Key Objectives
* Determine if working remotely increases social isolation compared to office work.
* Analyze the probability of high stress among remote workers using **Bayes' Theorem**.
* Model the relationship between isolation scores and wellbeing using **Linear Regression**.
* Validate findings using **Inferential Statistics** (Z-scores & Sampling Distributions).

---

## 🔑 Key Findings

### 1. Isolation Analysis 🏠 vs 🏢
There is a clear trend indicating that remote work significantly increases feelings of social isolation.
* **Remote Workers:** Avg Isolation Score **6.83** (Highest).
* **Hybrid Workers:** Avg Isolation Score **4.17**.
* **Office Workers:** Avg Isolation Score **2.82** (Lowest).

### 2. Probability & Bayes' Theorem 🧮
We calculated the posterior probability of an employee working remotely given they report **High Stress**:
* **Result:** If an employee suffers from high stress, there is a **~49%** probability they are a Remote Worker.
* **Insight:** Stress is statistically more prevalent among remote workers in this dataset.

### 3. Wellbeing Correlation 📉
* **Correlation Coefficient (r):** -0.36.
* **Insight:** A moderate negative correlation exists; as isolation increases, wellbeing tends to decrease. However, isolation explains only **13.2%** of the variance in wellbeing, suggesting other complex factors are at play.

---

## 🛠️ Tools & Technologies
* **Language:** R (v4.x)
* **Libraries:** `tidyverse`, `dplyr`, `ggplot2`
* **Techniques:**
    * Descriptive Statistics (Mean, Median, IQR)
    * Data Visualization (Boxplots, Scatter plots)
    * Inferential Statistics (Sampling Distributions, Hypothesis Testing)
    * Probability Theory (Bayes' Rule)
    * Simple Linear Regression

---

## 👥 Team Members
This project was conducted by a dedicated team from the **Faculty of Computer and Information Sciences, Ain Shams University**.

| Name | Role |
|------|------|
| **Abanob Adly Gad** | Team Leader |
| **Anthony George Shaker** | Team Member |
| **Kirolos Samy Tadrous** | Team Member |
| **Pierre Bassem Salah** | Team Member |
| **Sabry Ehab Wahba** | Team Member |

---

## 📂 Repository Structure
* `Analysis_Code.r`: The main R script containing all statistical calculations and plots.
* `Statistical_Analysis_Report.pdf`: The final documentation presenting the problem statement, methodology, and conclusions.
* `README.md`: Project documentation.

---

## 🚀 How to Run
1. Clone this repository.
2. Open `Analysis_Code.r` in RStudio.
3. Ensure the dataset is loaded correctly in the working directory.
4. Run the script line-by-line to view the generated plots and console outputs.

---

> **Disclaimer:** This project uses simulated data for educational purposes within a university course context.
