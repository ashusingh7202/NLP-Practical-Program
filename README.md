# NLP Lab Programs — CO1, CO2 & CO3

This repository contains practical programs for **Natural Language Processing (NLP)** using Python and popular NLP libraries. It covers fundamental text processing, word representations, text classification, sentiment analysis, topic modeling, information extraction, information retrieval, recurrent neural networks, attention mechanisms, and Transformer-based NLP applications.

All programs are designed for educational purposes and can be adapted to run in Google Colab, Jupyter Notebook, or a local Python environment.

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

### CO3 — Deep Learning and Transformer-Based NLP

| S. No. | Practical Program |
|:---:|---|
| 22 | Sequence Classification using RNN/LSTM (Keras/TensorFlow) |
| 23 | Implementing Attention Mechanism (Basic Custom Model) |
| 24 | Fine-Tuning BERT for Text Classification using Hugging Face |
| 25 | Sentence Embeddings using BERT and GPT-2 |
| 26 | Text Generation using GPT-2 on a Custom Dataset |
| 27 | Named Entity Recognition using Transformers (BERT) |
| 28 | Machine Translation using MarianMT or T5 (Hugging Face) |
| 29 | Text Summarization using BART or T5 |
| 30 | Chatbot Development using a Pre-trained Transformer (DialoGPT) |
| 31 | Automatic Document Classification and Separation using ML |
| 32 | Hybrid Probabilistic + FSM-Based Sequence Modeling for Document Boundary Detection |

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Fundamental NLP:** NLTK, spaCy, Regular Expressions
- **Machine Learning:** scikit-learn, Naïve Bayes, SVM
- **Text Representation:** Bag-of-Words, TF-IDF, Word2Vec, GloVe
- **Deep Learning:** TensorFlow, Keras, PyTorch
- **Transformer Models:** Hugging Face Transformers, BERT, GPT-2, BART, DialoGPT, MarianMT
- **Sentiment Analysis:** TextBlob, VADER Sentiment
- **Topic Modeling:** LDA, LSA
- **Numerical Computing:** NumPy, SciPy
- **Data Processing:** Python, pandas (optional)
- **Execution Environments:** Google Colab, Jupyter Notebook, VS Code

## ⚙️ Installation

### 1. Install the required libraries

Run the following command in your terminal or a Google Colab cell:

```bash
pip install nltk spacy scikit-learn gensim textblob vaderSentiment numpy scipy tensorflow transformers torch sentencepiece
```

### 2. Download the spaCy English model

```python
import spacy

!python -m spacy download en_core_web_sm

nlp = spacy.load("en_core_web_sm")
```

### 3. Download the required NLTK resources

```python
import nltk

nltk.download("punkt")
nltk.download("punkt_tab")
nltk.download("stopwords")
nltk.download("wordnet")
nltk.download("omw-1.4")
nltk.download("averaged_perceptron_tagger")
nltk.download("averaged_perceptron_tagger_eng")
nltk.download("maxent_ne_chunker")
nltk.download("maxent_ne_chunker_tab")
nltk.download("words")
```

Some NLTK resources are only required by specific programs. If a resource is unavailable in your installed NLTK version, check the resource requirements for that program.

### 4. Download pretrained models when required

Programs using pretrained embeddings or Transformer models may download model files when first executed.

Examples include:

- Word2Vec and GloVe embeddings
- BERT for text classification and NER
- GPT-2 for text generation and embeddings
- BART for text summarization
- DialoGPT for chatbot development
- MarianMT for machine translation

An internet connection is generally required for the initial download. Some models may require substantial disk space, memory, or GPU resources.

**Note:** Google Colab is recommended for the deep learning and Transformer-based programs. Select **Runtime → Change runtime type → T4 GPU** when GPU acceleration is useful.

## ▶️ Running the Programs

### Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Copy the required program into a code cell.
4. Run any required installation commands.
5. Execute the program and inspect the output.

Each program should be run independently unless its instructions explicitly state otherwise.

### Local Python Environment

1. Clone or download this repository.
2. Install the required Python libraries.
3. Download the necessary language resources and pretrained models.
4. Open the required `.py` file or notebook.
5. Run the program using VS Code, PyCharm, Jupyter Notebook, or a terminal.

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
│   │
│   ├── CO2/
│   │   ├── 08_BOW.py
│   │   ├── 09_TFIDF.py
│   │   ├── 10_NGram.py
│   │   ├── 11_Cosine_Similarity.py
│   │   ├── 12_Word2Vec.py
│   │   ├── 13_GloVe.py
│   │   ├── 14_WMD.py
│   │   ├── 15_Text_Classification.py
│   │   ├── 16_Sentiment_Analysis.py
│   │   ├── 17_LDA_Topic_Modeling.py
│   │   ├── 18_LSA_Topic_Modeling.py
│   │   ├── 19_Opinion_Mining.py
│   │   ├── 20_Information_Extraction.py
│   │   └── 21_Information_Retrieval.py
│   │
│   ├── CO3/
│   │   ├── 22_RNN_LSTM_Classification.py
│   │   ├── 23_Custom_Attention.py
│   │   ├── 24_BERT_Text_Classification.py
│   │   ├── 25_BERT_GPT2_Embeddings.py
│   │   ├── 26_GPT2_Text_Generation.py
│   │   ├── 27_BERT_NER.py
│   │   ├── 28_MarianMT_Translation.py
│   │   ├── 29_BART_Summarization.py
│   │   ├── 30_DialoGPT_Chatbot.py
│   │   ├── 31_Document_Classification.py
│   │   └── 32_Hybrid_FSM_Boundary_Detection.py
│   │
│   └── README.md
│
└── README.md
```

*Note: The directory tree represents the intended organization. Create the folders and files as needed, and adjust the filenames to match the actual programs in your repository. Program 7 is not listed because its title was not provided.*

## 🎯 Learning Outcomes

After completing these practical programs, students will be able to:

1. Perform sentence and word tokenization, stemming, and lemmatization.
2. Remove stop words and perform POS tagging, parsing, and chunking.
3. Identify named entities using traditional NLP and Transformer-based models.
4. Represent text using Bag-of-Words, TF-IDF, n-grams, and word embeddings.
5. Calculate text similarity using cosine similarity and Word Mover's Distance.
6. Build text classification systems using Naïve Bayes, SVM, and LSTM.
7. Perform sentiment analysis, opinion mining, and topic modeling.
8. Extract structured information from documents and rank information retrieval results.
9. Implement a basic custom attention mechanism for sequence modeling.
10. Fine-tune BERT and generate sentence embeddings using pretrained language models.
11. Generate text using GPT-2 and build a basic conversational chatbot using DialoGPT.
12. Perform machine translation, text summarization, and Transformer-based NER.
13. Classify documents automatically and organize them into separate categories.
14. Detect document boundaries using probabilistic scoring and finite-state machine (FSM) logic.

## 📌 Important Notes

- These programs are intended for learning and experimentation; small sample datasets are not sufficient for reliable real-world performance.
- Pretrained models may produce different outputs depending on model versions, random seeds, hardware, and decoding settings.
- Fine-tuning large models can require considerable time and computational resources.
- The hybrid probabilistic + FSM boundary detector is a basic rule-based demonstration unless trained probability estimates are incorporated.
- Always verify model predictions before using them in important applications.

## 👨‍💻 Author

**Ashutosh Singh**

B.Tech — Computer Science & Engineering (AI)

Roll No.: 2401331520057 | Section: AI A
