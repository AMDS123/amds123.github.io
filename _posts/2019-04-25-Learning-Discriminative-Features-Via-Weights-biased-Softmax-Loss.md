---
layout: post
title: "Learning Discriminative Features Via Weights-biased Softmax Loss"
date: 2019-04-25 03:24:53
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: XiaoBin Li, WeiQiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Loss functions play a key role in training superior deep neural networks. In convolutional neural networks (CNNs), the popular cross entropy loss together with softmax does not explicitly guarantee minimization of intra-class variance or maximization of inter-class variance. In the early studies, there is no theoretical analysis and experiments explicitly indicating how to choose the number of units in fully connected layer. To help CNNs learn features more fast and discriminative, there are two contributions in this paper. First, we determine the minimum number of units in FC layer by rigorous theoretical analysis and extensive experiment, which reduces CNNs' parameter memory and training time. Second, we propose a negative-focused weights-biased softmax (W-Softmax) loss to help CNNs learn more discriminative features. The proposed W-Softmax loss not only theoretically formulates the intraclass compactness and inter-class separability, but also can avoid overfitting by enlarging decision margins. Moreover, the size of decision margins can be flexibly controlled by adjusting a hyperparameter $\alpha$. Extensive experimental results on several benchmark datasets show the superiority of W-Softmax in image classification tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11138](http://arxiv.org/abs/1904.11138)

##### PDF
[http://arxiv.org/pdf/1904.11138](http://arxiv.org/pdf/1904.11138)

