# Spam Email Detection Using CNN and MLP

## Overview
This project uses Deep Learning models to classify emails as Spam or Ham (Not Spam).  
The models implemented are:
- Convolutional Neural Network (CNN)
- Multilayer Perceptron (MLP)

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training
- Performance evaluation

---

## Dataset
Dataset used:
Spam Mails Dataset from Kaggle

Source:
https://www.kaggle.com/datasets/venky73/spam-mails-dataset

### Dataset Features
- Email text/content
- Label:
  - Spam
  - Ham

---

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK

---

## Kernel Version
- 3.11.4

## Data Preprocessing
The following preprocessing steps were performed:
- Lowercasing text
- Removing punctuation
- Removing stopwords
- Tokenization
- Text vectorization/padding

---

## Models

### CNN
The CNN model uses:
- Embedding Layer
- Convolution1D
- MaxPooling
- Dense Layers

### MLP
The MLP model uses:
- Fully Connected Dense Layers
- ReLU Activation
- Dropout Regularization

---

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## How to Run

### 1. Clone Repository
git clone https://github.com/yourusername/yourrepository.git

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run Notebook
Open Jupyter Notebook or Google Colab and run the notebook.
