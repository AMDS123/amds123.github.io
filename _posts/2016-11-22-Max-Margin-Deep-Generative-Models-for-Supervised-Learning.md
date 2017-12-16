---
layout: post
title: "Max-Margin Deep Generative Models for Supervised Learning"
date: 2016-11-22 01:36:29
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Inference Classification Prediction Recognition
author: Chongxuan Li, Jun Zhu, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep generative models (DGMs) are effective on learning multilayered representations of complex data and performing inference of input data by exploring the generative ability. However, it is relatively insufficient to empower the discriminative ability of DGMs on making accurate predictions. This paper presents max-margin deep generative models (mmDGMs) and a class-conditional variant (mmDCGMs), which explore the strongly discriminative principle of max-margin learning to improve the predictive performance of DGMs in both supervised and semi-supervised learning, while retaining the generative capability. In semi-supervised learning, we use the predictions of a max-margin classifier as the missing labels instead of performing full posterior inference for efficiency; we also introduce additional max-margin and label-balance regularization terms of unlabeled data for effectiveness. We develop an efficient doubly stochastic subgradient algorithm for the piecewise linear objectives in different settings. Empirical results on various datasets demonstrate that: (1) max-margin learning can significantly improve the prediction performance of DGMs and meanwhile retain the generative ability; (2) in supervised learning, mmDGMs are competitive to the best fully discriminative networks when employing convolutional neural networks as the generative and recognition models; and (3) in semi-supervised learning, mmDCGMs can perform efficient inference and achieve state-of-the-art classification results on several benchmarks.

##### Abstract (translated by Google)
深度生成模型（DGM）对于学习复杂数据的多层表示以及通过探索生成能力来对输入数据进行推理是有效的。然而，加强DGM的判别能力做出准确的预测是相对不足的。本文提出了最大边缘深度生成模型（mmDGMs）和一个类别条件变量（mmDCGMs），探讨了最大边缘学习的强歧视性原则，以提高DGM在监督学习和半监督学习中的预测性能，保持生成能力。在半监督学习中，我们使用最大边缘分类器的预测作为缺失标签，而不是对效率进行完全后验推理;我们还引入了额外的最大利润率和标签平衡正规化术语的未标记数据的有效性。我们针对不同设置下的分段线性目标开发了一种高效的双随机次梯度算法。对各种数据集的实证结果表明：（1）最大边缘学习能显着提高DGMs的预测性能，同时保留生成能力; （2）在监督学习中，mmDGMs在使用卷积神经网络作为生成和识别模型时，具有最好的全识别性网络竞争力; （3）在半监督学习中，mmDCGM可以进行高效的推理，并在几个基准上达到最新的分类结果。

##### URL
[https://arxiv.org/abs/1611.07119](https://arxiv.org/abs/1611.07119)

##### PDF
[https://arxiv.org/pdf/1611.07119](https://arxiv.org/pdf/1611.07119)

