# failure_type_predictor_AI
Edunet foundation IBM AI and cloud technologies internship Project

# AutoAI Project
---

## 🔍 Overview

The `failure_type_predictor_AI` is a machine learning model designed to predict the **type of failure** a machine might encounter before it actually happens. This helps industries reduce unplanned downtime, optimize maintenance schedules, and save operational costs. The model uses sensor readings and machine-specific data to forecast potential issues.

---

## 📊 Problem Statement

In manufacturing and industrial settings, machines often fail due to various reasons. The objective of this project is to classify **different types of machine failures** using historical data collected from IoT-enabled sensors. This classification aids in taking proactive measures to prevent major breakdowns.

---

## 🧠 Model Architecture

- **Model Name:** `failure_type_predictor_AI`
- **Algorithm Used:** Random Forest Classifier (with tuning)
- **Target Feature:** `failure_type`
- **Input Features:** `air_temperature`, `process_temperature`, `rotational_speed`, `torque`, `tool_wear`, etc.
- **Output:** Predicted failure class (e.g., Heat Dissipation, Power Failure, Tool Wear, etc.)

---

## ✅ Features

- Real-time fault prediction.
- Probability scores for multi-class classification.
- Deployable as a REST API or cloud model (Watsonx.ai supported).
- Scalable for large industrial setups.

---


