# End-to-End-Chatbot
A chatbot is a computer program that understands the intent of your query to answer with a solution. Chatbots are the most popular applications of Natural Language Processing in the industry.

## import nessery libraries
`import os:` Imports the os module which provides a way of interacting with the operating system.
`import nltk:` Imports the nltk library which provides natural language processing tools and resources.

`import ssl:` Imports the ssl module which provides support for secure socket layer (SSL) and transport layer security (TLS) protocols.

`import streamlit as st:` Imports the streamlit library which is a framework for building interactive web applications, and assigns it the alias st for convenience.

`import random:` Imports the random module which provides functions for generating random numbers.

`from sklearn.feature_extraction.text import TfidfVectorizer:` Imports the TfidfVectorizer class from the sklearn.feature_extraction.text module, which is used for extracting features from text data based on the term frequency-inverse document frequency (TF-IDF) algorithm.

`from sklearn.linear_model import LogisticRegression:` Imports the LogisticRegression class from the sklearn.linear_model module, which is a classification algorithm that uses logistic regression.

`ssl._create_default_https_context = ssl._create_unverified_context:` Sets the default SSL context to an unverified context, which is necessary for some SSL connections to work properly.

`nltk.data.path.append(os.path.abspath("nltk_data")):` Appends the absolute path of the directory nltk_data to the list of paths where nltk looks for data.

`nltk.download('punkt'):` Downloads the punkt tokenizer from the nltk library, which is used for tokenizing text into words.

 ## Requirements
* Environment (pick one)
* VSCode + devcontainer: It has been configured in the .devcontainer folder and can be used directly
* Docker
* Python 3.10 or later (instructions: for Windows)
* OpenAI API key




