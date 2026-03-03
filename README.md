# Bitcoin Heist Classification (Spark ML)
This project performs large volume classification and clustering on the Bitcoin Heist dataset using PySpark and Spark MLlib.

#Project Structure
7006ml_bigdata/
│
├── notebooks/
│   ├── 1_data_ingestion.ipynb
│   ├── 2_feature_engineering.ipynb
│   ├── 3_model_training.ipynb
│   └── 4_evaluation.ipynb
│
├── scripts/
├── config/
├── data/
│   ├── schemas/
│   └── samples/
│
├── tableau/
├── tests/
│
├── README.md
├── environment.yml
├── Dockerfile
└── .gitignore

#Dataset
Dataset name: "BitcoinHeistData.csv"
The dataset is NOT included in this repository due to GitHub file size limitations.

#To Run This Project:
1. Download "BitcoinHeistData.csv" dataset from UCI ML Repository: https://archive.ics.uci.edu/dataset/526/bitcoinheistransomwareaddressdataset.
2. Run notebooks in the following order:
   a. 1_data_ingestion.ipynb
   b. 2_feature_engineering.ipynb
   c. 3_model_training.ipynb
   d. 4_evaluation.ipynb

#Libraries adapted in this project
- PySpark
- Spark MLlib
- Scikit-learn
- Matplotlib
- NumPy
- Pandas

#Description
This project demonstrates:
- Distributed data processing using Apache Spark
- Feature engineering and dataset partitioning
- Supervised models (Logistic Regression, Decision Tree, Random Forest)
- Unsupervised learning (KMeans)
- Model evaluation using RMSE, MAE, R2, ROC, Precision-Recall
- Visualization of learning curves and feature importance

#Notes
- Large files are excluded via ".gitignore"
- Parquet outputs are not tracked
- This project can be run locally or in Google Colab
