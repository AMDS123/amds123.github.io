---
layout: post
title: "Named Entity Recognition Only from Word Embeddings"
date: 2019-08-31 08:22:13
categories: arXiv_CL
tags: arXiv_CL Knowledge Reinforcement_Learning Embedding Prediction Detection Recognition
author: Ying Luo, Hai Zhao, Junlang Zhan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network models have helped named entity (NE) recognition achieve amazing performance without handcrafting features. However, existing systems require large amounts of human annotated training data. Efforts have been made to replace human annotations with external knowledge (e.g., NE dictionary, part-of-speech tags), while it is another challenge to obtain such effective resources. In this work, we propose a fully unsupervised NE recognition model which only needs to take informative clues from pre-trained word embeddings. We first apply Gaussian Hidden Markov Model and Deep Autoencoding Gaussian Mixture Model on word embeddings for entity span detection and type prediction, and then further design an instance selector based on reinforcement learning to distinguish positive sentences from noisy sentences and refine these coarse-grained annotations through neural networks. Extensive experiments on CoNLL benchmark datasets demonstrate that our proposed light NE recognition model achieves remarkable performance without using any annotated lexicon or corpus.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00164](http://arxiv.org/abs/1909.00164)

##### PDF
[http://arxiv.org/pdf/1909.00164](http://arxiv.org/pdf/1909.00164)

