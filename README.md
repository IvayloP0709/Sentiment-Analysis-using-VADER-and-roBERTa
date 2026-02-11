# 📊 Sentiment Analysis using VADER and roBERTa

A comparative NLP project that analyzes sentiment in textual reviews using both **lexicon-based** (VADER) and **transformer-based** (roBERTa) approaches.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green.svg)

## 📋 Overview

This project compares two sentiment analysis techniques on a large corpus of text reviews:

| Approach | Model | Type |
|----------|-------|------|
| **VADER** | Valence Aware Dictionary and sEntiment Reasoner | Lexicon-based, rule-based |
| **roBERTa** | Robustly optimized BERT pretraining approach | Transformer-based, deep learning |

Both models produce **polarity scores** (positive, negative, neutral) for comparative analysis.

## 📊 Dataset

- **Size**: ~500,000 textual reviews
- **Task**: Sentiment classification and polarity scoring

> ⚠️ The dataset is too large to host on GitHub (even when compressed). Please obtain the review dataset from your course materials or the original source.

## 🏗️ Project Structure

```
├── Sentiment.ipynb    # Main notebook with implementation and analysis
└── README.md
```

## 📈 Contents

The notebook includes:

- **Data preprocessing** and exploratory analysis
- **Data distribution** visualizations
- **VADER** sentiment scoring and polarity outputs
- **roBERTa** sentiment scoring and polarity outputs
- **Model comparison** and polarity score analysis
- **Limitations** of each approach

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy transformers torch vaderSentiment
```

### Usage

1. Add your review dataset to the project directory
2. Open `Sentiment.ipynb` in Jupyter
3. Update the data path in the notebook
4. Run all cells to preprocess, analyze, and compare sentiment scores

## 📝 Key Findings

- Comparative performance of lexicon-based vs. transformer-based sentiment analysis
- Polarity score outputs from both VADER and roBERTa
- Discussion of strengths and limitations of each approach

## 👤 Author

**Ivaylo Papazov**

## 📄 License

This project is available for educational purposes.

---

⭐ If you find this project useful, please consider giving it a star!
