# nlp_rasa_foodbot
A rasa open source chatbot that takes user queries and returns the best restaurants in the area using Zomato API

## Pre-requisites

- python 3.7.0
- rasa 1.3.9
- spacy 2.1.4
- en_core_web_md 2.1.0


## Installation

### RASA

Refer to official [installation guide](https://rasa.com/docs/rasa/user-guide/installation/) to install RASA

### Spacy

1. Package Installation

   ```python
   pip install -U spacy
   ```

2. Model Installation

   ```python
   python -m spacy download en_core_web_md
   ```

3. Create custom shortcut link to Spacy model

   ```python
   python -m spacy link en_core_web_md en
   ``
   
