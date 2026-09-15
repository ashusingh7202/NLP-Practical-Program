# NLP Unit 1 Practical Programs

This repository contains the **Unit 1 Practical Programs for Natural Language Processing (NLP)** using **Python, NLTK, and spaCy**.

The programs cover fundamental NLP techniques such as text tokenization, stemming, lemmatization, stop-word removal, POS tagging, parsing, chunking, and Named Entity Recognition.

---

## 📚 List of Programs

| S. No. | Practical Program                                        |  CO |
| :----: | -------------------------------------------------------- | :-: |
|    1   | Tokenization of Sentences and Words using NLTK and spaCy | CO1 |
|    2   | Stemming and Lemmatization on Sample Text                | CO1 |
|    3   | Stop-word Removal from a Document                        | CO1 |
|    4   | Part-of-Speech (POS) Tagging of a Given Sentence         | CO1 |
|    5   | Parsing and Chunking using RegEx and spaCy               | CO1 |
|    6   | Named Entity Recognition (NER) using spaCy               | CO1 |

---

# 1. Tokenization of Sentences and Words

### Aim

To perform **sentence and word tokenization** using NLTK and spaCy.

### Description

Tokenization is the process of dividing a text into smaller units called **tokens**. Tokens can be individual words or sentences.

### Technologies Used

* Python
* NLTK
* spaCy

### Concepts Covered

* Sentence Tokenization
* Word Tokenization
* NLTK Tokenization
* spaCy Tokenization

---

# 2. Stemming and Lemmatization

### Aim

To perform **stemming and lemmatization** on sample text.

### Description

**Stemming** reduces words to their root form by removing prefixes or suffixes.

**Lemmatization** converts words into their meaningful dictionary or base form.

### Example

| Word    | Stem   | Lemma |
| ------- | ------ | ----- |
| playing | play   | play  |
| studies | studi  | study |
| running | run    | run   |
| better  | better | good  |

### Technologies Used

* Python
* NLTK
* Porter Stemmer
* WordNet Lemmatizer

---

# 3. Stop-word Removal

### Aim

To remove stop words from a given document using NLTK.

### Description

Stop words are commonly occurring words that usually provide limited useful information for many NLP tasks.

### Examples

```text
the
is
are
a
an
and
in
on
it
they
```

### Technologies Used

* Python
* NLTK
* NLTK Stopwords Corpus

---

# 4. Part-of-Speech (POS) Tagging

### Aim

To perform **Part-of-Speech tagging** on a given sentence.

### Description

POS tagging assigns a grammatical category to each word in a sentence.

### Common POS Tags

| Tag | Meaning       |
| --- | ------------- |
| NN  | Noun          |
| NNS | Plural Noun   |
| VB  | Verb          |
| VBG | Verb - Gerund |
| JJ  | Adjective     |
| RB  | Adverb        |
| DT  | Determiner    |
| PRP | Pronoun       |

### Example

```text
The -> DT
students -> NNS
are -> VBP
learning -> VBG
NLP -> NN
```

### Technologies Used

* Python
* NLTK

---

# 5. Parsing and Chunking using RegEx and spaCy

### Aim

To perform **parsing and chunking** using Regular Expressions and spaCy.

### Description

Parsing analyzes the grammatical structure of a sentence.

Chunking groups related words into meaningful phrases such as **Noun Phrases (NP)**.

### Example

Input:

```text
The quick brown fox jumps over the lazy dog.
```

Noun phrases:

```text
The quick brown fox
the lazy dog
```

### Technologies Used

* Python
* NLTK
* RegEx
* spaCy
* RegexpParser

---

# 6. Named Entity Recognition (NER)

### Aim

To identify and classify named entities in a given text using spaCy.

### Description

Named Entity Recognition identifies important entities such as people, organizations, locations, dates, and monetary values.

### Common NER Labels

| Label  | Meaning               | Example        |
| ------ | --------------------- | -------------- |
| PERSON | Person                | Ashutosh       |
| ORG    | Organization          | Microsoft      |
| GPE    | Geographical Location | Delhi          |
| DATE   | Date                  | 15 August 2026 |
| MONEY  | Monetary Value        | ₹5000          |
| TIME   | Time                  | 10 AM          |

### Technologies Used

* Python
* spaCy
* `en_core_web_sm`

---

# 🛠️ Requirements

The practical programs are developed using **Python 3**.

Required libraries:

```text
nltk
spacy
```

Install them using:

```bash
pip install nltk spacy
```

For spaCy's English language model:

```bash
python -m spacy download en_core_web_sm
```

---

# ▶️ Running the Programs

The programs are provided as **Jupyter Notebook (`.ipynb`) files**.

They can be executed using:

* Google Colab
* Jupyter Notebook
* JupyterLab
* VS Code
* PyCharm

## Google Colab

Upload the required `.ipynb` file to Google Colab and run the cells sequentially.

For spaCy programs, the English model can be installed using:

```python
!python -m spacy download en_core_web_sm
```

For NLTK programs, required resources can be downloaded using:

```python
import nltk

nltk.download('punkt')
nltk.download('stopwords')
```

---

# 📂 Repository Contents

```text
NLP-Unit-1-Practical-Program/
│
├── 1_Tokenization_of_Sentences_and_Words_using_NLTK_and_spacy.ipynb
├── 2_Stemming_and_Lemmatization_on_Sample_Text.ipynb
├── 3_Stop_word_Removal_from_a_Document.ipynb
├── 4_Part_of_Speech_POS_Tagging_of_a_Given_Sentence.ipynb
├── 5_Parsing_and_Chunking_using_RegEx_and_spaCy.ipynb
├── 6_Named_Entity_Recognition_NER_using_spaCy.ipynb
└── README.md
```

---

# 🎯 Learning Outcomes

After completing these practical programs, the following fundamental NLP concepts are demonstrated:

1. Sentence and word tokenization
2. Stemming and lemmatization
3. Stop-word removal
4. Part-of-Speech tagging
5. Parsing and chunking
6. Named Entity Recognition

These techniques form the foundation of many **Natural Language Processing pipelines**.

---

# 💻 Technologies Used

* **Python**
* **NLTK**
* **spaCy**
* **Regular Expressions (RegEx)**
* **Jupyter Notebook**
* **Google Colab**

---

# 👨‍💻 Author

**Ashutosh Singh 2401331520057 AI A**

B.Tech – Computer Science & Engineering (AI)
