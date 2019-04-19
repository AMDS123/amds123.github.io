---
layout: post
title: "A large-scale field test on word-image classification in large historical document collections using a traditional and two deep-learning methods"
date: 2019-04-17 16:03:14
categories: arXiv_CV
tags: arXiv_CV OCR Image_Classification Classification Deep_Learning
author: Lambert Schomaker
mathjax: true
---

* content
{:toc}

##### Abstract
This technical report describes a practical field test on word-image classification in a very large collection of more than 300 diverse handwritten historical manuscripts, with 1.6 million unique labeled images and more than 11 million images used in testing. Results indicate that several deep-learning tests completely failed (mean accuracy 83%). In the tests with more than 1000 output units (lexical words) in one-hot encoding for classification, performance steeply drops to almost zero percent accuracy, even with a modest size of the pre-final (i.e., penultimate) layer (150 units). A traditional feature method (BOVW) displays a consistent performance over numbers of classes and numbers of training examples (mean accuracy 87%). Additional tests using nearest mean on the output of the pre-final layer of an Inception V3 network, for each book, only yielded mediocre results (mean accuracy 49\%), but was not sensitive to high numbers of classes. Notably, this experiment was only possible on the basis of labels that were harvested on the basis of a traditional method which already works starting from a single labeled image per class. It is expected that the performance of the failed deep learning tests can be repaired, but only on the basis of human handcrafting (sic) of network architecture and hyperparameters. When the failed problematic books are not considered, end-to-end CNN training yields about 95% accuracy. This average is dominated by a large subset of Chinese characters, performances for other script styles being lower.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08421](http://arxiv.org/abs/1904.08421)

##### PDF
[http://arxiv.org/pdf/1904.08421](http://arxiv.org/pdf/1904.08421)

