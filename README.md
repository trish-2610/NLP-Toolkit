## NLP Functions Collection

This repository contains a curated collection of core Natural Language Processing (NLP) functions implemented using Python and NLTK. The goal is to provide a ready-to-use reference for commonly used NLP operations such as tokenization, stemming, lemmatization, stopword removal, POS tagging, and more.

---
### Features Covered

#### 🔹 Tokenization

* **Sentence Tokenization:** Breaks paragraphs into individual sentences using `sent_tokenize`.
* **Word Tokenization:** Splits sentences into individual words using `word_tokenize`.

#### 🔹 Stemming

* Implements stemming using:

  * `PorterStemmer`
  * `Regular Expression Stemmer Class `
  * `SnowballStemmer`

#### 🔹 Lemmatization

* Uses WordNet lemmatizer (`WordNetLemmatizer`) to reduce words to their base form.

#### 🔹 Stopword Removal

* Filters out common English stopwords using NLTK's predefined list.

#### 🔹 POS Tagging

* Performs Part-of-Speech tagging using `pos_tag` on tokenized text.

#### 🔹 Named Entity Recognition (NER)

* Demonstrates chunking using `ne_chunk` for identifying named entities.

---

### Requirements

Ensure that the following Python libraries are installed:

```bash
pip install nltk
```

Also, download the necessary NLTK resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
nltk.download('maxent_ne_chunker')
nltk.download('words')
...
```

This notebook is ideal for:

* Students learning NLP basics
* Data science practitioners who need reusable NLP functions
* Quick experimentation in NLP prototypes

---

### Author

Made with ❤️ by **Trishansh**

