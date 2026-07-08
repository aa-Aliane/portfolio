# Tree View:
```
src/content/publications
├── arabic-sentiment-classification.md
├── lsa-plagiarism-detection.md
├── neural-machine-translation.md
├── sarcasm-detection-arabic.md
└── siamese-models-arabic.md

```

# Content:

## arabic-sentiment-classification.md

```md
---
title: "A genetic algorithm feature selection based approach for Arabic sentiment classification"
author: "Aliane Amine"
date: "2016-11-01"
journal: "IEEE/ACS International Conference on Computer Systems and Applications (AICCSA)"
description: "Research on sentiment classification for Arabic text using genetic algorithms to optimize performance."
external_url: "/papers/arabic-sentiment-classification.pdf"
doi: ""
tags:
  - "NLP"
  - "Sentiment Analysis"
  - "Genetic Algorithms"
  - "Arabic"
---

## Abstract

Sentiment classification for Arabic text faces challenges rarely encountered in English, including rich morphology, dialectal variation, and sparse labeled resources. This work proposes a genetic algorithm based feature selection method to reduce dimensionality and noise in the feature space before classification, aiming to improve both accuracy and computational efficiency.

## Method

A genetic algorithm searches the space of candidate feature subsets, using classification accuracy as the fitness function, to select a compact and informative set of features from a larger pool of lexical and statistical candidates.

## Contribution

Demonstrates that evolutionary feature selection can improve sentiment classification accuracy on Arabic text while reducing the dimensionality of the feature space compared to using the full feature set.

```


## lsa-plagiarism-detection.md

```md
---
title: "A Latent Semantic Analysis (LSA) approach for plagiarism detection in Arabic documents"
author: "Aliane Amine"
date: "2018-01-01"
journal: "International Conference"
description: "Exploring Latent Semantic Analysis (LSA) for identifying plagiarism in Arabic text."
external_url: "/papers/lsa-plagiarism-detection.pdf"
doi: ""
tags:
  - "NLP"
  - "LSA"
  - "Plagiarism Detection"
  - "Arabic"
---

## Abstract

Plagiarism detection in Arabic text is complicated by the language's morphological richness, where surface-level word matching often fails to capture semantic similarity between paraphrased passages. This work applies Latent Semantic Analysis to represent documents in a reduced semantic space, allowing detection of conceptually similar content even when the wording differs.

## Method

Documents are represented as term-document matrices, then projected into a lower-dimensional semantic space using singular value decomposition, so that similarity can be measured on meaning rather than exact word overlap.

## Contribution

Shows that LSA based semantic similarity outperforms purely lexical matching approaches for detecting plagiarism in Arabic documents, particularly for paraphrased or reworded content.

```


## neural-machine-translation.md

```md
---
title: "Neural Machine Translation for the Arabic-English Language Pair"
author: "Aliane Amine"
date: "2024-03-01"
journal: "ICPAIS (International Conference on Pattern Analysis and Intelligent Systems)"
description: "Implementation and evaluation of modern Neural Machine Translation models for the Arabic-English language pair."
external_url: "/papers/neural-machine-translation.pdf"
doi: ""
tags:
  - "NLP"
  - "Machine Translation"
  - "Neural Networks"
  - "Arabic"
---

## Abstract

This work implements and evaluates modern neural machine translation architectures on the Arabic-English language pair, a setting where morphological complexity and limited high-quality parallel data pose challenges beyond those typically faced by well-resourced language pairs.

## Method

Transformer-based sequence-to-sequence models are trained and evaluated on Arabic-English parallel corpora, with results compared across architectural and training variants.

## Contribution

Provides an evaluation of neural machine translation performance for Arabic-English, establishing a baseline that later informed the model efficiency and pruning work developed for multilingual NMT.

## Related work

This paper's translation setup is the foundation for [A General Framework for Efficient Multilingual Neural Machine Translation](/publications/general-framework-efficient-nmt), which builds on it with model compression techniques.

```


## sarcasm-detection-arabic.md

```md
---
title: "Sarcasm Detection in Arabic Tweets: A Comparison Between Deep Learning and Pre-trained Transformer-based Models"
author: "Aliane Amine"
date: "2022-06-01"
journal: "ISIA"
description: "A study on detecting sarcasm in dialectal Arabic tweets using machine learning techniques."
external_url: "/papers/sarcasm-detection-arabic.pdf"
doi: ""
tags:
  - "NLP"
  - "Sarcasm Detection"
  - "Twitter"
  - "Arabic"
---

## Abstract

Sarcasm detection is difficult even in well-resourced languages, and Arabic adds further challenges through dialectal variation and limited annotated data for informal, social media text. This work compares classical deep learning architectures against pre-trained transformer models (such as AraBERT) for detecting sarcasm in Arabic tweets.

## Method

Both approaches are trained and evaluated on a dataset of dialectal Arabic tweets labeled for sarcasm, allowing direct comparison of transformer-based transfer learning against models trained from scratch.

## Contribution

Quantifies the performance gap between pre-trained transformer models and traditional deep learning approaches for Arabic sarcasm detection, informing model choice for downstream sentiment and opinion mining systems on Arabic social media.

```


## siamese-models-arabic.md

```md
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

```
