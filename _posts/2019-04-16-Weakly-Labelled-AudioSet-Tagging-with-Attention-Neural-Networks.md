---
layout: post
title: "Weakly Labelled AudioSet Tagging with Attention Neural Networks"
date: 2019-04-16 08:18:16
categories: arXiv_SD
tags: arXiv_SD Salient Attention Embedding Classification Relation
author: Qiuqiang Kong, Changsong Yu, Turab Iqbal, Yong Xu, Wenwu Wang, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
Audio tagging is the task of predicting the presence or absence of sound classes within an audio clip. Previous work in audio classification focused on relatively small datasets limited to recognising a small number of sound classes. We investigate audio tagging on AudioSet, which is a dataset consisting of over 2 million audio clips and 527 classes. AudioSet is weakly labelled, in that only the presence or absence of sound classes is known for each clip, while the onset and offset times are unknown. To address the weakly-labelled audio classification problem, we propose attention neural networks as a way to attend the the most salient parts of an audio clip. We bridge the connection between attention neural networks and multiple instance learning (MIL) methods, and propose decision-level and feature-level attention neural networks for audio tagging. We investigate attention neural networks modelled by different functions, depths and widths. Experiments on AudioSet show that the feature-level attention neural network achieves a state-of-the-art mean average precision (mAP) of 0.369, outperforming the best multiple instance learning (MIL) method of 0.317 and Google's deep neural network baseline of 0.314. In addition, we discover that the audio tagging performance on AudioSet embedding features has a weak correlation with the number of training examples and the quality of labels of each sound class.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00765](http://arxiv.org/abs/1903.00765)

##### PDF
[http://arxiv.org/pdf/1903.00765](http://arxiv.org/pdf/1903.00765)

