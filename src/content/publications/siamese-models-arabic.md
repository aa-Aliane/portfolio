---
title: "Evaluating Siamese Architecture Neural Models for Arabic Textual Similarity and Plagiarism Detection"
author: "Aliane Amine"
date: "2020-05-01"
journal: "ISIA"
description: "Implementation of Siamese neural networks to detect textual similarity and plagiarism in Arabic documents."
external_url: "/papers/siamese-models-arabic.pdf"
doi: ""
tags:
  - "NLP"
  - "Siamese Networks"
  - "Plagiarism Detection"
  - "Arabic"
---

## Abstract

Textual similarity detection in Arabic requires models that can capture semantic closeness despite the language's rich morphology and orthographic variation. This work evaluates Siamese neural network architectures, which learn to embed pairs of documents such that similar texts are placed close together in embedding space, for the task of Arabic textual similarity and plagiarism detection.

## Method

Twin neural networks with shared weights process pairs of documents, trained so that semantically similar pairs produce close embeddings and dissimilar pairs produce distant ones.

## Contribution

Evaluates Siamese architectures as an alternative to LSA-based approaches (see the earlier plagiarism detection work) for Arabic textual similarity, comparing their ability to generalize across paraphrasing and rewording patterns typical of plagiarized Arabic text.
