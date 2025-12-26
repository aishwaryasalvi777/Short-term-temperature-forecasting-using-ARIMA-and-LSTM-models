# 🌡️ Short-Term Temperature Forecasting using ARIMA and LSTM

## 📋 Project Overview
This project presents a comprehensive **time series forecasting study** comparing **ARIMA (AutoRegressive Integrated Moving Average)** and **LSTM (Long Short-Term Memory)** models for predicting **short-term temperature variations across U.S. cities**.

The work combines **statistical modeling** and **deep learning approaches** to evaluate forecasting performance and identify optimal methodologies for short-term weather prediction.

**Course:** Statistics Project (STAT)  
**Team:** Team 12  
**University:** University at Buffalo  
**Date:** 2024  

---

## 🎯 Project Objectives
- **Data Analysis:** Perform exploratory data analysis on U.S. city temperature datasets  
- **Model Development:** Implement and optimize ARIMA and LSTM forecasting models  
- **Comparative Analysis:** Benchmark model performance using statistical metrics  
- **Validation:** Validate forecasts against real-world temperature trends  
- **Documentation:** Provide comprehensive technical and statistical documentation  

---

## 📁 Project Structure
├── 01_Source_Code/
│ ├── Python/
│ │ └── PyCode_Stat.ipynb
│ └── R_Code/
│ ├── Team12Code.Rmd
│ ├── data_preparation.R
│ └── data_preparation-Siddhi-Acer-Aspire-7.R
│
├── 02_Data/
│ ├── Raw/
│ │ └── US_City_Temp_Data.csv
│ └── Processed/
│
├── 03_Documentation/
│ ├── Meeting_Notes/
│ └── Progress_Reports/
│ └── Progress Report.pdf
│
├── 04_Reports/
│ ├── Final_Reports/
│ │ ├── final report Time Series Analysis.docx
│ │ ├── Team12report.pdf
│ │ ├── group project.pdf
│ │ ├── Paper_33-Time_Series_Forecasting_using_LSTM_and_ARIMA.pdf
│ │ └── Weather_Forecasting_Using_Spatial_Feature_Based_LS.pdf
│ └── Proposals/
│ ├── Team 12 Proposal.docx
│ └── team12proposal.docx
│
├── 05_Research_Papers/
│ ├── Harshal/
│ ├── Mrudula/
│ └── Sidhhi/
│
├── 06_Presentations/
│ └── Project_Poster_Template.pptx
│
├── .archive/
├── .git/
├── .gitattributes
└── README.md



---

## 🚀 Getting Started

### Prerequisites

**Python**
- Python 3.7+
- pandas, numpy, scikit-learn
- TensorFlow / Keras
- statsmodels
- matplotlib, seaborn

**R**
- R 4.0+
- forecast, lubridate, ggplot2, tidyverse

---

### Installation
```bash
git clone [repository-url]
cd short-term-temp-forcast-ARIMA-LSTM-Statistic


Python Environment
pip install pandas numpy scikit-learn tensorflow statsmodels matplotlib seaborn


R Environment
install.packages(c("forecast", "lubridate", "ggplot2", "tidyverse"))


▶️ Running the Analysis
Python Implementation
jupyter notebook 01_Source_Code/Python/PyCode_Stat.ipynb

R Implementation
rmarkdown::render("01_Source_Code/R_Code/Team12Code.Rmd")

📊 Methodology
Data

Source: U.S. City Temperature Dataset

Variables: Temperature readings, temporal features, city identifiers

Time Period: As provided in dataset

Frequency: Daily

Modeling Approaches
1. ARIMA

Stationarity testing (ADF, KPSS)

ACF / PACF analysis

Parameter tuning (p, d, q)

Residual diagnostics and validation

2. LSTM

Sequence-to-sequence modeling

Time windowing and normalization

Multi-layer LSTM with dropout

Train / validation / test splits

Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Mean Absolute Percentage Error (MAPE)

Diebold–Mariano test

Residual analysis

📈 Key Findings

Add specific RMSE, MAPE, and performance comparison results here.

👥 Team Members & Contributions
Member	Contributions
Harshal	Weather forecasting research, meteorological analysis
Mrudula	CNN-LSTM hybrid approaches, Bayesian methods
Sidhhi	ARIMA comparison and literature review
📚 Research References

Time Series Forecasting using LSTM and ARIMA

Weather Forecasting Using Spatial Features

Comparative Analysis of ARIMA and LSTM Predictions

CNN-LSTM Hybrid Methods

Bayesian Inference in Neural Networks

See 05_Research_Papers/ for the complete reference collection.

🔧 Technical Stack
Component	Technology
Data Processing	Python (pandas, numpy), R (tidyverse)
Statistical Modeling	statsmodels, forecast
Deep Learning	TensorFlow / Keras
Visualization	Matplotlib, Seaborn, ggplot2
Documentation	Jupyter Notebook, R Markdown
Version Control	Git / GitHub
🛠️ Skills & Techniques

Time series decomposition

Stationarity testing & differencing

LSTM sequence modeling

Feature engineering (lags, rolling windows)

Model evaluation & statistical testing

Hyperparameter tuning

📋 Project Timeline

Literature review & data collection

Data exploration & preprocessing

ARIMA model development

LSTM model training

Comparative evaluation

Final reporting & presentation

📧 Contact & Support

For detailed documentation, refer to:

04_Reports/Final_Reports/

03_Documentation/

04_Reports/Proposals/

📂 Archive

Legacy files from earlier project versions are preserved in the .archive/ directory.

📄 License

This project is submitted as coursework for University at Buffalo (MS Program).

✅ Checklist

Review 04_Reports/Final_Reports/

Check 05_Research_Papers/

Run Python and R notebooks

Review raw data in 02_Data/Raw/

Last Updated: December 2024
Project Status: ✅ Complete
