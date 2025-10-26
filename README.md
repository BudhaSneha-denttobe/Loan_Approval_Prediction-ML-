# Loan_Approval_Prediction-ML-
A machine learning project that predicts whether a loan application will be approved or rejected based on applicant data such as income, credit score, loan amount, and other financial details. The model helps banks and financial institutions make faster and data-driven lending decisions.
Process / Methodology

Data Collection & Understanding

Gathered historical loan application data.

Columns include applicant details, financial information, and loan approval status.

Explored dataset to handle missing values, categorical variables, and outliers.

Data Preprocessing

Missing values were filled using mean, median, or mode depending on the column type.

Categorical variables were encoded using Label Encoding / One-Hot Encoding.

Features were scaled if required for algorithms like SVM.

Model Selection
Multiple machine learning algorithms were trained and evaluated:

Logistic Regression – A baseline model for binary classification.

Accuracy: 0.905

Decision Tree Classifier – Captures non-linear relationships in data.

Accuracy: 0.978

Support Vector Machine (SVM) – Finds the optimal decision boundary for classification.

Accuracy: 0.917

Model Evaluation

Models were evaluated using accuracy score and optionally confusion matrix, precision, recall, and F1-score.

Decision Tree gave the highest accuracy, indicating strong performance on the dataset.

Prediction

After training, the model can take new applicant data as input and predict loan approval status.

Supports real-time prediction if integrated with a frontend (like a web app).

Technologies Used

Python – Core programming language

Pandas & NumPy – Data manipulation

Scikit-learn – Machine learning models and evaluation

Joblib / Pickle – Saving trained models for later use
