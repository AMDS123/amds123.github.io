---
layout: post
title: "Gender Bias in Neural Natural Language Processing"
date: 2019-05-30 23:34:50
categories: arXiv_CL
tags: arXiv_CL Embedding Optimization RNN Language_Model Gradient_Descent
author: Kaiji Lu, Piotr Mardziel, Fangjing Wu, Preetam Amancharla, Anupam Datta
mathjax: true
---

* content
{:toc}

##### Abstract
We examine whether neural natural language processing (NLP) systems reflect historical biases in training data. We define a general benchmark to quantify gender bias in a variety of neural NLP tasks. Our empirical evaluation with state-of-the-art neural coreference resolution and textbook RNN-based language models trained on benchmark datasets finds significant gender bias in how models view occupations. We then mitigate bias with CDA: a generic methodology for corpus augmentation via causal interventions that breaks associations between gendered and gender-neutral words. We empirically show that CDA effectively decreases gender bias while preserving accuracy. We also explore the space of mitigation strategies with CDA, a prior approach to word embedding debiasing (WED), and their compositions. We show that CDA outperforms WED, drastically so when word embeddings are trained. For pre-trained embeddings, the two methods can be effectively composed. We also find that as training proceeds on the original data set with gradient descent the gender bias grows as the loss reduces, indicating that the optimization encourages bias; CDA mitigates this behavior.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11714](http://arxiv.org/abs/1807.11714)

##### PDF
[http://arxiv.org/pdf/1807.11714](http://arxiv.org/pdf/1807.11714)

