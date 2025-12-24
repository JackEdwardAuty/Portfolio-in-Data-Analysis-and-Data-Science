# Portfolio in Data Analysis and Data Science

Welcome to my data portfolio. This repository acts as a central hub for the projects that best represent my journey from Bachelors‑level machine learning, through Masters‑level reinforcement learning research to Personal Data Analytics. Together, they cover the spectrum from practical data analysis and dashboarding to experimental AI research.

---

## Skills Demonstrated

Across these projects, this portfolio shows:

- **Data wrangling and cleaning** in Python (pandas, custom **regex based parsers** for Markdown, time‑series preprocessing).
- Exploratory **Data Analysis**, **Visualisation** and **dashboarding** (Excel / **Tableau** / Power BI).
- **Machine learning** for tabular and time‑series data, including **evaluation** on imbalanced problems/datasets (sepsis prediction).
- **Reinforcement learning**, **Curriculum Learning** exploration with **curricula design** from the Masters project.
- Communication of complex ideas via diagrams, notebooks, and written reports suitable for both technical and non‑technical audiences.

---

## Overview of Flagship Projects

| # | Project | Focus | Key Skills |
|---|--------|-------|-----------|
| 1 | [Markdown Notes – Personal Analytics](https://github.com/JackEdwardAuty/Markdown-Notes-Processing-and-Analysis) | Personal habit / wellbeing analytics from Markdown notes | **Python**,  **Data Wrangling**, **Tableau dashboards**:<br>- Built **Python scripts (regex)** to **parse Markdown** and **transform** templates into **analysis ready** tables (datetimes, categories, metrics).<br>- Demonstrates practical **data‑wrangling** on real, messy text; **feature engineering**; and **communication** of insights in a way that **non‑technical people** can understand.<br>- Created **visualisations and dashboards** in **Tableau** to explore relationships between routines, medications, and sleep or wellbeing measures. |
| 2 | [Masters – Curriculum Learning for RL](https://github.com/JackEdwardAuty/Masters-Project-Exploring-Curriculum-Learning-to-Improve-Reinforcement-Learning) | Structuring tasks to improve RL training performance | **Experiment Design**, **Reinforcement Learning**, **Quantitative Analysis**, **Codebase Management**: <br>- Implemented and evaluated **reinforcement learning agents** under different curriculum strategies, using **Python, TensorFlow and RL libraries**.<br>- Designed experiments, collected results, and **analysed learning curves and performance metrics** to understand when curricula help or hurt training. <br>- Shows **ability to manage complex codebases**, **design controlled experiments**, and **interpret model behaviour** – skills that transfer directly to A/B testing and **model evaluation** in industry. |
| 3 | [Bachelors – Early Sepsis Prediction](https://github.com/JackEdwardAuty/Masters-Project-Exploring-Curriculum-Learning-to-Improve-Reinforcement-Learning) | Predicting clinical deterioration ahead of time | **Time‑series Machine Learning**, **end‑to‑end** with **ETL**, **Model Training**, **Evaluation**:<br>- Built an **end‑to‑end workflow**: **data loading and preprocessing**, windowed feature creation, **model training** (e.g. tree‑based or gradient‑boosted models), and **evaluation**. <br>- Used metrics such as **ROC AUC** and **precision–recall** to assess early‑warning performance on **highly imbalanced clinical data**.  <br>- Includes **UML and sequence diagrams** to document the architecture (DataLoader → ModelTrainer → Evaluator) and to **communicate clearly with clinical or non‑technical stakeholders**.|

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

**Technical Highlights**

- Built Python scripts to parse and transform Markdown templates into analysis‑ready tables (dates, times, categories, metrics).
- Performed exploratory analysis and built interactive charts / dashboards in Excel and Tableau to explore relationships between routines, medications, and sleep or wellbeing measures.
- Demonstrates practical data‑wrangling on real, messy text; feature engineering; and communication of insights in a way that non‑technical people can understand.

---

## 2. Masters Project – Curriculum Learning for Reinforcement Learning

**Repository:** [Masters-Project-Exploring-Curriculum-Learning-to-Improve-Reinforcement-Learning](https://github.com/JackEdwardAuty/Masters-Project-Exploring-Curriculum-Learning-to-Improve-Reinforcement-Learning)

This Masters dissertation investigates how **curriculum learning** – presenting tasks in order of increasing complexity – can accelerate and stabilise training of reinforcement learning agents.

**What I did**

- Implemented and evaluated RL agents (using Python and deep learning / RL frameworks) and designed different curriculum strategies to control task difficulty over time.

- Wrote a detailed thesis tying experimental results back to the broader RL and curriculum‑learning literature, strengthening skills in research communication and critical evaluation.

**Why it matters for data roles**

- Shows experience with complex modelling workflows, experiment tracking, and quantitative comparison of competing methods.
- Designed and ran controlled experiments, collected training curves and metrics, and analysed when curriculum learning improves sample efficiency and final performance compared with baseline training.
- Reinforces strengths in statistical thinking, research design, and explaining model behaviour – all valuable for applied data science and ML roles.

**Technical Highlights**

- Implemented and evaluated RL agents (using Python, Tenserflow and x,x,RL frameworks) and designed different curriculum strategies to control task difficulty over time.
- Designed controlled experiments, collected training curves and metrics, and analysed when curriculum learning improves sample efficiency and final performance compared with baseline training.
- Shows ability to manage complex codebases, design controlled experiments, and interpret model behaviour – skills that transfer directly to A/B testing and model evaluation in industry.

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

**Technical Highlights**

- Built an end‑to‑end workflow: data loading and preprocessing, windowed feature creation, model training (e.g. tree‑based or gradient‑boosted models), and evaluation.  
- Used metrics such as ROC AUC and precision–recall to assess early‑warning performance on highly imbalanced clinical data.  
- Includes UML and sequence diagrams to document the architecture (DataLoader → ModelTrainer → Evaluator) and to communicate clearly with clinical or non‑technical stakeholders.

---

## Skills Demonstrated

Across these projects, this portfolio shows:

- Data **wrangling and cleaning** in Python (pandas, custom regex based parsers for Markdown, time‑series preprocessing).
- Exploratory **data analysis**, visualisation and dashboarding (Excel / Tableau / Power BI).
- **Machine learning** for tabular and time‑series data, including evaluation on imbalanced problems/datasets (sepsis prediction).
- **Reinforcement learning** and curriculum design from the Masters project.
- Communication of complex ideas via diagrams, notebooks, and written reports suitable for both technical and non‑technical audiences.

---

## How to Read This Portfolio

- If you are interested in **analyst‑style work** (data cleaning, dashboards, stakeholder communication), start with the Markdown Notes project.
- For **applied machine learning** on structured data, explore the Bachelors Sepsis Prediction project.
- For **research‑oriented ML / RL**, see the Masters Curriculum Learning project.

You can find links to each repository above; over time, this portfolio hub will be updated with additional projects and maybe lightweight summaries or slide decks for quick interview walk‑throughs.
