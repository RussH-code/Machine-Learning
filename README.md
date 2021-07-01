# Machine-Learning

In this notebook we are going to look at email classification. In machine learning lingo, **'Ham'** describes email that has real desirable content and not-spam, and **Spam** refers to those that are generally not desirable. To classify ham from spam, we are going to perform surpervised learning on some pre-labeled data. (Source: http://spamassassin.apache.org/publiccorpus/)

We are going to look at several key concepts in Natural Language Processing (NLP) in the framework of machine learning to handle text data. 

## 1. Tokenization
This is usually an early step in NLP to break long strings of text into smaller chunks or words (tokens).

## 2. Normalization
In text handling, normalization refers to a series of steps to standardize words, such as converting to the same case, removing punctuation and expanding contractions. This reduces bias introduced due to similar words appearing in differenct forms.

## 3. Stemming
Stemming is the process of removing suffix to get the **stem** of a word.

Example: playing -> play, eating -> eat

## 4. Lemmatization
Lemmatization is the process of capturing the canonical forms based on a word's lemma. This is generally more complicated and require a deeper understanding of the language to implement.

Example: worse -> bad, is -> be

## 5. Corpus
A corpus is a collection of structured and curated text and we check our data against them to perform statistical analysis and draw conclusions. In this notebook, we will use the NLTK corpus.

## 6. Bag of words
Bag of words is a way we represent text data in machine learning algorithm. It represents the occurence of words within a document. 

![Bag-of-words](https://github.com/RussH-code/Machine-Learning---Spam-Classifier/blob/main/BoW.png)

Source: https://medium.com/voice-tech-podcast/nlp-pipeline-101-with-basic-code-example-feature-extraction-ea9894ed8daf

---------------------------

In this notebook we will compare and contrast the performance of two common ML algorithm in handling this dataset.
