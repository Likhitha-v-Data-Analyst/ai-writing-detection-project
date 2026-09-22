# ai-writing-detection-project
AI-Assisted Writing Detection — An end-to-end data analytics project analyzing student writing behavior (typing speed, revisions, plagiarism score) to detect AI-assisted submissions. Built using Python (EDA &amp; cleaning), SQL (MySQL queries), and Power BI (interactive dashboard).
# 🧠 AI-Assisted Writing Detection — End-to-End Data Analytics Project

## 📖 Overview

This project explores a question that's becoming increasingly relevant in education: **can we detect AI-assisted writing by analyzing behavioral patterns, rather than the text itself?**

Using a dataset of ~10,000 student writing submissions, this project investigates whether measurable writing-behavior metrics — typing speed, revision patterns, plagiarism scores, and more — can reveal meaningful differences between human-written and AI-assisted academic work.

Rather than relying on content-based detection (analyzing *what* was written), this analysis focuses on **how** the writing was produced — capturing signals like how quickly someone typed, how many times they revised their draft, and how closely the final content matched existing sources.

The project follows a complete data analytics workflow, from raw data to a polished, interactive dashboard:

- 🐍 **Python** — Data cleaning, outlier handling, and exploratory data analysis (EDA)
- 🗄️ **SQL** — Structured querying (MySQL) to validate and dig deeper into patterns found during EDA
- 📊 **Power BI** — An interactive dashboard visualizing key findings for non-technical stakeholders

### Key Finding
The strongest signals separating AI-assisted from human-written submissions weren't grammar or vocabulary — they were **behavioral**: AI-assisted submissions showed dramatically higher typing speeds, far fewer revisions, and — counterintuitively — *lower* plagiarism scores than human-written ones.

---

## 📂 Dataset

- **Source:** Kaggle
- **Size:** 10,200 rows × 20 columns (10,000 rows after cleaning)
- **Target column:** `Is_AI_Assisted` (0 = human-written, 1 = AI-assisted)
- **Key features:** `Word_Count`, `Typing_Speed`, `Revision_Count`, `Plagiarism_Score`, `Grammar_Errors`, `Vocabulary_Richness`, `Academic_Level`, `Submission_Type`, `Submission_Hour`, and more

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy, Matplotlib, Seaborn) | Data cleaning, outlier detection, EDA |
| Google Colab | Notebook environment |
| MySQL Workbench | Data storage and SQL querying |
| Power BI | Interactive dashboard and visualization |

---

## 🗂️ Project Structure
