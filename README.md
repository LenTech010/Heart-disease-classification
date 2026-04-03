Heart Disease Classification: SVM Kernel Analysis
This project explores the use of Support Vector Machines (SVM) to predict heart disease. Rather than sticking to a single model, this analysis compares different SVM kernels to determine which mathematical boundary best fits the clinical data.

📌 Project Overview
Heart disease prediction is a non-linear problem. This notebook demonstrates the machine learning pipeline from data ingestion to model evaluation, specifically focusing on how different SVM Kernels (Linear, RBF, Poly) affect classification accuracy.

📊 Dataset
The analysis is performed on the heart (1).csv dataset, which includes 14 clinical features such as:

Age & Sex

Chest Pain Type (cp)

Cholesterol Levels (chol)

Maximum Heart Rate (thalach)

🛠️ Methodology
The project follows these standard Data Science steps:

Data Loading: Importing heart (1).csv via Pandas.

Preprocessing: Handling missing values and encoding categorical variables.

Feature Scaling: (Optional but recommended for SVM) Normalizing data for better kernel performance.

Model Comparison: * Linear Kernel: For simple, linearly separable data.

RBF (Radial Basis Function): For complex, non-linear boundaries.

Polynomial Kernel: To capture interactions between features.

🚀 How to Run
Clone the repo.

Upload heart (1).csv to your environment.

Run Heart_Disease_Prediction_SVM.ipynb.

📈 Evaluation Metrics
We evaluate the models using:

Accuracy Score: Percentage of total correct predictions.

F1-Score: The balance between Precision and Recall (crucial for medical diagnosis).
