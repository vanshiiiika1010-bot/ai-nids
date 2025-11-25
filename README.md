#Network Intrusion Detection System (NIDS) using Machine Learning

It detects network intrusions (attacks) using Machine Learning based on the NSL-KDD dataset.

Project Overview
The goal of this project is to classify network connections as:

Normal
Attack
We use:

Random Forest Classifier
Preprocessing Pipeline (StandardScaler + OneHotEncoder)
Train/Test split
Evaluation with Classification Report & Confusion Matrix
Folder Structure
ai-nids -intrusion_detection.ipynb -README.md -models/ --best_model.pkl --preprocessor.pkl -screenshots -report

Dataset
Used dataset: NSL-KDD (network intrusion dataset)
Uploaded manually in Colab.

Machine Learning Workflow
Load dataset
Clean data
Preprocess features
Train model (Random Forest)
Evaluate
Save model
Predict on new data
Requirements
pandas numpy scikit-learn matplotlib seaborn joblib
