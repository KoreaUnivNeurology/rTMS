# rTMS Analysis in Drug-Resistant Epilepsy

This repository contains code for analyzing EEG-based functional connectivity changes and machine learning modeling from the study:  
**“Network-based effects of transcranial magnetic stimulation in drug-resistant epilepsy: a randomized, single-blind, crossover trial”**

## 🚀 **Main Objectives**
- Analyze pre- and post-rTMS EEG data to assess changes in brain functional connectivity using weighted phase lag index (**wPLI**) across multiple frequency bands.
- Perform correlation analysis between EEG connectivity changes and clinical outcomes (e.g., seizure frequency).
- Develop machine learning models (Logistic Regression) to classify rTMS responders and predict optimal stimulation dose.

## 🔍 **Key Features**
- **Seizure Frequency Comparison**: Visual comparison of seizure frequency pre- and post-stimulation.
- **EEG Connectivity Visualization**: Display inter-electrode and ROI-based wPLI difference matrices.
- **Correlation Analysis**: Explore statistical relationships between connectivity changes and clinical outcomes.
- **Machine Learning**: Logistic regression models for responder classification and dose prediction, with ROC curve evaluation.

## 📂 **Repository Contents**
- **`rTMS_Analysis.ipynb`**: Jupyter Notebook containing the full analysis pipeline: data preprocessing, connectivity analysis, correlation analysis, machine learning modeling, and visualization.

## ⚠️ **Important Notes**
- The current code **does not include raw EEG data**, which is required to reproduce the analysis.

## 📚 **Reference**
Kim H, et al. *Network-based effects of transcranial magnetic stimulation in drug-resistant epilepsy: a randomized, single-blind, crossover trial*.
