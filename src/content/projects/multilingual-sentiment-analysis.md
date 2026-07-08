---
title: "Multilingual Sentiment Analysis"
description: "Sentiment classification models generalized across multiple languages, extending Arabic-focused work to a broader multilingual setting at CERIST."
tags:
  - "NLP"
  - "Multilingual"
  - "Sentiment Analysis"
  - "Transformers"
  - "Python"
image: "/images/placeholder.svg"
---

## Project Overview

Extended sentiment classification work beyond Arabic to a multilingual setting, evaluating how well transformer-based approaches generalize across languages with different morphological structures and resource levels.

## Technical Details

- **Architectures**: Multilingual transformer models (e.g. mBERT, XLM-R) evaluated against language-specific fine-tuned models.
- **Languages**: [List the actual languages covered, e.g. Arabic, French, English.]
- **Approach**: Compared zero-shot cross-lingual transfer against per-language fine-tuning, to assess how much language-specific adaptation is actually needed.

## Challenges

Cross-lingual transfer tends to work well between related, well-resourced languages but degrades for morphologically distant or low-resource ones, echoing the same pattern seen in the Arabic-specific sentiment work. Part of the evaluation was quantifying exactly where and how much that gap appears.

## Outcome

*[Status: in progress / completed — update this line.]* [Add your actual finding, e.g. "Zero-shot transfer retained X% of in-language performance for related languages, but dropped to Y% for Arabic without fine-tuning."]

## My Role

Designed the cross-lingual evaluation protocol and ran the comparative experiments across languages and model variants.
