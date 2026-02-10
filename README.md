🧠 Machine Learning Models Used

The following classification models are implemented and evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Naive Bayes

📈 Evaluation Metrics Used

Each model is evaluated using multiple criteria:

Accuracy

Precision

Recall

F1 Score

These metrics are used as input for the TOPSIS method.

🧮 What is TOPSIS?

TOPSIS is a mathematical method used to rank alternatives based on their distance from:

Ideal Best Solution (highest performance)

Ideal Worst Solution (lowest performance)

The best model is the one closest to the ideal solution and farthest from the worst solution.

⚙️ Workflow

The project follows these steps:

Load and preprocess text data

Convert text into numerical form using vectorization

Train multiple Machine Learning models

Evaluate models using classification metrics

Apply TOPSIS algorithm

Rank models based on TOPSIS score

🛠️ Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib

TOPSIS Algorithm

📂 Project Structure
text_classification_topsis.ipynb
README.md
