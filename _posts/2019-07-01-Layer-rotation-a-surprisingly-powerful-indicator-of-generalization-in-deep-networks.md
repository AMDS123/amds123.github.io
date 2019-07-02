---
layout: post
title: "Layer rotation: a surprisingly powerful indicator of generalization in deep networks?"
date: 2019-07-01 16:01:43
categories: arXiv_CV
tags: arXiv_CV Relation
author: Simon Carbonnelle, Christophe De Vleeschouwer
mathjax: true
---

* content
{:toc}

##### Abstract
Our work presents extensive empirical evidence that layer rotation, i.e. the evolution across training of the cosine distance between each layer's weight vector and its initialization, constitutes an impressively consistent indicator of generalization performance. In particular, larger cosine distances between final and initial weights of each layer consistently translate into better generalization performance of the final model. Interestingly, this relation admits a network independent optimum: training procedures during which all layers' weights reach a cosine distance of 1 from their initialization consistently outperform other configurations -by up to 30% test accuracy. Moreover, we show that layer rotations are easily monitored and controlled (helpful for hyperparameter tuning) and potentially provide a unified framework to explain the impact of learning rate tuning, weight decay, learning rate warmups and adaptive gradient methods on generalization and training speed. In an attempt to explain the surprising properties of layer rotation, we show on a 1-layer MLP trained on MNIST that layer rotation correlates with the degree to which features of intermediate layers have been trained.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.01603](http://arxiv.org/abs/1806.01603)

##### PDF
[http://arxiv.org/pdf/1806.01603](http://arxiv.org/pdf/1806.01603)

