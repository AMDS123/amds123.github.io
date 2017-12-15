---
layout: post
title: "What is the Best Feature Learning Procedure in Hierarchical Recognition Architectures?"
date: 2016-06-05 17:31:39
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Recognition
author: Kevin Jarrett, Koray Kvukcuoglu, Karol Gregor, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
(This paper was written in November 2011 and never published. It is posted on arXiv.org in its original form in June 2016). Many recent object recognition systems have proposed using a two phase training procedure to learn sparse convolutional feature hierarchies: unsupervised pre-training followed by supervised fine-tuning. Recent results suggest that these methods provide little improvement over purely supervised systems when the appropriate nonlinearities are included. This paper presents an empirical exploration of the space of learning procedures for sparse convolutional networks to assess which method produces the best performance. In our study, we introduce an augmentation of the Predictive Sparse Decomposition method that includes a discriminative term (DPSD). We also introduce a new single phase supervised learning procedure that places an L1 penalty on the output state of each layer of the network. This forces the network to produce sparse codes without the expensive pre-training phase. Using DPSD with a new, complex predictor that incorporates lateral inhibition, combined with multi-scale feature pooling, and supervised refinement, the system achieves a 70.6\% recognition rate on Caltech-101. With the addition of convolutional training, a 77\% recognition was obtained on the CIfAR-10 dataset.

##### Abstract (translated by Google)
（本文于2011年11月撰写，从未发布，于2016年6月以原始格式发布在arXiv.org上）。许多最近的对象识别系统已经提出使用两阶段训练过程来学习稀疏卷积特征层次：无监督的预训练，然后是有监督的微调。最近的结果表明，这些方法提供了纯粹的监督系统时，包括适当的非线性几乎没有改善。本文对稀疏卷积网络的学习过程空间进行了实证研究，以评估哪种方法产生最佳性能。在我们的研究中，我们介绍了预测稀疏分解方法的增强，其中包括一个判别项（DPSD）。我们还引入了一个新的单阶段监督学习过程，在网络的每一层的输出状态上设置一个L1惩罚。这迫使网络在没有昂贵的预训练阶段的情况下产生稀疏码。使用DPSD结合横向抑制的新型复杂预测器，结合多尺度特征池和监督细化，该系统对Caltech-101的识别率达到70.6％。随着卷积训练的加入，CIfAR-10数据集获得了77％的认可。

##### URL
[https://arxiv.org/abs/1606.01535](https://arxiv.org/abs/1606.01535)

##### PDF
[https://arxiv.org/pdf/1606.01535](https://arxiv.org/pdf/1606.01535)

