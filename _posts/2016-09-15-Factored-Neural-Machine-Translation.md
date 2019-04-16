---
layout: post
title: "Factored Neural Machine Translation"
date: 2016-09-15 13:15:01
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Mercedes García-Martínez, Loïc Barrault, Fethi Bougares
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach for neural machine translation (NMT) using the morphological and grammatical decomposition of the words (factors) in the output side of the neural network. This architecture addresses two main problems occurring in MT, namely dealing with a large target language vocabulary and the out of vocabulary (OOV) words. By the means of factors, we are able to handle larger vocabulary and reduce the training time (for systems with equivalent target language vocabulary size). In addition, we can produce new words that are not in the vocabulary. We use a morphological analyser to get a factored representation of each word (lemmas, Part of Speech tag, tense, person, gender and number). We have extended the NMT approach with attention mechanism in order to have two different outputs, one for the lemmas and the other for the rest of the factors. The final translation is built using some \textit{a priori} linguistic information. We compare our extension with a word-based NMT system. The experiments, performed on the IWSLT'15 dataset translating from English to French, show that while the performance do not always increase, the system can manage a much larger vocabulary and consistently reduce the OOV rate. We observe up to 2% BLEU point improvement in a simulated out of domain translation setup.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1609.04621](https://arxiv.org/abs/1609.04621)

##### PDF
[https://arxiv.org/pdf/1609.04621](https://arxiv.org/pdf/1609.04621)

