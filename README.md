# NLP: Part-of-Speech (POS) Tagging Using spaCy

## About the Project
This project explores Part-of-Speech (POS) tagging using **spaCy**, a popular Python library for Natural Language Processing (NLP).

POS tagging is the process of identifying the grammatical category of each word in a sentence, such as noun, verb, adjective, adverb, and pronoun.

## Objectives
- Understand the basics of NLP using spaCy.
- Learn how to tokenize text.
- Perform coarse-grained POS tagging.
- Explore fine-grained POS tagging.
- Understand how words can have different grammatical roles depending on context.
- Visualize dependency parsing.

## Technologies Used
- Python
- spaCy
- Jupyter Notebook

## Installation and Setup

Install spaCy:

```bash
pip install spacy jupyter
```

Download the English language model:

```bash
python -m spacy download en_core_web_sm
```

## How to Run
1. Clone this repository.
2. Install the required dependencies.
3. Download the spaCy English language model.
4. Open `pos_tagging.ipynb` using Jupyter Notebook.
5. Run the notebook cells.

## Project Structure

```text
nlp-pos-tagging-with-spacy/
├── pos_tagging.ipynb
├── README.md
└── requirements.txt
```

## Key Concepts Learned
- Tokenization
- Coarse-grained POS tagging (`pos_`)
- Fine-grained POS tagging (`tag_`)
- `spacy.explain()` for understanding grammatical tags
- Context-based POS tagging
- Dependency parsing and visualization using displaCy

## Learning Outcome
Through this project, I gained practical experience with fundamental NLP concepts and learned how spaCy analyzes grammatical structures in natural language.

---

**Note:** This is a learning project developed as part of my journey into Natural Language Processing.
