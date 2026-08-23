# CallMeMaybe — Telecom Operator Performance Analysis

## 📊 Project Overview

This project analyzes the performance of call center operators for **CallMeMaybe**, a virtual telephony service.

The main objective is to identify differences in operator performance and determine which operators present less expressive results across different performance indicators.

The analysis was conducted using exploratory data analysis (EDA) and statistical hypothesis testing, followed by the creation of groups of operators requiring attention.

---

## 🎯 Objectives

The project aims to:

- Analyze call center operator performance;
- Identify differences in operator behavior;
- Evaluate inbound and outbound call activity;
- Analyze waiting time and missed calls;
- Identify operators with less expressive performance;
- Segment operators according to the areas in which they require improvement;
- Provide actionable recommendations based on the analysis.

---

## 🗂️ Dataset

The dataset contains information about calls handled by operators, including variables related to:

- Operator ID;
- Call direction (inbound/outbound);
- Number of calls;
- Missed calls;
- Waiting time;
- Call duration;
- Date and time information.

The original dataset was cleaned and prepared before the analysis.

> The original CSV files are not included in this repository.

---

## 🧹 Data Preparation

The data preparation process included:

- Data type corrections;
- Date and time formatting;
- Identification and treatment of missing values;
- Analysis and treatment of outliers;
- Creation of derived metrics;
- Filtering of relevant operator groups;
- Aggregation of data by operator when appropriate.

New metrics were also created to support the analysis, including:

- Average waiting time;
- Missed call ratio;
- Total number of calls;
- Inbound/outbound operator classification.

---

## 🔎 Exploratory Data Analysis

The exploratory analysis was performed using Python and included:

- Descriptive statistics;
- Distribution analysis;
- Histograms;
- Boxplots;
- Analysis of outliers;
- Comparison of operator performance;
- Analysis of inbound and outbound activity.

The EDA was used to understand the characteristics of the data and support the subsequent statistical analysis.

---

## 🧪 Hypothesis Testing

Statistical hypothesis tests were performed to determine whether operator performance differed significantly across the analyzed metrics.

The **Kruskal-Wallis test** was used as the main statistical test because the data presented characteristics such as non-normal distributions and significant outliers.

The analysis evaluated three main performance situations:

1. **Waiting time**
2. **Missed calls**
3. **Outbound call volume**

The results indicated statistically significant differences between operators in the three situations analyzed.

These results supported the creation of distinct groups of operators with less expressive performance.

---

## 📌 Results

The analysis identified **393 operators** with less expressive performance in at least one of the evaluated situations.

The operators were segmented according to the performance indicators analyzed, allowing the identification of different areas requiring attention.

The statistical analysis indicates that the observed differences between operators are unlikely to be explained solely by random variation.

---

## 💡 Recommendations

Based on the results, two main recommendations were developed.

### 1. Targeted training

Provide training sessions focused on the specific areas where each operator demonstrates lower performance.

For example, operators identified as having higher waiting times could receive training focused on call handling efficiency.

This approach allows training resources to be directed according to each operator's specific needs.

### 2. Better distribution of responsibilities

Consider a more balanced distribution of inbound and outbound calling responsibilities.

Operators who perform a high volume of outbound calls may have less availability to answer inbound calls, potentially contributing to longer waiting times or missed calls.

A better allocation of responsibilities could therefore contribute to improving overall team performance.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Jupyter Notebook**
- **Git & GitHub**

---

## 📁 Project Structure

```text
├── Análise a CallMeMaybe.ipynb
├── Apresentação a CallMeMaybe.pdf
├── README.md
└── .gitignore
