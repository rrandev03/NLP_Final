# Social Media Sentiment Analysis of Electric Vehicles: Leveraging BERT, RoBERTa, and VADER
---

## Authors

- **Loo Si Min (Lucy)**  
- **Rishika Randev**  
- **Eric Ortega Rodriguez**  
- **Fan Xu**
---
## Overview

This repository explores public sentiment regarding electric vehicles (EVs) on Twitter using advanced NLP tools. The study focuses on how sentiment shifted between January 2020 and December 2023, influenced by significant policies like the Biden administration’s "Build Back Better" agenda.

In this project, we used transformer-based models (BERT and RoBERTa) and VADER to classify tweets into positive, neutral, and negative sentiments. The analysis examines the relationship between public sentiment, government policies, and the broader adoption of sustainable transportation.

---

## Contents

### 1. **BERT & RoBERTa Analysis Notebook**
- BERT and RoBERTa models for sentiment classification using labeled real and synthetic tweet data.

### 2. **VADER Sentiment Analysis Notebook**
- Applies VADER to classify sentiment and establish a comparison containing visualizations.

### 3. **Dataset Details**
- **Real Data**: 83,591 tweets collected via Octoparse, filtered for relevance to electric vehicles.
- **Synthetic Data**: 400 tweets generated by artificial intelligence, labeled with positive, neutral, or negative sentiments. 

---

## Features

- **Sentiment Analysis**: Classifies tweets into positive, neutral, and negative categories.
- **Time Trend Analysis**: Examines sentiment evolution over time in response to key events and policies
- **Data Preprocessing**: Includes text cleaning, tokenization, and normalization
- **Performance Comparison**: Evaluate and compare the performance of BERT, RoBERTa, and VADER

---

## Dependencies and Installation

   ```bash
   pip install vaderSentiment
   pip install pandas
   pip install numpy
   pip install matplotlib
   pip install scikit-learn
   pip install transformers
   pip install tensorflow
   pip install emoji
   pip install nltk
   pip install seaborn
   pip install torch
   ```




