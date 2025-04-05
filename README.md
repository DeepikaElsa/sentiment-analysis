# sentiment-analysis
This project is a Sentiment Analysis tool built using Python and popular NLP libraries. It processes text data, cleans it, and classifies sentiments (e.g., positive, negative, neutral) using machine learning models. Ideal for analyzing user reviews, social media comments, or customer feedback.

# 🧠 GoEmotions Text Preprocessing with BERT Embeddings

This repository contains a Jupyter Notebook focused on advanced text preprocessing and feature extraction using BERT for the **GoEmotions** dataset by Google.

## 📦 Dataset

- **GoEmotions** by Google: A manually annotated dataset of 58k+ Reddit comments labeled across 27 emotion categories.
- [Dataset Source](https://github.com/google-research/goemotions)

## 🧹 Preprocessing Steps

The following preprocessing techniques are applied to clean and structure the data:

- Tokenization
- Stop Word Removal
- Stemming (using NLTK’s PorterStemmer)
- Lemmatization (using spaCy)
- Handling missing values
- Addressing class imbalance (if any)

## 🔍 Feature Extraction

- **BERT Embeddings**: High-quality sentence embeddings are extracted using BERT to represent each text sample numerically.
- No additional machine learning model is used in this phase.

## 📊 Visualizations

To gain insights from the text, the notebook includes:

- Word clouds for the most common words
- Bar charts showing emotion distribution
- Histograms highlighting word/token frequencies

## 📁 Deliverables

- ✅ Preprocessed dataset (tokenized, cleaned, and embedded)
- ✅ Feature extraction using BERT
- ✅ Visual insights into the dataset
- ✅ Summary of preprocessing techniques

## 🛠️ Technologies Used

- Python
- pandas, numpy
- NLTK, spaCy
- transformers (Hugging Face BERT)
- matplotlib, seaborn, wordcloud

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/DeepikaElsa/sentiment-analysis.git
   cd sentiment-analysis
2. Install dependencies
    ```bash
   pip install -r requirements.txt
3. Run the notebook
   ```bash
   jupyter notebook sentiment_analysis.ipynb




 

