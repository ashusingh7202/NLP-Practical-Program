# NLP Lab Programs — CO1 & CO2

This repository contains practical programs for **Natural Language Processing (NLP)** using Python and popular NLP libraries. It covers fundamental text-processing techniques, word representations, text classification, sentiment analysis, topic modeling, information extraction, and information retrieval.

## 📚 List of Programs

### CO1 — NLP Fundamentals

| S. No. | Practical Program |
|:---:|---|
| 1 | Tokenization of Sentences and Words using NLTK and spaCy |
| 2 | Stemming and Lemmatization on Sample Text |
| 3 | Stop-word Removal from a Document |
| 4 | Part-of-Speech (POS) Tagging of a Given Sentence |
| 5 | Parsing and Chunking using RegEx and spaCy |
| 6 | Named Entity Recognition (NER) using spaCy |

### CO2 — Text Representation and Advanced NLP

| S. No. | Practical Program |
|:---:|---|
| 8 | Bag-of-Words (BoW) Vectorization and Representation |
| 9 | TF-IDF Implementation and Comparison with BoW |
| 10 | N-Gram Model (Unigram, Bigram, Trigram) Generation |
| 11 | Cosine Similarity Between Text Documents |
| 12 | Word2Vec Word Embeddings using Gensim |
| 13 | GloVe Embeddings Loading and Vector Representation |
| 14 | Text Similarity using Word Mover's Distance (WMD) |
| 15 | Text Classification using Naïve Bayes and SVM with TF-IDF |
| 16 | Sentiment Analysis using TextBlob and VADER |
| 17 | Topic Modeling using Latent Dirichlet Allocation (LDA) |
| 18 | Topic Modeling using Latent Semantic Analysis (LSA) |
| 19 | Opinion Mining on Product/Service Reviews |
| 20 | Information Extraction from Structured and Unstructured Documents |
| 21 | Information Retrieval System with TF-IDF Ranking |

## 🛠️ Technologies Used

- Python 3
- NLTK
- spaCy
- scikit-learn
- Gensim
- TextBlob
- VADER Sentiment
- NumPy
- Regular Expressions (RegEx)
- Jupyter Notebook

## ⚙️ Installation

Install the required libraries:

```bash
pip install nltk spacy scikit-learn gensim textblob vaderSentiment numpy scipy
```

Download the spaCy English model:

```bash
python -m spacy download en_core_web_sm
```

Download required NLTK resources when needed:

```python
import nltk

nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
nltk.download('averaged_perceptron_tagger_eng')
```

Some programs using GloVe or Word2Vec pretrained embeddings may require an internet connection to download models.

## ▶️ Running the Programs

1. Clone or download this repository.
2. Open the project in VS Code, PyCharm, Jupyter Notebook, or another Python environment.
3. Install the required libraries.
4. Open the `CO1` or `CO2` folder.
5. Run the required Python program.

## 📂 Repository Structure

```text
NLP-Practical-Program/
├── NLP-Lab-Programs/
│   ├── CO1/
│   │   ├── 01_Tokenization.py
│   │   ├── 02_Stemming_Lemmatization.py
│   │   ├── 03_Stopword_Removal.py
│   │   ├── 04_POS_Tagging.py
│   │   ├── 05_Parsing_Chunking.py
│   │   └── 06_NER.py
│   ├── CO2/
│   │   ├── 08_BOW.py
│   │   ├── 09_TFIDF.py
│   │   ├── 10_NGram.py
│   │   └── ...
│   └── README.md
└── README.md
```

*The filenames above illustrate the intended organization; adjust them to match your actual files.*

## 🎯 Learning Outcomes

After completing these practical programs, students will be able to:

1. Process text using tokenization, stemming, and lemmatization.
2. Remove stop words and perform POS tagging.
3. Analyze sentence structure and identify named entities.
4. Represent documents using BoW and TF-IDF.
5. Generate n-grams and compare text documents.
6. Work with Word2Vec and GloVe word embeddings.
7. Build text classifiers using Naïve Bayes and SVM.
8. Perform sentiment analysis and opinion mining.
9. Discover topics using LDA and LSA.
10. Extract information and rank search results using TF-IDF.

## 👨‍💻 Author

**Ashutosh Singh**

B.Tech — Computer Science & Engineering (AI)

Roll No.: 2401331520057 | Section: AI A
