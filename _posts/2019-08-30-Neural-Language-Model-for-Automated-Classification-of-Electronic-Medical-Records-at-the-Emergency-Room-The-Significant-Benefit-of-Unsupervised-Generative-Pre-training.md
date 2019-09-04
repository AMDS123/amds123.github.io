---
layout: post
title: "Neural Language Model for Automated Classification of Electronic Medical Records at the Emergency Room. The Significant Benefit of Unsupervised Generative Pre-training"
date: 2019-08-30 17:25:06
categories: arXiv_AI
tags: arXiv_AI Classification Language_Model
author: Binbin Xu, Cédric Gil-Jardiné, Frantz Thiessard, Eric Tellier, Marta Avalos, Emmanuel Lagarde
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of a project to build a national injury surveillance system based on emergency room (ER) visit reports, it was necessary to develop a coding system capable of classifying the causes of these visits based on the automatic reading of clinical notes written by clinicians. Supervised learning techniques have shown good results but require manual coding of a large number of texts for model training. New levels of performance have been achieved in neural language models (NLM) with the use of the Transformer architecture with an unsupervised generative pre-training step. Our hypothesis is that this latter method significantly reduces the number of annotated samples required. We derived from available diagnostic codes the traumatic/non-traumatic nature of the cause of the ER visit. We then designed a case study to predict from free text clinical notes whether a visit was traumatic or not. We compared two strategies: Strategy A consisted in training the GPT-2 NLM on the training data (with a maximum of 161930 samples) with all labels (trauma/non-trauma) in a single fully-supervised phase. In Strategy B, we split the training data in two parts, 151930 samples without any label for the self-supervised pre-training phase and a much smaller part (up to 10000 samples) for the supervised fine-tuning with labels. In Strategy A, AUC and F1 score reach 0.97 and 0.89 respectively after the processing of 7000 samples. The use of generative pre-training (Strategy B) achieved an AUC of 0.93 and an F1-score of 0.80 after the processing of only 120 samples. The same performance was achieved with only 30 labeled samples processed 3 times (3 epochs of learning). To conclude, it is possible to easily adapt a multi-purpose NLM model such as the GPT-2 to create a powerful tool for classification of free-text notes with the need of a very small number of labeled samples.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1909.01136](https://arxiv.org/abs/1909.01136)

##### PDF
[https://arxiv.org/pdf/1909.01136](https://arxiv.org/pdf/1909.01136)

