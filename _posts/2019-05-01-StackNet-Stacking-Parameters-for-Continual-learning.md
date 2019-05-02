---
layout: post
title: "StackNet: Stacking Parameters for Continual learning"
date: 2019-05-01 08:10:25
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jangho Kim, Jeesoo Kim, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Training a neural network for a classification task typically assumes that the data to train are given from the beginning. However, in the real world, additional data accumulate gradually and the model requires additional training without accessing the old training data. This usually leads to the catastrophic forgetting problem which is inevitable for the traditional training methodology of neural networks. In this paper, we propose a continual learning method stacking feature map based continual learning method that is able to learn additional tasks while retaining the performance of previously learned tasks by stacking parameters. Composed of two complementary components, the index module and the StackNet, our method estimates the index of the corresponding task for an input sample with the index module and utilizes a particular portion of StackNet with this index. The StackNet guarantees no degradation in the performance of the previously learned tasks and the index module shows high confidence in finding the origin of an input sample.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.02441](https://arxiv.org/abs/1809.02441)

##### PDF
[https://arxiv.org/pdf/1809.02441](https://arxiv.org/pdf/1809.02441)

