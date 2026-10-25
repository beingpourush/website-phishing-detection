# Website Phishing Detection Using Machine Learning

## 📌 Project Overview

This project uses machine learning classification algorithms to distinguish between legitimate and phishing websites using precomputed website features. Four classification models are trained and evaluated to compare their predictive performance.

## 📊 Dataset Information

- **Total samples:** 11,054
- **Input features:** 30
- **Test samples:** 2,211
- **Target labels:** `-1` and `1`
- **Problem type:** Supervised Machine Learning — Binary Classification

*Note: Verify the exact meaning of the target labels using the original dataset documentation.*

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Neural Network (MLP Classifier)

## 📈 Model Performance

| Model | Accuracy |
|---|---:|
| Random Forest | **97.42%** |
| Decision Tree | 96.88% |
| Neural Network (MLP) | 95.52% |
| Logistic Regression | 93.58% |

**Best-performing model:** Random Forest Classifier, with an accuracy of **97.42%**.


## ⚙️ Project Workflow

1. Load and inspect the phishing website dataset.
2. Separate the 30 input features from the target labels.
3. Split the dataset into training and testing sets.
4. Train four classification models.
5. Compare performance using accuracy, precision, recall, and F1-score.
6. Generate a classification report and confusion matrix.
7. Examine feature importance where supported by the model.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Google Colab

## 🚀 How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the dataset and configure its file path as expected by the notebook.
4. Run the notebook cells in order to train and evaluate the models.

## ⚠️ Limitations

- The notebook uses precomputed dataset features rather than extracting all 30 features directly from a newly entered URL.
- It does not include a complete website interface or a validated live URL detection system.
- Performance on this test set does not guarantee the same results on new, real-world websites.
- Dataset quality, feature definitions, and class-label interpretation affect the reliability of predictions.



## 👨‍💻 Project Summary

A machine learning classification project comparing four algorithms for website phishing detection using 30 precomputed features and 11,054 dataset samples. Random Forest achieved the highest test accuracy of **97.42%**, followed by Decision Tree at **96.88%**, Neural Network at **95.52%**, and Logistic Regression at **93.58%**.
