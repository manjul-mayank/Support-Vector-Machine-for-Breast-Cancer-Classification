## 🧬 Support Vector Machine for Breast Cancer Classification
This repository contains a machine learning project that demonstrates how to use a Support Vector Machine (SVM) classifier to predict whether a tumor is benign or malignant, using the well-known Breast Cancer Wisconsin (Diagnostic) Dataset.
## 📌 Project Overview
Breast cancer is one of the most common and deadly cancers among women. Early detection through machine learning can significantly improve diagnostic accuracy. In this project, an SVM model is implemented for binary classification of tumor types based on various input features derived from digitized images of a breast mass.

## 🛠️ Technologies Used
- Python 🐍

- Jupyter Notebook 📓

- scikit-learn 🧪

- pandas 📊

- seaborn & matplotlib 📈
## 📂 Dataset
The Breast Cancer Wisconsin (Diagnostic) dataset is directly imported using sklearn.datasets.load_breast_cancer().

- Total Instances: 569

- Features: 30 numeric features computed from digitized images

- Classes: 2 (Benign = 1, Malignant = 0)
## 📉 Workflow
- Data Loading and Exploration
  - Understanding feature distributions
  - Checking for missing values
- Data Preprocessing
  - Feature scaling using StandardScaler
  - Splitting dataset into training and test sets
- Model Training
  - Training a Support Vector Machine with linear kernel
  - Hyperparameter tuning using GridSearchCV
- Evaluation
  - Accuracy, confusion matrix, and classification report
  - ROC-AUC curve visualization
## ✅ Results
- Model Accuracy: ~97% (depending on train-test split and tuning)
- High precision and recall for both classes
- Well-separated decision boundary (visualized in 2D projections)

## 📊 Visuals
- The notebook includes several helpful visualizations:
- Correlation heatmap of features
- Confusion matrix
- ROC-AUC curve
- Distribution plots for target classes
## 📚 References
- UCI Breast Cancer Wisconsin Dataset
- scikit-learn Documentation
## 💡 Future Work
- Try different kernels (RBF, polynomial)
- Add cross-validation and ensemble methods
- Implement deep learning approach for comparison
## 🤝 Contributing
Feel free to fork this repo, open issues, or submit pull requests for improvements or feature additions.
## 📄 License
This project is open-source and available under the MIT License.
## Author
- Manjul Mayank
