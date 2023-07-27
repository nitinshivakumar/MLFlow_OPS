## Testing MLflow with DVC and Dagshub on Wine Quality Data

MLFLOW_TRACKING_URI=https://dagshub.com/snitin128/MLFlow_OPS.mlflow \
MLFLOW_TRACKING_USERNAME=snitin128 \
MLFLOW_TRACKING_PASSWORD=692c55f750225658725210498219de05af91e3c1 \
python script.py
 
 ----------------------------------------------------------------
### Project Overview:
The goal of this project is to demonstrate the integration of MLflow, DVC (Data Version Control), and Dagshub to manage and track machine learning experiments using the Wine Quality dataset. MLflow will be used to track and visualize experiments, DVC will handle data versioning and pipeline management, and Dagshub will provide a collaborative platform for sharing and discussing results.

----------------------------------------------------------------
### Dataset:
The Wine Quality dataset consists of red and white variants of the Portuguese "Vinho Verde" wine. It contains various physicochemical properties and quality ratings for each variant. The dataset will be used for building a regression model to predict wine quality based on the input features.

----------------------------------------------------------------
### Project Steps:

1. Data Preprocessing:
Download the Wine Quality dataset, combine the red and white variants if needed, and perform necessary data preprocessing steps.
Split the dataset into training and testing sets.

2. Model Training and Tracking:
Implement a regression model using a machine learning library like Scikit-learn or TensorFlow.
Utilize MLflow to track model hyperparameters, metrics, and artifacts (e.g., model files) during training.
Organize experiments using MLflow runs, and compare different model configurations.

3. Experiment Versioning with DVC:
Initialize a DVC repository to manage data versioning and experiment pipelines.
Use DVC to track data changes and create a reproducible pipeline for data preprocessing and model training.
Connect DVC with MLflow to store and link artifacts from each run.

4. Integration with Dagshub:
Create a project repository on Dagshub to collaborate and share the project's progress with others.
Link the DVC repository to Dagshub to automatically track changes in the data and experiments.
Push the code, data, and MLflow artifacts to the Dagshub repository to share with the community.

5. Experiment Reproducibility and Sharing:
Use DVC and MLflow in conjunction to ensure experiment reproducibility.
Share the repository link with colleagues or the community to allow them to reproduce experiments and results.