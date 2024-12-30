# Fraud Detection with Streaming and Batch Processing

This project demonstrates a machine learning pipeline for fraud detection using a Random Forest Classifier with Apache Spark. The pipeline processes both batch and streaming data, applies transformations, and evaluates the model’s performance.

**Overview**

Financial fraud detection is a critical application in modern financial systems. This project processes a synthetic dataset of financial transactions and builds a scalable solution to identify fraudulent activities. The project includes:

Data Preprocessing: Handling missing values, normalizing numerical features, and converting data types for compatibility.

Feature Engineering: Scaling features and selecting the most relevant ones.

Machine Learning Model: Training and evaluating a Random Forest Classifier.

Streaming Pipeline: Simulating real-time fraud detection with Spark’s structured streaming.

Visualizations: Analyzing model performance with ROC curve, feature importance, and other metrics.

**Technologies Used**

Apache Spark: For distributed data processing and machine learning.

Databricks Community Edition: For cluster setup and notebook execution.

PySpark: For data processing and model training.

Matplotlib and Seaborn: For visualizations.

Pandas and NumPy: For data manipulation and analysis.

**Usage**

1. Clone the Repository

git clone https://github.com/yourusername/fraud-detection-with-spark.git
cd fraud-detection-with-spark

2. Requirements

Ensure you have the following installed:

Databricks Community Edition account.

Python libraries: pyspark, matplotlib, seaborn, pandas, numpy, sklearn.

Install additional dependencies if needed:

pip install pyspark matplotlib seaborn pandas numpy scikit-learn

3. Run the Notebooks

Open Databricks and upload the provided notebooks.

Attach a cluster to the notebooks.

Execute the cells step-by-step.


**File Structure**

Fraud_Detection_Streaming.ipynb: Notebook for streaming pipeline implementation.

2024-12-28 - Fraud detection dataset.ipynb: Dataset Permanant table conversion in Databricks Workspace
