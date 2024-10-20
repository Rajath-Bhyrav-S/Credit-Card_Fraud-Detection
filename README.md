# Credit Card Fraud Detection

## Project Overview
This project focuses on detecting credit card fraud using various machine learning techniques. It was developed as part of the IBM Z and Shooting Star Foundation Datathon.

## Dataset
The project uses the "creditcard.csv" dataset, which contains credit card transactions, including both legitimate and fraudulent cases.

## Features
- Time
- V1-V28 (anonymized features)
- Amount
- Class (0 for valid transactions, 1 for fraudulent transactions)

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Imbalanced-learn (for SMOTE)

## Models Implemented
1. Isolation Forest
2. Local Outlier Factor
3. Autoencoder (Neural Network)
4. Logistic Regression
5. K-Nearest Neighbors (KNN)
6. Histogram-based Gradient Boosting Classifier

## Key Steps
1. Data Loading and Exploration
2. Data Preprocessing (handling missing values, scaling)
3. Exploratory Data Analysis (EDA)
4. Handling Class Imbalance (using SMOTE)
5. Model Training and Evaluation
6. Performance Visualization (ROC curves, confusion matrices)

## Results
- Achieved up to 99.91% accuracy in fraud detection
- Detailed performance metrics for each model, including precision, recall, and F1-score

## Visualizations
- Histograms of feature distributions
- Correlation heatmap
- ROC curves
- Confusion matrices

## Future Improvements
- Feature engineering to create more discriminative features
- Ensemble methods combining multiple models
- Deep learning approaches (e.g., LSTM for sequence modeling)
- Real-time fraud detection system implementation

## How to Run
1. Clone this repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook or Python scripts

## Contributors
- Rajath Bhyrav S
- Nithish C
- Disha  S kashipati
- Chinmayi H E
- Muni Raju BR

## Acknowledgments
Special thanks to IBM Z and the Shooting Star Foundation for organizing this Datathon and providing the opportunity to work on this challenging problem.
