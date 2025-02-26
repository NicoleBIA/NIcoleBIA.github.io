---
title: "Reflections on the Cannabis Sales Analysis Project"
date: 2024-02-22
author: Nicole Reaves
---

# **Lessons from the Cannabis Sales Analysis Project** 📊

## **Understanding Data Enrichment & Enhancement**
Today, I made the difficult decision to step away from my cannabis sales dataset after weeks of data wrangling, transformations, and validation efforts. While it’s frustrating, I also recognize the immense growth I’ve had during this process.

What I Learned Today:

- 🔍 **All datasets are not created equal.** Even when data is structured in a CSV, it doesn’t mean it’s analysis-ready.
- 🏗️ **Data modeling matters.** If relationships between fields aren’t clear from the start, analysis will suffer.
- 🔄 **Iteration is key.** Even well-intentioned enhancements can fail if the dataset’s original reporting logic lacks consistency.

---

### **What I Tried** 🛠️
To **enhance the dataset and make it more suitable for analysis**, I attempted several data structuring techniques:
- 🔹 **Date Normalization:** I attempted to standardize and structure the dataset's date fields to differentiate individual months and years.
- 🔹 **Rolling 12-Month Sales Issue:** I discovered that the dataset reported sales on a rolling cumulative basis, making it difficult to **isolate single-month sales** without risk of overcounting.
- 🔹 **Segmentation Attempts:** I connected a **Market Table** for segmentation and a **Product Category Table** for classification.
- 🔹 **Time-Series Analysis Challenges:** Even after adding structured month and year fields, the **dataset still lacked clarity on whether figures represented distinct months or were aggregated over time.**
- 🔹 **Multiple KPI Calculations:** I attempted to create **Monthly Sales KPIs**, but inconsistencies in how totals rolled over made the results unreliable.
- 🔹 **Visualization Diagnostics:** While Tableau helped highlight discrepancies, the **underlying data structure made it impossible to confidently extract meaningful trends.**

---

### **Key Takeaways** 🚀
- **Data integrity is everything!** If the reporting structure of a dataset is unclear, the analysis will be too.
- **Rolling cumulative reporting complicates time-based analytics.** Without a clear breakdown of individual months, meaningful trend analysis is nearly impossible.
- **Enhancements must be verifiable.** Adding segmentation and structured date fields was helpful, but without a clear, reliable source dataset, these adjustments **couldn’t fix the underlying data issues.**
- **Visualization can reveal hidden inconsistencies.** The dataset’s flaws became more apparent **after attempting Tableau visualizations**, reinforcing the importance of **exploratory data analysis (EDA).**
- **Knowing when to pivot is a skill.** The decision to move on was about **maintaining professional integrity** rather than forcing insights from an unreliable dataset.

> **Final Thought:** Not every dataset leads to meaningful analysis, and that’s okay! The real skill lies in **knowing when to pivot** and applying lessons learned to future projects.

---
🌐 **[Back to Diary Index](README.md)**  
🔗 **[Home](../index.html)**
