# Description

## Video Demonstration
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wYlM6hy2Kg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Description
- Created a normalized database (3NF) and used SQL join statements to fetch data into Pandas DataFrames
- Explored data using yprofile and correlation matrix, identifying necessary data cleanup tasks
- Performed stratified train/test split based on data analysis
- Developed preprocessing pipelines including StandardScaler, MinMaxScaler, LogTransformation, and OneHotEncoding
- Experimented with multiple classifiers: LogisticRegression, RidgeClassifier, RandomForestClassifier, and XGBClassifier
- Conducted feature engineering, attribute combination, and selection using Correlation Threshold, Feature Importance, and Variance Threshold
- Applied PCA for dimensionality reduction, creating a scree plot to select optimal components
- Designed and executed two custom experiments to further optimize model performance
- Logged all experiment results in MLFlow on DagsHub, creating F1-score plots for model comparison
- Saved the final model using joblib and created a FastAPI application to serve it
- Containerized the FastAPI application using Docker, pushed to Docker Hub, and deployed to a cloud platform
- Developed a Streamlit app for real-time interaction with the deployed model

## Links to Project: 
- [MLFlow/DagsHub Experiments](https://dagshub.com/singhvarunnn789/EAS503.mlflow/#/experiments/3/runs/39cec5d898fe4322a96519de965399a9)
- [Docker Hub Container](https://hub.docker.com/repository/docker/singhvarunnn789/heart-disease-predictor/general)
- [Deployed Model](https://heart-disease-predictor-latest.onrender.com/)
- [Streamlit App](https://apprender-ghfqkbcthxbxrfdgcomw23.streamlit.app/)