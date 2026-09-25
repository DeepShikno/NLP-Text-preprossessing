# NLP Text Preprocessing

A small collection of NLP preprocessing scripts using NLTK.

## Contents
- `stemmer_comparison.py` — Compares Porter, Lancaster, and Snowball stemmers on sample text
- `preprocessing_pipeline.py` — Tokenization → stopword removal → stemming pipeline
- `tweet_tokenization.py` — Social-media-aware tokenization (preserving hashtags/handles), stemming, and lemmatization, with notes on how symbols and emoji are handled

## Setup
```bash
pip install nltk
```
```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
```

## Usage
```bash
python stemmer_comparison.py
python preprocessing_pipeline.py
python tweet_tokenization.py
```
