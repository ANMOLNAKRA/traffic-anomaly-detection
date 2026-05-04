# Traffic Data Analysis & Anomaly Detection

##  Overview

This project focuses on analyzing traffic data to extract insights, detect anomalies, and build predictive models. It combines **data preprocessing, classification, regression, and anomaly detection** into a single pipeline.


The goal is to simulate real-world traffic monitoring systems where identifying unusual patterns is critical for safety and optimization.


---

##  Tech Stack

* **Python**
* **Pandas, NumPy** – Data processing
* **Scikit-learn** – ML models
* **Matplotlib / Seaborn** – Visualization
* **Joblib** – Model persistence

---

##  Features

*  Data preprocessing and cleaning pipeline
*  Classification models (SVM, Decision Tree, Random Forest)
*  Confusion matrix visualization
*  Anomaly detection on traffic data
*  Regression analysis for trend prediction
*  Modular and reusable code structure

---

##  Project Structure

```
.
├── prj.ipynb                      # Main notebook (all workflows)
├── input_data.csv                # Raw dataset
├── processed_traffic_data.csv    # Cleaned dataset
├── anomaly_results.csv           # Detected anomalies
```

---

##  How It Works

### 1. Data Preprocessing

* Loads raw traffic data
* Cleans missing/invalid values
* Normalizes features
* Saves processed dataset

### 2. Classification

* Splits data into train/test
* Trains multiple models:

  * SVM
  * Decision Tree
  * Random Forest
* Evaluates performance using confusion matrices

### 3. Anomaly Detection

* Samples dataset
* Identifies unusual traffic patterns
* Outputs anomalies to CSV

### 4. Regression Analysis

* Performs regression on processed data
* Helps understand trends and relationships

---

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/traffic-analysis.git
cd traffic-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib joblib
```

### 3. Run the notebook

```bash
jupyter notebook prj.ipynb
```

---

##  Output

* Processed dataset (`processed_traffic_data.csv`)
* Anomaly results (`anomaly_results.csv`)
* Model evaluation (confusion matrices)

---

##  Future Improvements

*  Add deep learning models (LSTM for time-series)
*  Deploy as a web dashboard
*  Real-time traffic data integration
*  Hyperparameter tuning for better accuracy

---

##  Use Cases

* Smart city traffic monitoring
* Road safety analysis
* Congestion prediction
* Intelligent transport systems

---

## 👨‍💻 Author

Anmol

---
