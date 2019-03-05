---
layout: post
title: "Predicting and interpreting embeddings for out of vocabulary words in downstream tasks"
date: 2019-03-02 15:32:39
categories: arXiv_CL
tags: arXiv_CL Attention Face Embedding Prediction
author: Nicolas Garneau, Jean-Samuel Leboeuf, Luc Lamontagne
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel way to handle out of vocabulary (OOV) words in downstream natural language processing (NLP) tasks. We implement a network that predicts useful embeddings for OOV words based on their morphology and on the context in which they appear. Our model also incorporates an attention mechanism indicating the focus allocated to the left context words, the right context words or the word's characters, hence making the prediction more interpretable. The model is a ``drop-in'' module that is jointly trained with the downstream task's neural network, thus producing embeddings specialized for the task at hand. When the task is mostly syntactical, we observe that our model aims most of its attention on surface form characters. On the other hand, for tasks more semantical, the network allocates more attention to the surrounding words. In all our tests, the module helps the network to achieve better performances in comparison to the use of simple random embeddings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00724](http://arxiv.org/abs/1903.00724)

##### PDF
[http://arxiv.org/pdf/1903.00724](http://arxiv.org/pdf/1903.00724)

