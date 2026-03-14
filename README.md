# Explainable Hybrid Quantum–Classical Machine Learning for Anomaly Detection

This project investigates the use of **hybrid quantum–classical machine learning** for anomaly detection under realistic **Noisy Intermediate-Scale Quantum (NISQ)** constraints. The study evaluates classical, quantum, and hybrid models using the **NSL-KDD intrusion detection dataset**, while integrating **Explainable Artificial Intelligence (XAI)** techniques to improve model transparency and interpretability.

---

## Models Implemented

* **Classical Machine Learning Baseline**
  Random Forest classifier used as a strong classical anomaly detection model.

* **Quantum Machine Learning Model**
  Variational Quantum Classifier (VQC) implemented using Qiskit.

* **Hybrid Quantum–Classical Model**
  Combines predictions from classical and quantum models using a meta-classifier.

* **Explainable AI (XAI)**

  * SHAP explanations for the classical model
  * Sensitivity analysis for the quantum model
  * Feature importance analysis for the hybrid model

---

## Key Results

The hybrid model achieved the **best overall anomaly detection performance** by combining classical model stability with quantum feature representation.

| Model                    | Accuracy   | ROC-AUC    | PR-AUC     |
| ------------------------ | ---------- | ---------- | ---------- |
| Classical Random Forest  | 0.7649     | 0.9619     | 0.9645     |
| Quantum VQC              | 0.6640     | 0.7400     | 0.7486     |
| Hybrid Quantum–Classical | **0.8700** | **0.9568** | **0.9503** |

Overall, the hybrid model improved classification accuracy by **approximately 10% compared to the classical baseline**, while maintaining strong ROC and precision–recall performance.

---

## Dataset

This study uses the **NSL-KDD Intrusion Detection Dataset**, a widely used benchmark for evaluating anomaly detection systems in network security research.

---

## Technologies Used

* Python
* Scikit-learn
* Qiskit
* SHAP
* Google Colab / Jupyter Notebook

---

## Repository Contents

* `Hybrid_Quantum_ML.ipynb` – Full project implementation
* `model1_outputs.zip` – Classical model outputs
* `model2_outputs.zip` – Quantum model outputs
* `model3_outputs.zip` – Hybrid model outputs

---

## Dissertation

This repository contains the implementation used for the final year dissertation:

**Explainable Hybrid Quantum–Classical Machine Learning for Anomaly Detection**

Canterbury Christ Church University – BSc Computer Science
