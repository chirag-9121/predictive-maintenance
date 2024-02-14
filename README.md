The project aimed at applying advanced unsupervised machine learning techniques for building a predictive maintenance framework. The objective was to detect anomalies and predict failures
in Metro Air Production Units (APUs) using analog and digital sensor data. Apart from this, it also focuses on identifying features that highly influence the occurrence of failures. 
The dataset used in this study can be found at https://archive.ics.uci.edu/dataset/791/metropt+3+dataset.

The below four models were applied to this dataset:
- Density-Based Spatial Clustering of Applications with Noise (DBSCAN)
- One-Class Support Vector Machine (OC-SVM)
- Sparse Autoencoder (SAE)
- Long Short-Term Memory (LSTM)

The SAE model displayed the best results and was further integrated with the Random Forest Classifier, thereby successfully identifying 99% of failures.
The code can be viewed [here](https://github.com/chirag-9121/predictive-maintenance/blob/main/maincode.ipynb).
