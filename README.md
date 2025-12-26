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

## 🚀 Getting Started

---

### **Prerequisites**
* **Python 3.7+**: `pandas`, `numpy`, `scikit-learn`, `TensorFlow/Keras`, `statsmodels`
* **R 4.0+**: `forecast`, `lubridate`, `ggplot2`, `tidyverse`
* **Tools**: Jupyter Notebook or RStudio for interactive development

---

🚀 Getting StartedPrerequisitesPython 3.7+: pandas, numpy, scikit-learn, TensorFlow/Keras, statsmodelsR 4.0+: forecast, lubridate, ggplot2, tidyverseTools: Jupyter Notebook or RStudio for interactive developmentInstallationClone the repository:Bashgit clone [repository-url]
cd short-term-temp-forcast-ARIMA-LSTM-Statistic
Set up Python environment:Bashpip install pandas numpy scikit-learn tensorflow statsmodels matplotlib seaborn
Set up R environment:Rinstall.packages(c("forecast", "lubridate", "ggplot2", "tidyverse"))
Running the AnalysisPython Implementation: Open 01_Source_Code/Python/PyCode_Stat.ipynb in Jupyter Notebook.R Implementation: Run the following in RStudio:Rrmarkdown::render('01_Source_Code/R_Code/Team12Code.Rmd')
📊 MethodologyDataSource: US City Temperature DatasetVariables: Temperature readings, temporal features, city locationsFrequency: DailyApproachesARIMA ModelingStationarity testing (ADF, KPSS tests)ACF/PACF analysis for order selection ($p, d, q$)Parameter optimization and diagnostic checkingLSTM Neural NetworkSequence-to-sequence architectureMultiple layers with dropout regularizationTime series windowing and normalization📈 Key Findings[!IMPORTANT][Add specific results from your analysis here - e.g., "LSTM showed a 15% improvement in RMSE over ARIMA for volatile coastal cities."]👥 Team Members & ContributionsMemberRoleContributionsHarshalResearcherWeather forecasting research, meteorological analysisMrudulaML EngineerCNN-LSTM hybrid approaches, Bayesian methodsSidhhiLead AnalystARIMA comparative analysis, literature review📄 License & NotesThis project is submitted as coursework for the University at Buffalo.Project Status: Complete ✓Last Updated: December 2024
