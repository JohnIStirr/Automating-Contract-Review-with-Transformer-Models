# 📄 Automating ContractNLI with Transformer Models

A Natural Language Processing (NLP) project that applies transformer-based models to perform **Natural Language Inference (NLI)** on long-form documents. Using the ContractNLI dataset, the models classify whether a given statement is **entailed**, **contradicted**, or **not mentioned** within a document.

---

## Overview

This project explores how transformer models can automate document understanding by learning semantic relationships between text pairs. I performed exploratory data analysis, fine-tuned pretrained language models, and evaluated their performance on an NLI classification task.

---

## Features

- Fine-tuned **ALBERT** and **DistilBERT** for NLI
- Explored and visualized the dataset using Matplotlib
- Built an end-to-end text classification pipeline with Hugging Face Transformers and PyTorch
- Compared transformer model performance on a multi-class classification task

---

## Workflow

```text
Dataset
   │
   ▼
Data Exploration
   │
   ▼
Text Preprocessing
   │
   ▼
Tokenizer
   │
   ▼
ALBERT / DistilBERT
   │
   ▼
NLI Classification
   │
   ▼
Model Evaluation
```

---

## Tech Stack

- Python
- Hugging Face Transformers
- PyTorch
- Matplotlib
- Pandas
- NumPy

---

## Key Concepts

- Natural Language Processing (NLP)
- Natural Language Inference (NLI)
- Transformer Models
- Transfer Learning
- Text Classification
- Model Evaluation

---

## Future Improvements

- Fine-tune larger transformer models such as DeBERTa or RoBERTa
- Support long-context document models
- Build an interactive inference API with FastAPI
- Deploy as a web application
