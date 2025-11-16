
#  Covid-19: Comparative Data Analysis and Prediction for the World and Bangladesh.

**A Machine Learning and Deep Learning-Based Study for World and Bangladesh COVID-19 Trends**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)
![Last Update](https://img.shields.io/badge/Updated-June%202025-brightgreen)

---

## Project Overview

# This project explores the spread and progression of the COVID-19 pandemic through a **comparative analysis** between **global** data and **Bangladesh-specific** data. i am apply **time series forecasting** and **machine learning models** to predict confirmed, death, and recovered cases using real-world data.

# The goal is to develop robust models (e.g., **LSTM**, **CNN**, **ARIMA**, and **XGBoost**) to support **public health planning** and **early-warning systems**.

---

##  Objectives


-  Compared COVID-19 trends to : World vs. Bangladesh
-  Forecast future case counts using ML and deep learning
-  Evaluate models based on MAE, RMSE, R, and MASE
-  Visualize patterns and trends for data-driven decision making
-  To Build hybrid models (CNN-LSTM) for enhanced accuracy


## Project Structure

 FINAL_project.ipynb # Main Jupyter notebook with full analysis and models
 data/
+--covid_19_data1.csv # world COVID-19 data
+-- COVID_DataSet_Bangladesh_Test_Confirm_Death_Recovery.csv # Bangladesh-specific data
 models/
+-- trained_models.h5 # Saved model weights (optional)
 results/
+-- plots/ # Forecasting results and EDA visualizat



# 1.INTRODUCTION	
- Overview and Purpose of the Project-	
- Research Question, Aims, and Objectives	
# 2. BACKGROUND	
- 2.1 Overview of the COVID-19 Pandemic	
- 2.2 Bangladesh in the Context of the Global Pandemic	
- 2.3 Importance of Comparative Analysis	
- 2.4 Predictive Modeling in Epidemiology	
- 2.5 Machine Learning and Deep Learning Applications in COVID-19 Forecasting	
- 2.6 Significance of the Study	
- 2.7 Selection Criteria for Literature Review	
- 2.8 Summary of Literature Review	
# 3.Dataset	
- 3.1 Preprocessing Steps	
- 3.2 Exploratory Data Analysis (EDA)	
- 3.3 Dataset Selection	9
- 3.4 Features of Dataset	
- 3.5 Data Type and Quality	
- 3.6 Summary of Project Methodology	
# 4. Ethical Issues	
# 5. Methodology	
# 6. Analysis and Results	
- 6.1. Dataset Description	
- 6.2 Data Type Conversion	
- 6.3 Global Summary of COVID-19 Cases: Total Counts and Percentage Distribution	
- 6.4 Model Performance Comparison (COVID-19: Actual vs Predicted and Evaluation Metrics in the world all cases).	
- Model Used: Long Short-Term Memory (LSTM) neural network	
- XGBoost Regressor (Extreme Gradient Boosting Regressor)	
- 6.5 The First Epicenter of the pandemic- Since China is the first epicenter of this pandemic situation, I am checking for provinces within China to detect the spread out of the virus-	
- 6.6 These are detailed parts of the world-	
	20 number of countries affected Show In a Plot	
- 6.7 COVID-19 Impacts and Response in Bangladesh-	
- 6.8 COVID-19 Distributions in Bangladesh: A Pie Chart Perspective-
- 6.9 Correlation Analysis of COVID-19 Factors in Bangladesh	
- 6.10 .Forecasting COVID-19 Trends in Bangladesh Using LSTM: Actual vs. Predicted Analysis for Confirmed, Deaths, and Recovered Cases.	
- 6.11 .Comparative forecasting of COVID-19 Trends: Bangladesh vs. Global Cases Using Deep Learning Models-	
- LSTM training and prediction complete and Evaluation Metrics in the world -	
- Bangladesh LSTM training and prediction completed.	
- World vs. Bangladesh cumulative LSTM training and prediction completed:	
# 7.Final Model Selection & Final Result :	
- 7.1 Final Model Selection & Results: LSTM-Based COVID-19 Forecasting for Bangladesh	
- Model Architecture:	
- Evaluation Metrics:	
- Prediction vs Actual :	
- Forecast Insight:	
# LMST Model:	
# CNN Model:	
# 7.2 Model Performance Comparison:	
- Forecast Model 14 Days	
# 8. Discussion and Limitations	
- 8.1 Discussion	
- 8.2 Limitations	
# 9. Future Work	
# 10. Conclusion	
# 11. REFERENCES
# 12. APPENDICES.	

##  Models Used

| Model        | Description                               | Use Case                       |
|--------------|-------------------------------------------|-------------------------------|
| `ARIMA`      | Statistical time series forecasting        | Baseline prediction            |
| `LSTM`       | Long-term memory recurrent neural network  | Captures complex temporal trends |
| `CNN`        | Detects local features in time sequences   | Enhances deep learning         |
| `XGBoost`    | Gradient boosting regression               | Fast, but less accurate here   |





##  Exploratory Analysis Highlights

-  Global confirmed cases peaked in early 2021
-  Bangladesh data showed high volatility and gaps
-  Strong correlation between confirmed and recovered trends
-  Multi-wave patterns observed in both global and local data

---

##  Limitations

- Short forecasting window (14 days)
- No vaccination or mobility data included
- Data quality issues (missing/reported delays in Bangladesh)

---

##  Future Work

- Integrate external features (vaccination, lockdown, mobility)
- Use Transformer-based models (e.g., Informer, TFT)
- Build real-time dashboards with Streamlit / Dash
- Apply uncertainty quantification (Bayesian LSTM)
- Extend to division-wise forecasting in Bangladesh

---

## License

This project is licensed under the **MIT License**  see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- WHO, Kaggle, Johns Hopkins University, DGHS Bangladesh for data
- University of Hertfordshire  MSc Data Science Programme
- Supervisor: Dr. William Bate

---

## Links

- Full Project Report (PDF): [[Available on request](https://drive.google.com/file/d/1-prXeho5LhrfV-pqZfXG-z0ti-RI-2rt/view?usp=drive_link)]
- Dataset Sources: [Kaggle](https://www.kaggle.com), [WHO](https://www.who.int)
-  Google Drive Folder: [Click here](https://drive.google.com/drive/folders/1uTZzwnYL3Wu4xKs4Sn8EhH273IUYTHo0?usp=drive_link)
- GitHub Repo: [Project Repository](https://github.com/Fariduk/PROJECT-DATA-SCIENCE-COVID-19-Comparative-Data-Analysis-and-Prediction-for-the-World-and-Bangladesh)

---

##  Contact

**Farid Hossain**  
Email: [faridhossain7600@gmail.com]  
MSc Data Science  University of Hertfordshire











