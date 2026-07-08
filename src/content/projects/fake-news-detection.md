---
title: "Fake News Detection System"
description: "A deep learning system combining semantic text representation with classification models to identify misinformation."
tags:
  - "NLP"
  - "Deep Learning"
  - "Misinformation Detection"
  - "Python"
image: "/images/placeholder.svg"
---

## Project Overview

Developed a system to detect fake news articles by combining rich semantic text representations with deep neural classification models, at CERIST. The goal was to move beyond simple keyword or source-based heuristics toward representations that capture meaning and framing.

## Key Features

- **Semantic Embedding**: Word and sentence embeddings used to build dense representations of article content rather than relying on surface lexical features.
- **Classification**: Deep neural network architecture trained to distinguish credible from fabricated content based on these representations.
- **Evaluation**: Testing on curated datasets of labeled news articles, with attention to generalization across topics (a common failure mode for fake news classifiers trained on a narrow topic set).

## Challenges

Fake news detection models often overfit to topic-specific vocabulary rather than learning generalizable signals of misinformation. Part of the evaluation focused on testing whether the model's performance held up on topics not seen during training, a stronger and more honest test than in-topic accuracy alone.

## Outcome

[Add your actual result, e.g. "Achieved X% accuracy on held-out topics, compared to Y% for a bag-of-words baseline."]

## My Role

Built the embedding pipeline and classification model, and designed the topic-generalization evaluation.
