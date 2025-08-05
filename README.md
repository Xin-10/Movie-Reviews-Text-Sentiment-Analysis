# Movie-Reviews-Text-Sentiment-Analysis

This project focuses on building a binary text classification system to predict the sentiment (positive or negative) of movie reviews from the IMDb dataset. 

## Project Files

- `GoogleNews-vectors-negative300-SLIM.bin`: Required for Word2Vec embedding. [https://github.com/eyaler/word2vec-slim](https://github.com/eyaler/word2vec-slim)
- The dataset used in this project is the [Large Movie Review Dataset v1.0](https://ai.stanford.edu/~amaas/data/sentiment/) published by Stanford University.  

## Installation & Execution

This project runs on **Python 3.12+** and requires several dependencies listed in `requirements.txt`.

### 1. Clone the repository
```bash
git clone https://github.com/Xin-10/Movie-Reviews-Text-Sentiment-Analysis.git
cd Movie-Reviews-Text-Sentiment-Analysis
```

## 2. Create a virtual environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate      # Windows
```

## 3. Install dependencies
```bash
pip install -r requirements.txt
```

## 4. Launch Notebook and Run
```bash
jupyter notebook
Then open and run A3_IMDB_sentiment_classification.ipynb.
```
