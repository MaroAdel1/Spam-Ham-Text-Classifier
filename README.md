# Spam/Ham Text Classifier

## Overview
This project is an end-to-end NLP solution that classifies SMS messages as **Spam** or **Ham (Not Spam)** using deep learning models.  
It focuses on building RNN and GRU architectures to achieve high accuracy in text classification tasks.

---

## Corpus Description
The dataset contains over 5,000 SMS messages labeled as *spam* or *ham (not spam)*.  
Each row has a message and its label. The data is used to train and test the model to detect whether a message is spam or not.  
It provides a good mix of real messages and unwanted promotional texts.

Dataset Source: [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

---

## Data Preprocessing
- Removed special characters, numbers, and extra spaces  
- Converted text to lowercase  
- Tokenized text and padded sequences  
- Split data into training and testing sets  

---

## Model Architecture
- Embedding Layer for word representation  
- RNN and GRU layers for sequence learning  
- Dense layer with sigmoid activation for binary classification  

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy / Pandas  
- Matplotlib / Seaborn  
- NLTK  

---

## How to Run
1. Open the file `Spam.ipynb` in **Jupyter Notebook** or **Google Colab**  
2. Run all cells sequentially  
3. The notebook will preprocess data, train the model, and evaluate performance  

---

## Results
The GRU model achieved high accuracy and effective spam detection performance.  
The evaluation includes accuracy, precision, recall, and loss visualization during training.

---

## Author
Developed by **Maro Adel**  
