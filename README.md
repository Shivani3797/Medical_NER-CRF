# Custom Named Entity Recognition (NER) with Conditional Random Fields (CRF)

![Custom NER with CRF]("C:\Users\Pro\Downloads\nlp.jpg")


This repository contains a Jupyter Notebook that demonstrates a workflow for developing a custom Named Entity Recognition (NER) model using Conditional Random Fields (CRF). The notebook includes data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

---

## 📂 Notebook Contents

### 1. Problem Statement
- Overview of the objective: Identifying diseases and their associated treatments using custom NER techniques.

### 2. Setup
- Instructions for setting up the environment (e.g., Google Colab or local setup).
- Mounting Google Drive (if applicable) and importing necessary libraries.

### 3. Data Preprocessing
- Loading and inspecting training/testing datasets.
- Tokenizing sentences and labels.
- Combining tokens into sentences and corresponding label sequences.

### 4. Exploratory Data Analysis
- Frequency analysis of tokens with specific Part-of-Speech (PoS) tags (e.g., NOUN, PROPN).
- Contextual vs. independent PoS tag analysis to improve feature extraction.

### 5. Feature Extraction
- Engineering features for CRF from sentences, including contextual tagging.

### 6. Building the Model
- Training a CRF model with features extracted from training data.
- Using `sklearn-crfsuite` for implementation.

### 7. Evaluation
- Evaluating the CRF model using metrics such as F1-score.
- Displaying predictions for test data with actual vs. predicted labels.

### 8. Disease and Treatment Extraction
- Custom dictionary-based extraction of diseases and treatments from test data.
- Cleaning and formatting the results into a readable format (dataframe).

---

## ⚙️ How to Run

1. Clone the repository:
   
git clone https://github.com/username/repo-name.git

3. Install required dependencies:

pip install -r requirements.txt

3. Open the notebook and run cells sequentially:

jupyter notebook NER_CRF.ipynb

## 📊 Key Insights
Analyzed the impact of contextual PoS tagging in improving NER performance.
Extracted and structured diseases and their corresponding treatments into a clean format.

## 🛠 Libraries Used
Python
sklearn-crfsuite
pandas
collections
matplotlib

## 🖋️ Author
Shivani Bhatia
Passionate about machine learning and NLP.
GitHub | LinkedIn


