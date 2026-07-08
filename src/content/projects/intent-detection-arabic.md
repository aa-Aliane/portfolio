---
title: "Intent Detection in Arabic"
description: "Intent classification for Arabic conversational text, supporting downstream applications like chatbots and voice assistants."
tags:
  - "NLP"
  - "Intent Detection"
  - "Arabic"
  - "Transformers"
  - "Python"
image: "/images/placeholder.svg"
---

## Project Overview

Built intent classification models for Arabic conversational and query text at CERIST, a core component for downstream applications such as chatbots, voice assistants, or automated support systems operating in Arabic.

## Technical Details

- **Architectures**: [AraBERT / fine-tuned transformer, specify what you used, likely consistent with the sentiment work].
- **Intent taxonomy**: [Describe the intent categories, e.g. domain-specific intents for a given application].
- **Data**: [Dataset source, size, and labeling approach].

## Challenges

Intent detection in Arabic faces the same dialectal and morphological challenges as sentiment analysis, compounded by short, informal query text (as in chat or voice transcripts) that gives the model less context than full sentences or documents.

## Outcome

*[Status: in progress / completed — update this line.]* [Add your actual metric, e.g. "Achieved X% intent classification accuracy across N intent classes."]

## My Role

[Describe your specific contribution, e.g. built the labeled dataset, fine-tuned the classification model, integrated it into a downstream RAG/chatbot pipeline.]

## Related Work

Complements the [local LLM and RAG deployment work](/projects/research-infrastructure) by handling structured intent classification ahead of retrieval or generation.
