---
layout: single
author_profile: true
permalink: /
title: "Akshyat Ankur Patel | AI Engineer & Data Scientist"
---

## About Me

I'm a Data Scientist and AI Engineer with 2+ years of backend development experience at redBus (GO-MMT Group). I specialize in machine learning, predictive modeling, and high‑scale system optimization. Proficient in Erlang/OTP, Python, SQL, data structures & algorithms, and AI frameworks including LLMs and generative AI.

Currently pursuing an MSc in Data Science and AI at Middlesex University Dubai (Jan 2026 – present). Previously earned a B.Tech in Mechanical Engineering from NIT Rourkela (GPA: 8.45/10).

I build end‑to‑end AI products – from data cleaning and feature engineering to model tuning, deployment, and LLM‑powered explanations.

---

## Featured Project

## AI‑Powered Energy Simulation Engine for Dalma Mall (Abu Dhabi)

**Role:** Lead Developer (sole Data Scientist/AI Engineer)  
**Tech stack:** Python, Streamlit, Scikit‑learn, Pandas, NumPy, Plotly, Open‑Meteo API  
**Status:** Deployed and used internally by the mall’s engineering team

### Overview
Developed a production‑ready machine learning system for one of Abu Dhabi’s largest shopping centres to forecast daily **Power (kW)** and **Cooling Load (Tons)** under extreme arid climate conditions. The system enables proactive HVAC planning, shifting from reactive to predictive energy management.

### Key Contributions
- Engineered a **physics‑informed Ridge regression model** with polynomial features, using atmospheric enthalpy instead of naive lag‑based predictors. Achieved **R² > 0.96** for both targets.
- Built an interactive **Streamlit dashboard** with two operating modes:
  - **Manual mode:** real‑time “what‑if” simulation (dry bulb, wet bulb, footfall, occupancy).
  - **Auto date‑range mode:** predicts all input parameters from Open‑Meteo weather data (bias‑corrected to local sensors) + historical footfall/occupancy patterns, then generates day‑by‑day forecasts with downloadable CSV and Plotly time‑series visualisation.
- Deployed on **Streamlit Cloud**; currently used internally by the mall’s engineering team.

### Impact
Helps the mall reduce operational expenditure while maintaining customer comfort in a cooling‑dominated climate. The project demonstrates full‑stack AI engineering: from physics‑informed feature engineering to interactive deployment.

> **Note:** The underlying training data and model coefficients remain proprietary to Dalma Mall. This entry describes the architecture and my development role only.

---

## UAE Real Estate AI Analyzer

A live price prediction app for the UAE property market. Trained on 41,000+ listings with 40+ distance features (Burj Khalifa, Dubai Mall, metro stations, beaches, airports). Uses CatBoost (R² = 0.73, RMSE = 2.46M AED) and explains predictions via Groq LLM.

- **Live demo:** [uae-realestate-ai.streamlit.app](https://uae-realestate-ai-kjmsf4tshdkmtvlnzkgqx7.streamlit.app/)
- **GitHub repo:** [github.com/akshyat21/UAE-RealEstate-AI](https://github.com/akshyat21/UAE-RealEstate-AI)

**Tech:** Streamlit · CatBoost · Optuna · LangChain · Groq API · Python

---

### Customer Churn Prediction with AI Retention Advice

A production‑ready system that predicts whether a telecom customer will churn and generates personalised, LLM‑powered retention recommendations.

- **Live demo:** [ai-churn-prediction.streamlit.app](https://ai-churn-prediction-hpudyompmu5v7jnxk4epso.streamlit.app/)
- **GitHub repo:** [github.com/akshyat21/AI-Churn-Prediction](https://github.com/akshyat21/AI-Churn-Prediction)

**Tech stack:** Python, scikit‑learn, Streamlit, LangChain, Groq API, pandas, joblib

**Key decisions:**
- Logistic regression (AUC 0.84) – interpretable and fast
- Feature selection (11 out of 31 dummies) to reduce noise
- Threshold tuning (0.29) to balance recall (77%) and precision (52%)
- LLM (Groq Llama 3.3) used only for retention suggestions, not risk diagnosis – output is grounded in model coefficients

**Impact:** Helps a retention team prioritise high‑risk customers and act with tailored interventions.

---

## Work Experience

**Software Engineer (Erlang Backend Developer)**  
redBus (GO-MMT Group) | Aug 2023 – Aug 2025 | Bengaluru, India

- Built and maintained scalable, concurrent backend systems using Erlang/OTP.
- Designed and optimized RESTful APIs and background workers for production systems.
- Integrated APIs with ClickHouse, MySQL, MariaDB to ensure efficient data flow.
- Resolved critical production issues, reducing downtime and improving reliability.
- Engineered Grafana dashboards to visualize KPIs for data‑driven decisions.

**Software Engineer Intern**  
redBus (GO-MMT Group) | Mar 2023 – Jun 2023

- Developed a flight booking prototype with search filters, authentication, and booking management.
- Acquired Erlang for high‑concurrency backend systems.
- Deployed production‑grade APIs for the proprietary Order Management System (Neon).

---

## Certifications

- IBM Data Science Professional Certificate (Coursera)
- Machine Learning with Python (Coursera)
- Python for Data Science, AI & Development (Coursera)
- Back‑End / Full Stack Web Development with Node.js (Coding Ninjas)
- Advanced Front‑End Web Development with React (Coding Ninjas)
- Data Structures in C++ (Coding Ninjas)

---

## Hackathon

**Deriv AI Hackathon (Feb 2026)** – Collaborated with a team to build a partner churn prediction model for Deriv.

---

## Skills

**Languages & Databases:** Python, SQL, Erlang, C++, R, ClickHouse, MySQL, MariaDB  
**AI/ML:** Machine Learning, Predictive Modeling, LLMs, Generative AI, TensorFlow, PyTorch, NLP, Prompt Engineering  
**Tools & Practices:** Git, CI/CD Pipelines, Data Structures & Algorithms, Grafana, RabbitMQ, MERN Stack

---

## Contact

- **GitHub:** [github.com/akshyat21](https://github.com/akshyat21)
- **LinkedIn:** [linkedin.com/in/akshyat-ankur-patel-79993a215](https://linkedin.com/in/akshyat-ankur-patel-79993a215)
- **Email:** akshyat2001@gmail.com
