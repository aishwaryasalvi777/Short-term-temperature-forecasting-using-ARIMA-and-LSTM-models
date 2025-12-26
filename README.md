# Short-Term Temperature Forecasting using ARIMA and LSTM

## 📋 Project Overview
This is a comprehensive time series forecasting project that compares **ARIMA** (AutoRegressive Integrated Moving Average) and **LSTM** (Long Short-Term Memory) neural networks for predicting short-term temperature changes across US cities. The project combines statistical analysis with deep learning approaches to determine optimal forecasting methodologies.

* **Course:** Statistics Project (STAT)
* **Team:** Team 12
* **University:** University at Buffalo
* **Date:** 2024

---

## 🎯 Project Objectives
* **Data Analysis:** Conduct exploratory data analysis on US city temperature datasets.
* **Model Development:** Implement and optimize both ARIMA and LSTM forecasting models.
* **Comparative Analysis:** Benchmark model performance using statistical metrics.
* **Documentation:** Provide comprehensive technical and statistical documentation.
* **Validation:** Validate forecasts against real-world temperature patterns.

---

## 📁 Project Structure
```text
.
├── 01_Source_Code/                 # All source code files
│   ├── Python/                     # Python implementations
│   │   └── PyCode_Stat.ipynb       # Main Python analysis notebook
│   └── R_Code/                     # R implementations
│       ├── Team12Code.Rmd          # Main R analysis document
│       ├── data_preparation.R      # Data cleaning and preparation
│       └── data_preparation-Siddhi-Acer-Aspire-7.R  # Variant
│
├── 02_Data/                        # Data storage
│   ├── Raw/                        # Raw unprocessed data
│   │   └── US_City_Temp_Data.csv   # Original temperature dataset
│   └── Processed/                  # Cleaned and transformed data
│
├── 03_Documentation/               # Project documentation
│   ├── Meeting_Notes/              # Team meeting notes
│   └── Progress_Reports/           # Progress updates
│       └── Progress Report.pdf     # Latest progress report
│
├── 04_Reports/                     # Final deliverables
│   ├── Final_Reports/              # Completed reports and analysis
│   │   ├── final report Time Series Analysis.docx
│   │   ├── Team12eport.pdf
│   │   ├── group project.pdf
│   │   ├── Paper_33-Time_Series_Forecasting_using_LSTM_and_ARIMA.pdf
│   │   └── Weather_Forecasting_Using_Spatial_Feature_Based_LS.pdf
│   └── Proposals/                  # Project proposals
│       ├── Team 12 Proposal.docx
│       └── team12proposal.docx
│
│
├── 05_Presentations/               # Presentation materials
│   └── Project_Poster_Template.pptx
│
├── .archive/                       # Old/deprecated files
├── .gitattributes                  # Git configuration
└── README.md                       # This file

---

## 🚀 Getting Started

---

### Prerequisites
* **Python 3.7+**: `pandas`, `numpy`, `scikit-learn`, `TensorFlow/Keras`, `statsmodels`
* **R 4.0+**: `forecast`, `lubridate`, `ggplot2`, `tidyverse`
* **Tools**: Jupyter Notebook or RStudio for interactive development

---

### Installation

1. **Clone the repository:**
   ```bash
   git clone [repository-url]
   cd short-term-temp-forcast-ARIMA-LSTM-Statistic

