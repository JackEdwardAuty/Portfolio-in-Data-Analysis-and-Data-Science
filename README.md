# Portfolio in Data Analysis and Data Science

Welcome to my data portfolio. This repository acts as a central hub for the projects that best represent my journey from personal analytics, through Bachelors‑level machine learning, to Masters‑level reinforcement learning research. Together, they cover the spectrum from practical data analysis and dashboarding to experimental AI research.

---

## Overview of Flagship Projects

| # | Project | Focus | Key Skills |
|---|--------|-------|-----------|
| 1 | Markdown Notes – Personal Analytics | Personal habit / wellbeing analytics from Markdown notes | Python, Text parsing (regex), data wrangling, Tableau dashboards |
| 2 | Masters – Curriculum Learning for RL | Structuring tasks to improve RL training performance | Experiment design, RL, quantitative analysis |
| 3 | Bachelors – Early Sepsis Prediction | Predicting clinical deterioration ahead of time | Time‑series ML, evaluation, UML architecture |

Each project lives in its own repository with detailed documentation and code; this portfolio README explains how they fit together and what they show about my skills.

---

## 1. Markdown Notes – Personal Analytics

**Repository:** [Markdown-Notes-Processing-and-Analysis](https://github.com/JackEdwardAuty/Markdown-Notes-Processing-and-Analysis)

This project turns a long‑running Obsidian note‑taking habit into a structured analytics problem. Daily Markdown templates contain medication, meal times, sleep, and other tracked events; the goal is to systematically extract and analyse this information.
The challenges were that  the data would 

**What I did**

- Designed Python scripts to parse Markdown daily notes and templates into tabular data, handling irregularities and missing entries in real‑world personal logs.
- Performed exploratory analysis and built interactive charts / dashboards in Excel and Tableau to understand relationships between routines, medication timing, and sleep or wellbeing outcomes. 
- Documented the pipeline so it can be re‑run as new notes are added, turning the project into a living personal analytics system rather than a one‑off analysis.

**Why it matters for data roles**

- Demonstrates practical data‑wrangling and feature engineering on messy text data.
- Shows familiarity with business‑style dashboarding tools and the ability to communicate findings visually.

---

## 2. Masters Project – Curriculum Learning for Reinforcement Learning

**Repository:** [Masters-Project-Exploring-Curriculum-Learning-to-Improve-Reinforcement-Learning](https://github.com/JackEdwardAuty/Masters-Project-Exploring-Curriculum-Learning-to-Improve-Reinforcement-Learning)

This Masters dissertation investigates how **curriculum learning** – presenting tasks in order of increasing complexity – can accelerate and stabilise training of reinforcement learning agents.[web:94][web:97]

**What I did**

- Implemented RL agents (using Python and deep learning / RL frameworks) and designed different curriculum strategies to control task difficulty over time.
- Ran controlled experiments, collected training curves and metrics, and analysed when curriculum learning improves sample efficiency and final performance compared with baseline training.
- Wrote a detailed thesis tying experimental results back to the broader RL and curriculum‑learning literature, strengthening skills in research communication and critical evaluation.

**Why it matters for data roles**

- Shows experience with complex modelling workflows, experiment tracking, and quantitative comparison of competing methods.
- Reinforces strengths in statistical thinking, research design, and explaining model behaviour – all valuable for applied data science and ML roles.

---

## 3. Bachelors Project – Early Prediction of Sepsis from Clinical Data

**Repository:** [Bachelors-Project-Early-Prediction-of-Sepsis-from-Clinical-Data](https://github.com/JackEdwardAuty/Bachelors-Project-Early-Prediction-of-Sepsis-from-Clinical-Data)

This Bachelors project explores building an ML system to predict sepsis onset several hours before clinical recognition, using ICU time‑series data. It is inspired by public sepsis‑prediction challenges and research.

**What I did**

- Implemented a pipeline that loads and preprocesses multivariate clinical time‑series, creates fixed‑horizon windows (e.g. 6‑hour prediction), and handles missing values and class imbalance.
- Trained and evaluated machine‑learning models (e.g. XGBoost or other classifiers), using ROC and precision–recall curves to reflect clinical trade‑offs between sensitivity and false alarms.
- Documented the software architecture with UML class and sequence diagrams (DataLoader → ModelTrainer → Evaluator), making it easier to explain the system to clinicians and engineers alike.

**Why it matters for data roles**

- Demonstrates end‑to‑end project skills: from raw data to model evaluation and interpretation.
- Shows ability to reason about domain‑specific constraints (clinical risk, imbalance, evaluation metrics) while keeping the codebase organised and maintainable.

---

## How to Read This Portfolio

- If you are interested in **analyst‑style work** (data cleaning, dashboards, stakeholder communication), start with the Markdown Notes project.
- For **applied machine learning** on structured data, explore the Bachelors Sepsis Prediction project.
- For **research‑oriented ML / RL**, see the Masters Curriculum Learning project.

You can find links to each repository above; over time, this portfolio hub will be updated with additional projects and maybe lightweight summaries or slide decks for quick interview walk‑throughs.
