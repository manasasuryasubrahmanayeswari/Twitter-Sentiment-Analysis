# Twitter Sentiment Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/Twitter-Sentiment-Analysis/blob/master/twitter_sentimentanalysis_project.ipynb)

## Overview
This project analyzes tweets to classify them as **Positive, Negative, or Neutral** using the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140) and Natural Language Processing (NLP) techniques.

The project demonstrates:
- Data collection from Kaggle
- Data preprocessing (cleaning, tokenization, stopword removal, stemming)
- Sentiment classification using **TextBlob/VADER/ML model**
- Data visualization with charts and word clouds
- Execution in **Google Colab**

---

## Features
- Dataset downloaded directly from **Kaggle API**
- Lightweight repository (dataset excluded to keep repo size manageable)
- Visualization of sentiment distribution
- Example predictions from tweets

---

## Dataset
- Uses the **Sentiment140 dataset** (1.6 million tweets).  
- Due to its size, the dataset is **not included** in the repository.

### Download Dataset in Colab
1. Get your Kaggle API token: [Kaggle Account Settings](https://www.kaggle.com/account)
2. Upload the `kaggle.json` file in Colab:
```python
from google.colab import files
files.upload()  # Upload kaggle.json

```

### How to Run

#### 1.Clone this repository:

git clone https://github.com/manasasuryasubrahmanayeswari/Twitter-Sentiment-Analysis.git
cd Twitter-Sentiment-Analysis


#### 2.Install dependencies:

pip install -r requirements.txt


#### 3.Run the notebook:

jupyter notebook twitter_sentimentanalysis_project.ipynb
