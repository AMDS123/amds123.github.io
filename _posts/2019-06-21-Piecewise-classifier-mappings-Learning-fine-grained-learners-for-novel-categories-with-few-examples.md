---
layout: post
title: "Piecewise classifier mappings: Learning fine-grained learners for novel categories with few examples"
date: 2019-06-21 08:03:07
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Recognition
author: Xiu-Shen Wei, Peng Wang, Lingqiao Liu, Chunhua Shen, Jianxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Humans are capable of learning a new fine-grained concept with very little supervision, \emph{e.g.}, few exemplary images for a species of bird, yet our best deep learning systems need hundreds or thousands of labeled examples. In this paper, we try to reduce this gap by studying the fine-grained image recognition problem in a challenging few-shot learning setting, termed few-shot fine-grained recognition (FSFG). The task of FSFG requires the learning systems to build classifiers for novel fine-grained categories from few examples (only one or less than five). To solve this problem, we propose an end-to-end trainable deep network which is inspired by the state-of-the-art fine-grained recognition model and is tailored for the FSFG task. 
 Specifically, our network consists of a bilinear feature learning module and a classifier mapping module: while the former encodes the discriminative information of an exemplar image into a feature vector, the latter maps the intermediate feature into the decision boundary of the novel category. The key novelty of our model is a "piecewise mappings" function in the classifier mapping module, which generates the decision boundary via learning a set of more attainable sub-classifiers in a more parameter-economic way. We learn the exemplar-to-classifier mapping based on an auxiliary dataset in a meta-learning fashion, which is expected to be able to generalize to novel categories. By conducting comprehensive experiments on three fine-grained datasets, we demonstrate that the proposed method achieves superior performance over the competing baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.04288](http://arxiv.org/abs/1805.04288)

##### PDF
[http://arxiv.org/pdf/1805.04288](http://arxiv.org/pdf/1805.04288)

