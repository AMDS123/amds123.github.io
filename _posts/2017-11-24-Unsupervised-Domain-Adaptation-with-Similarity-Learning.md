---
layout: post
title: "Unsupervised Domain Adaptation with Similarity Learning"
date: 2017-11-24 14:49:25
categories: arXiv_CV
tags: arXiv_CV Inference Classification Deep_Learning
author: Pedro O. Pinheiro
mathjax: true
---

* content
{:toc}

##### Abstract
The objective of unsupervised domain adaptation is to leverage features from a labeled source domain and learn a classifier for an unlabeled target domain, with a similar but different data distribution. Most deep learning approaches to domain adaptation consist of two steps: (i) learn features that preserve a low risk on labeled samples (source domain) and (ii) make the features from both domains to be as indistinguishable as possible, so that a classifier trained on the source can also be applied on the target domain. In general, the classifiers in step (i) consist of fully-connected layers applied directly on the indistinguishable features learned in (ii). In this paper, we propose a different way to do the classification, using similarity learning. The proposed method learns a pairwise similarity function in which classification can be performed by computing distances between prototype representations of each category. The domain-invariant features and the categorical prototype representations are learned jointly and in an end-to-end fashion. At inference time, images from the target domain are compared to the prototypes and the label associated with the one that best matches the image is outputed. The approach is simple, scalable and effective. We show that our model achieves state-of-the-art performance in different large-scale unsupervised domain adaptation scenarios.

##### Abstract (translated by Google)
无监督域自适应的目标是利用来自标记源域的特征，并学习未标记目标域的分类器，具有类似但不同的数据分布。对领域适应的深度学习方法大多由两个步骤组成：（i）学习标记样本（源域）上保持低风险的特征;（ii）使两个域中的特征尽可能不区分，以便分类器在源码上训练也可以应用在目标域上。通常，步骤（i）中的分类器由直接应用于（ii）中学到的不可区分特征的完全连接层组成。在本文中，我们提出了一种不同的方法来进行分类，使用相似性学习。所提出的方法学习可以通过计算每个类别的原型表示之间的距离来执行分类的成对相似度函数。领域不变特征和分类原型表征是以端到端的方式共同学习的。在推断时，将来自目标域的图像与原型进行比较，并且与与图像最匹配的标签相关联的标签被输出。该方法简单，可扩展和有效。我们表明，我们的模型在不同的大规模无监督领域适应场景中实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1711.08995](https://arxiv.org/abs/1711.08995)

##### PDF
[https://arxiv.org/pdf/1711.08995](https://arxiv.org/pdf/1711.08995)

