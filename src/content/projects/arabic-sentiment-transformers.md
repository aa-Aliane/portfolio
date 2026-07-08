---
title: "Arabic Sentiment Analysis with Transformers"
description: "Transformer-based sentiment classification for Arabic text (MSA and dialectal), built at CERIST using BERT and AraBERT."
tags:
  - "NLP"
  - "Transformers"
  - "Hugging Face"
  - "Sentiment Analysis"
  - "Python"
image: "/images/placeholder.svg"
---

## Project Overview

Built high-accuracy sentiment classification models for Arabic text at CERIST, using transformer architectures (BERT, AraBERT, mBERT) via Hugging Face. The project targeted both Modern Standard Arabic and dialectal Arabic, which behave very differently under standard tokenization and required separate evaluation.

## Technical Details

- **Architectures**: BERT, AraBERT, mBERT, compared against classical ML baselines (SVM, logistic regression on TF-IDF features).
- **Frameworks**: PyTorch, Hugging Face Transformers.
- **Data**: [Add dataset name/size, e.g. "labeled dataset of X tweets/reviews across positive/negative/neutral classes"].
- **Evaluation**: Accuracy and F1 compared across architectures and against traditional baselines, with error analysis on dialectal variation.

## Challenges

Arabic's morphological richness and the frequent code-switching in dialectal text (Arabic mixed with French/English) made standard tokenization approaches underperform. AraBERT's Arabic-specific pretraining gave a measurable advantage over general multilingual BERT for this reason.

## Outcome

Improved classification accuracy compared to traditional machine learning baselines. [Replace with your actual number, e.g. "X% F1, a Y point improvement over the SVM baseline."]

## My Role

Designed the experimental setup, fine-tuned the transformer models, and ran the comparative evaluation against classical baselines.
