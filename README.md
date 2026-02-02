# A-Comparative-Analysis-of-DL & ML-Models-for-Integrated-Drought-Monitoring-in-the-Krishna-River-Basin-
This repository develops a Comprehensive Drought Index (CDI) using ML and DL models for the Krishna River Basin, India. Multi-source data from MODIS, CHIRPS, GLDAS, and SPEI are integrated, and models such as RF, XGBoost, LSTM, and ConvLSTM are evaluated to capture spatiotemporal drought dynamics for early warning and water resource planning.
Integrated Drought Monitoring Using Machine Learning and Deep Learning
Krishna River Basin,
📌 Overview
The framework compares classical ensemble models with advanced deep learning approaches to evaluate their ability to capture complex spatiotemporal drought dynamics.

🎯 Objectives

Develop a Comprehensive Drought Index (CDI) using multi-source data

Compare RF, XGBoost, CNN, LSTM, and ConvLSTM models

Validate CDI using station-based SPEI and GLDAS soil moisture

Analyze spatial and temporal drought patterns (2001–2022)

Support drought early warning and water resource planning

🌍 Study Area

The study focuses on the Krishna River Basin, covering parts of Karnataka, Telangana, Andhra Pradesh, and Maharashtra.
The basin is highly vulnerable to drought due to variable rainfall, high agricultural dependency, and increasing water stress.

📊 Datasets Used
Source	Product	Variable	Resolution
MODIS	MOD13A1	NDVI	1 km
MODIS	MOD11A1	LST	1 km
MODIS	MOD16A2	ET	1 km
CHIRPS	v2.0	Precipitation	1 km
GLDAS	2.1	Soil Moisture	1 km
Stations	SPEI	SPEI-1/3/6	Point
🧠 Models Implemented

Random Forest (RF)

XGBoost

Convolutional Neural Network (CNN)

Long Short-Term Memory (LSTM)

Convolutional LSTM (ConvLSTM)

ConvLSTM demonstrated superior performance in capturing spatial–temporal drought evolution, while RF and XGBoost provided strong and computationally efficient baselines.

📈 Evaluation Metrics

Coefficient of Determination (R²)

Root Mean Square Error (RMSE)

Mean Absolute Error (MAE)


🔍 Key Findings

ConvLSTM best captured spatiotemporal drought patterns

RF achieved high accuracy with low computational cost

ET and LST (TCI) were the most influential drought factors

CDI showed strong agreement with SPEI and soil moisture

🚀 Applications

Drought early warning systems

Agricultural risk assessment

Water resource management

Climate impact studies

📖 Citation

If you use this work, please cite:

Islam, A.
A Comparative Analysis of Deep Learning and Machine Learning Models for Integrated Drought Monitoring in the Krishna River Basin.

📬 Contact

Ahidul Islam
Department of Geoinformatics
JSS Academy of Higher Education & Research, Mysuru
📧 Email: ahidul@email.com
