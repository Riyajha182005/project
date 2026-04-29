# Reliability Assessment and Predictive Maintenance Modeling of Power MOSFET Devices

## Project Overview
This repository contains the research and implementation of a data-driven reliability modeling framework for **Metal-Oxide-Semiconductor Field-Effect Transistors (MOSFETs)** subjected to prolonged electro-thermal stress. Developed during a Winter Research Internship at the **Solid State Physics Laboratory (SSPL), DRDO**, this project integrates semiconductor physics with machine learning to predict failure behavior and remaining useful life (RUL).

The framework is designed to support maintenance decision-making for mission-critical electronic systems, specifically targeting defense, aerospace, and high-reliability industrial environments.

## Key Features
* **Physics-Guided Modeling:** Incorporates core semiconductor failure mechanisms:
    * Time-Dependent Dielectric Breakdown (TDDB)
    * Hot Carrier Injection (HCI)
    * Bias Temperature Instability (BTI)
* **Statistical Reliability:** Implementation of Arrhenius, Eyring, and Weibull distributions to represent temperature-accelerated aging and failure trends.
* **Machine Learning Integration:** Supervised learning pipeline to classify device health states and estimate failure probability over time.
* **Predictive Maintenance:** Transition from reactive to proactive maintenance strategies to minimize downtime and enhance system availability.

## Methodology
The analytical framework was implemented using **Python** (Google Colab) and follows a structured pipeline:
1.  **Data Preprocessing:** Cleaning, normalization, and feature scaling of operational parameters (temperature, voltage, current density, etc.).
2.  **Reliability Formulation:** Calculating failure rates (λ), reliability functions (R(t)), and Mean Time Between Failures (MTBF).
3.  **ML Pipeline:** Utilizing classification and regression techniques to analyze complex nonlinear degradation patterns.
4.  **Evaluation & Visualization:** Analyzing reliability curves, hazard rate functions, and confusion matrices.

## Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn, SciPy
* **Environment:** Google Colab

## Project Objectives
* Analyze the relationship between stress conditions and degradation rates in power MOSFETs.
* Develop a scalable solution for early failure detection.
* Translate reliability predictions into actionable preventive maintenance schedules.

## Credits
* **Author:** Riya Jha (B.Tech Information Technology)
* **Supervision:** Mentors at Solid State Physics Laboratory (SSPL), DRDO, Ministry of Defence, India.
* **Institutional Support:** Dr. Akhilesh Das Gupta Institute of Professional Studies (GGSIPU), New Delhi.
