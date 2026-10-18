# AI-Based QoE Optimization System

A Python pipeline that predicts and optimizes Quality of Experience (QoE) from network Quality of Service (QoS) metrics.

## Features
- Dataset upload and column configuration
- Exploratory data analysis
- Regression and classification models (Random Forest, Logistic Regression, SVM)
- Feature-importance analysis and PCA
- Anomaly detection with Isolation Forest
- A simulated QoE environment (`QoEEnvironment`) for optimization experiments

## Run
```bash
pip install scikit-learn pandas numpy matplotlib seaborn openpyxl
python finalaiproject.py
```
Written for Google Colab; the file-upload step expects a CSV/Excel dataset of QoS and QoE columns.
