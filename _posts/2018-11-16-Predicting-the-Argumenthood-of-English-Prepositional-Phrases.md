---
layout: post
title: "Predicting the Argumenthood of English Prepositional Phrases"
date: 2018-11-16 01:37:51
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Classification Language_Model Prediction
author: Najoung Kim, Kyle Rawlins, Benjamin Van Durme, Paul Smolensky
mathjax: true
---

* content
{:toc}

##### Abstract
Distinguishing between arguments and adjuncts of a verb is a longstanding, nontrivial problem. In natural language processing, argumenthood information is important in tasks such as semantic role labeling (SRL) and prepositional phrase (PP) attachment disambiguation. In theoretical linguistics, many diagnostic tests for argumenthood exist but they often yield conflicting and potentially gradient results. This is especially the case for syntactically oblique items such as PPs. We propose two PP argumenthood prediction tasks branching from these two motivations: (1) binary argument-adjunct classification of PPs in VerbNet, and (2) gradient argumenthood prediction using human judgments as gold standard, and report results from prediction models that use pretrained word embeddings and other linguistically informed features. Our best results on each task are (1) $acc.=0.955$, $F_1=0.954$ (ELMo+BiLSTM) and (2) Pearson's $r=0.624$ (word2vec+MLP). Furthermore, we demonstrate the utility of argumenthood prediction in improving sentence representations via performance gains on SRL when a sentence encoder is pretrained with our tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.07889](http://arxiv.org/abs/1809.07889)

##### PDF
[http://arxiv.org/pdf/1809.07889](http://arxiv.org/pdf/1809.07889)

