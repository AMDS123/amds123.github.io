---
layout: post
title: "Learning to Select Pre-Trained Deep Representations with Bayesian Evidence Framework"
date: 2016-04-25 01:35:31
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Transfer_Learning Prediction Recognition
author: Yong-Deok Kim, Taewoong Jang, Bohyung Han, Seungjin Choi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Bayesian evidence framework to facilitate transfer learning from pre-trained deep convolutional neural networks (CNNs). Our framework is formulated on top of a least squares SVM (LS-SVM) classifier, which is simple and fast in both training and testing, and achieves competitive performance in practice. The regularization parameters in LS-SVM is estimated automatically without grid search and cross-validation by maximizing evidence, which is a useful measure to select the best performing CNN out of multiple candidates for transfer learning; the evidence is optimized efficiently by employing Aitken's delta-squared process, which accelerates convergence of fixed point update. The proposed Bayesian evidence framework also provides a good solution to identify the best ensemble of heterogeneous CNNs through a greedy algorithm. Our Bayesian evidence framework for transfer learning is tested on 12 visual recognition datasets and illustrates the state-of-the-art performance consistently in terms of prediction accuracy and modeling efficiency.

##### Abstract (translated by Google)
我们提出了一个贝叶斯证据框架，以促进从预先训练的深度卷积神经网络（CNNs）转移学习。我们的框架是在最小二乘支持向量机（LS-SVM）分类器的基础上制定的，它在训练和测试中都简单快速，并且在实践中实现了有竞争力的表现。 LS-SVM中的正则化参数是通过最大化证据自动估计的，没有网格搜索和交叉验证，这是从多个候选者中选择性能最好的CNN用于传递学习的有用措施;利用Aitken的delta-squared过程有效地优化证据，加速了定点更新的收敛。提出的贝叶斯证据框架也提供了一个很好的解决方案，通过贪心算法来识别异构CNN的最佳集合。我们在12个视觉识别数据集上测试了用于转移学习的贝叶斯证据框架，并在预测准确性和建模效率方面一致地说明了最先进的性能。

##### URL
[https://arxiv.org/abs/1506.02565](https://arxiv.org/abs/1506.02565)

##### PDF
[https://arxiv.org/pdf/1506.02565](https://arxiv.org/pdf/1506.02565)

