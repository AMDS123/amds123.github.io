---
layout: post
title: "Domain adaptation for part-of-speech tagging of noisy user-generated text"
date: 2019-05-21 10:33:06
categories: arXiv_CL
tags: arXiv_CL Regularization Embedding RNN
author: Luisa M&#xe4;rz, Dietrich Trautmann, Benjamin Roth
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of a Part-of-speech (POS) tagger is highly dependent on the domain ofthe processed text, and for many domains there is no or only very little training data available. This work addresses the problem of POS tagging noisy user-generated text using a neural network. We propose an architecture that trains an out-of-domain model on a large newswire corpus, and transfers those weights by using them as a prior for a model trained on the target domain (a data-set of German Tweets) for which there is very little an-notations available. The neural network has two standard bidirectional LSTMs at its core. However, we find it crucial to also encode a set of task-specific features, and to obtain reliable (source-domain and target-domain) word representations. Experiments with different regularization techniques such as early stopping, dropout and fine-tuning the domain adaptation prior weights are conducted. Our best model uses external weights from the out-of-domain model, as well as feature embeddings, pre-trained word and sub-word embeddings and achieves a tagging accuracy of slightly over 90%, improving on the previous state of the art for this task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08920](http://arxiv.org/abs/1905.08920)

##### PDF
[http://arxiv.org/pdf/1905.08920](http://arxiv.org/pdf/1905.08920)

