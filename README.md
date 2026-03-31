# 🚢 AI-Driven Supply Chain Disruption Prediction

This project demonstrates how AI can be applied to predict and manage disruption risk in global logistics systems under real-world uncertainty.

---

## 🌍 Overview

Machine learning project predicting shipment disruption risk using supply chain data, with feature importance analysis and decision-support recommendations for logistics planning.

---

## 🎯 Objective

- Predict shipment delay risk  
- Identify key drivers of disruption  
- Support proactive logistics decision-making  

---

## ⚙️ Methodology

- Data preprocessing and feature selection  
- Logistic Regression and Random Forest models  
- Evaluation using ROC-AUC and classification metrics  
- Feature importance analysis  
- Decision-support logic for operational actions
- Dataset available on Kaggle: DataCo Smart Supply Chain Dataset (Link: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis?resource=download)

---

## 📊 Results

| Model | ROC-AUC |
|------|--------|
| Logistic Regression | 0.726 |
| Random Forest | 0.730 |

Both models achieved similar performance, indicating stable structural drivers of disruption risk.

---

## ⚠️ Key Design Choice

The model was intentionally restricted to **pre-shipment variables** to avoid data leakage, ensuring realistic predictions aligned with real-world logistics decision-making.

---

## 🧠 Decision Support

- High risk → reroute or expedite shipment  
- Moderate risk → monitor and prepare contingency  
- Low risk → proceed as planned  

---

## 🛠️ Tools

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

---

## 🌐 Relevance

This project reflects my interest in applying AI to global systems such as logistics, supply chains, and large-scale operational environments under uncertainty.
