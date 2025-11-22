#Network Intrusion Detection System (NIDS) using Machine Learning
  
It detects network intrusions (attacks) using Machine Learning based on the NSL-KDD dataset.

## Project Overview

The goal of this project is to classify network connections as:
- **Normal**
- **Attack**

We use:
- **Random Forest Classifier**
- **Preprocessing Pipeline** (StandardScaler + OneHotEncoder)
- **Train/Test split**
- **Evaluation with Classification Report & Confusion Matrix**


## Folder Structure
ai-nids
-intrusion_detection.ipynb
-README.md
-models/
--best_model.pkl
--preprocessor.pkl
-screenshots
-report


## Dataset
Used dataset: **NSL-KDD** (network intrusion dataset)  
Uploaded manually in Colab.


## Machine Learning Workflow

1. Load dataset  
2. Clean data  
3. Preprocess features  
4. Train model (Random Forest)  
5. Evaluate  
6. Save model  
7. Predict on new data  


## How to Run (Google Colab)

1. Open `intrusion_detection.ipynb` in Google Colab  
2. Upload `nsl_kdd.csv`  
3. Run cells from top to bottom  
4. Model file will be saved as:
   - `best_model.pkl`
   - `preprocessor.pkl`


## Requirements
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib



## Screenshots
All screenshots are attached.


