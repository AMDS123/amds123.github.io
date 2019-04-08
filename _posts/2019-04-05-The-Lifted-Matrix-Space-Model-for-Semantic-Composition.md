---
layout: post
title: "The Lifted Matrix-Space Model for Semantic Composition"
date: 2019-04-05 05:12:39
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding RNN
author: WooJin Chung, Sheng-Fu Wang, Samuel R. Bowman
mathjax: true
---

* content
{:toc}

##### Abstract
Tree-structured neural network architectures for sentence encoding draw inspiration from the approach to semantic composition generally seen in formal linguistics, and have shown empirical improvements over comparable sequence models by doing so. Moreover, adding multiplicative interaction terms to the composition functions in these models can yield significant further improvements. However, existing compositional approaches that adopt such a powerful composition function scale poorly, with parameter counts exploding as model dimension or vocabulary size grows. We introduce the Lifted Matrix-Space model, which uses a global transformation to map vector word embeddings to matrices, which can then be composed via an operation based on matrix-matrix multiplication. Its composition function effectively transmits a larger number of activations across layers with relatively few model parameters. We evaluate our model on the Stanford NLI corpus, the Multi-Genre NLI corpus, and the Stanford Sentiment Treebank and find that it consistently outperforms TreeLSTM (Tai et al., 2015), the previous best known composition function for tree-structured models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.03602](http://arxiv.org/abs/1711.03602)

##### PDF
[http://arxiv.org/pdf/1711.03602](http://arxiv.org/pdf/1711.03602)

