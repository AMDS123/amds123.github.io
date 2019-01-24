---
layout: post
title: "Delta-training: Simple Semi-Supervised Text Classification using Pretrained Word Embeddings"
date: 2019-01-22 23:55:49
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification Prediction
author: Hwiyeol Jo, Ceyda Cinarel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel and simple method for semi-supervised text classification. The method starts from a hypothesis that a classifier with pretrained word embeddings always outperforms the same classifier with randomly initialized word embeddings, as empirically observed in NLP tasks. Our method first builds two sets of classifiers as a form of model ensemble, and then initializes their word embeddings differently: one using random, the other using pretrained word embeddings. We focus on different predictions between the two classifiers on unlabeled data while following the self-training framework. We also introduce label refinement and early-stopping in meta-epoch for better confidence on the label-by-prediction. We experiment on 4 different classification datasets, showing that our method performs better than the method using only the training set. Delta-training also outperforms the conventional self-training method in multi-class classification, showing robust performance against error accumulation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07651](http://arxiv.org/abs/1901.07651)

##### PDF
[http://arxiv.org/pdf/1901.07651](http://arxiv.org/pdf/1901.07651)

