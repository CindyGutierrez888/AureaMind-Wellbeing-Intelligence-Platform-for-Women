# AureaMind-Wellbeing-Intelligence-Platform-for-Women
AureaMind is a complete data science project that simulates the design, construction and analysis of a digital mental health platform focused on women's wellbeing.  

The project covers the full lifecycle of a data product: from data architecture and synthetic data generation, to predictive modeling, behavioral analysis and strategic insights.The project is designed to be scalable and extensible, with future integration of automation pipelines and operational workflows

It includes three core analytical solutions:

• Early Dropout Risk Prediction  
• Wellbeing Trajectory Modeling  
• User Behavioral Segmentation

All data used in this project is synthetically generated to reflect realistic user behavior over a six-month period, following strict coherence rules and business logic inspired by real-world mental health platforms.

## Project Objectives
• Generate business and health insights
• Track and evaluate women’s wellbeing progress
• Detect behavioral patterns associated with outcomes
• Predict user dropout risk
• Build a scalable analytical architecture

## Dataset Arquitecture
| Table           | Description                     | Size    |
| --------------- | ------------------------------- | ------- |
| `users`         | Static entity: one row per user | 1,000   |
| `assessments`   | Periodic wellbeing evaluations  | 9,000   |
| `sessions`      | Scheduled therapeutic sessions  | 24,000  |
| `engagement`    | Daily in-app behavior           | 180,000 |
| `content_usage` | Content consumption events      | 60,000  |
| `outcomes`      | Final user program results      | 1,000   |

#### Total records: ~275,000

This structure enables:
• Longitudinal modeling
• Behavioral analysis
• Future prediction
• Impact measurement

##Data Model

#### Primary Key (PK): Unique identifier of each record
#### Foreign Key (FK): Relationship between tables

Central entity: users
All other tables are linked through user_id.

## 🧾 Data Dictionary (Summary)

Each table includes fully documented fields with data types and descriptions for interpretability and modeling consistency.

(Detailed data dictionary available in /docs folder)

## Project Roadmap (6 Weeks) 
Considering 6 weekx to work organically with no burnouts.

### Week 1 — Objectives & Architecture  (Completed) 

✔ Problem definition

✔ Dataframes arquitecture

✔ Data modeling & schema

### Week 2 — Synthetic Data Generation (Completed)

✔ Data simulation with Pandas & NumPy

✔ CSV generation

✔ Initial EDA

### Week 3 — Project 1: Dropout Risk Prediction (in progress)

Churn model
Evaluation & metrics
Business insights

### Week 4 — Project 2: Wellbeing Trajectory Analysis (in progress)

Time series modeling
Progress prediction
Visual analysis

### Week 5 — Project 3: User Segmentation (in progress)

Clustering
Group profiling
Product implications

### Week 6 — Professional Refinement (in progress)

Final documentation
Visual polish
Repository cleanup
Final conclusions & next steps

## 🚀 Next Steps

Planned expansion includes:

* Automated data pipelines
* Model retraining workflows
* MLOps and deployment processes
