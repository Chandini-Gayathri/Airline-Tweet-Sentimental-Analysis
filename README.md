# ✈️ Airline-Tweet-Sentimental-Analysis
Sentiment analysis of US airline tweets using NLP and an LSTM deep learning models to classify customer feedback as positive or negative or neutral.


## Overview  

This repository contains a **sentiment analysis project on US airline tweets** using Natural Language Processing (NLP) techniques and an LSTM-based deep learning approach implemented in Python.  

The goal of the project is to automatically classify customer tweets as **Positive** or **Negative**, enabling airlines to better understand public sentiment toward their services. 

Rather than manual labeling of thousands of tweets, the pipeline processes raw text data, transforms it into numerical representations, and applies a neural network to learn patterns associated with sentiment.

---

## 🎯 Objective  

The project aims to:  

- Automate sentiment classification of airline-related tweets  
- Demonstrate an end-to-end NLP workflow  
- Apply deep learning (LSTM) to text data  

---

## 📊 Dataset  

The analysis is based on a publicly available **Twitter US Airlines Sentiment Dataset**, which contains:  

- **14,640 tweets** collected in February 2015  
- Tweets related to major US airlines  
- Three sentiment labels: **Positive, Negative, Neutral**  

For this study, only **Positive and Negative** tweets were used to build a binary classifier.


## Methodology 
The implemented workflow includes:

1. **Data preprocessing**
   - Filtering out neutral tweets  
   - Extracting tweet text and labels  

2. **Text processing**
   - Tokenization of words  
   - Converting text into numerical sequences  
   - Padding sequences to a fixed length  

3. **Learning approach**
   - Use of an **LSTM-based neural network** to capture contextual relationships in text  
   - Training the model on labeled tweet data  

4. **Evaluation**
   - Monitoring training and validation accuracy/loss  
   - Visualizing performance through plots  

5. **Prediction**
   - A helper function to classify sentiment for new input sentences.

---

## 🛠️ Technologies Used  

- **Python**  
- **Pandas**  
- **TensorFlow / Keras**  
- **LSTM (sequence modeling)**  
- **Basic NLP techniques (tokenization, padding)**  
- **Matplotlib (for visualizations)**  

---
