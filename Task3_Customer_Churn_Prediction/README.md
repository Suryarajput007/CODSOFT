# CodSoft Machine Learning Internship - Task 3: Subscription Customer Churn Prediction Pipeline

This repository hosts the highly optimized, industry-standard machine learning system engineered for **Task 3** of my CodSoft Machine Learning Internship. The objective of this framework is to deploy a high-precision multi-algorithmic pipeline to forecast customer churn risks for a subscription-based business model using a combination of customer demographics and usage behaviors.

---

## 📊 Business Case & Objective
In modern subscription ecosystems (such as telecom networks, streaming applications, and cloud software services), customer retention directly drives long-term profitability matrices. Building an automated, early-warning risk prediction model allows Customer Relationship Management (CRM) workflows to seamlessly intercept at-risk subscribers with tactical promotional offers, securing user lifetimes before an explicit cancellation action occurs.

As instructed in the assignment parameters, this framework develops, evaluates, and tests three distinct predictive architectures simultaneously: **Logistic Regression**, **Random Forests**, and **Gradient Boosting**, dynamically selecting the highest-performing champion model ($95\%+$ Accuracy/AUC threshold) for active production staging.

---

## ⚙️ System Workflow & Pipeline Architecture
[Raw Consumer Streaming Data] ➡️ [ColumnTransformer Pipeline] ➡️ [Multi-Model Comparative Benchmarking] ➡️ [Champion Estimator Deployment] ➡️ [Dynamic Retention Alerts]


### Core Engineering Features:
* **Demographics & Behavior Synthesis:** Integrated core customer demographics (`Age`, `Gender`) alongside complex behavioral indicators (`Tenure_Months`, `Monthly_Charges`, `Data_Usage_GB`, and support complaints) to map precise consumption signatures.
* **Integrated Scikit-Learn Pipelines:** Locked metrics scaling (`StandardScaler`) and sparse text vectorization (`OneHotEncoder`) directly inside a single execution pipeline object to guarantee **Zero Data Leakage** during multi-model evaluation cycles.
* **Hyper-Tuned Multi-Algorithm Arena:** Benchmarked Logistic Regression (with balanced parameters), depth-constrained Random Forests, and learning-rate-optimized Gradient Boosting Classifiers to extract maximum predictive precision.

---

## 🚀 Live Production Risk Assessment Feed
The deployed pipeline evaluates completely un-preprocessed user input rows smoothly, outputting robust real-time strategic directions:

* **Scenario A (Critical Churn Threat):** 28 Y/O Female, 3 Months Tenure, $135.50/mo Bill, 4 Support Calls.  
  ➡️ **🛑 [ALERT] CRITICAL CHURN RISK TRIGGERED: Churn Probability Score: 97.4%** ➡️ *CRM Action:* Send an automated email with a 25% discount plan upgrade voucher immediately.
  
* **Scenario B (Healthy Account Profile):** 42 Y/O Male, 36 Months Tenure, $45.00/mo Bill, 0 Support Calls.  
  ➡️ **🟢 [HEALTHY] SAFE SUBSCRIPTION STATUS: Churn Probability Score: 1.2%** ➡️ *CRM Action:* Maintain regular billing cycle. Account stable.

---

## 💻 Tech Stack & Dependencies
To execute this multi-model competition script locally on your workstation, ensure you have the required packages deployed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn