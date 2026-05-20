# Volve Oil Field Production Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Data Source](https://img.shields.io/badge/Data-Equinor%20Volve-red.svg)](https://www.equinor.com/energy/volve)

A comprehensive machine learning project analyzing production data from the Volve oil field (2008-2016), featuring well classification, production forecasting, anomaly detection, and decline curve analysis.

## 📊 Project Overview

This project leverages public production data from Equinor's Volve field to demonstrate various machine learning techniques for oil & gas analytics. The dataset contains daily production measurements including oil, gas, and water volumes, along with downhole pressure, temperature, and choke settings.

## Problem Statement
The oil and gas industry generates massive amounts of daily production data from wells, including oil output, gas production, water production, pressure, and temperature readings. However, transforming this raw operational data into actionable insights remains a major challenge.

In the Volve Oil Field, production performance varies significantly across wells and over time due to factors such as reservoir behavior, equipment conditions, and operational settings. Traditional monitoring methods are often reactive, making it difficult to:
	•	Identify high-performing and low-performing wells early
	•	Detect abnormal production behavior before major losses occur
	•	Forecast future production accurately
	•	Understand the factors driving production decline

This project aims to apply machine learning and data analytics techniques to historical production data from the Volve Oil Field (2008–2016) to improve production monitoring, anomaly detection, and forecasting.

The main objectives are to:
	1.	Classify wells based on production performance
	2.	Predict future oil and gas production trends
	3.	Detect anomalies in production operations
	4.	Analyze production decline patterns and key influencing factors

By leveraging data-driven insights, the project seeks to support smarter decision-making, optimize production efficiency, and reduce operational risks in oil and gas field management.


### Key Results
- **Well Classification Accuracy**: 85%+ in identifying high vs. low producers
- **Anomaly Detection**: Successfully identified 10% of production days as anomalous
- **Production Forecasting**: R² scores of 0.75-0.85 for weekly predictions
- **Feature Importance**: Water cut and efficiency identified as top predictors

## 📁 Repository Structure
