---
layout: post
title: "Distributed Averaging CNN-ELM for Big Data"
date: 2016-10-07 18:59:23
categories: arXiv_CV
tags: arXiv_CV
author: Arif Budiman, Mohamad Ivan Fanany, Chan Basaruddin
mathjax: true
---

* content
{:toc}

##### Abstract
Increasing the scalability of machine learning to handle big volume of data is a challenging task. The scale up approach has some limitations. In this paper, we proposed a scale out approach for CNN-ELM based on MapReduce on classifier level. Map process is the CNN-ELM training for certain partition of data. It involves many CNN-ELM models that can be trained asynchronously. Reduce process is the averaging of all CNN-ELM weights as final training result. This approach can save a lot of training time than single CNN-ELM models trained alone. This approach also increased the scalability of machine learning by combining scale out and scale up approaches. We verified our method in extended MNIST data set and not-MNIST data set experiment. However, it has some drawbacks by additional iteration learning parameters that need to be carefully taken and training data distribution that need to be carefully selected. Further researches to use more complex image data set are required.

##### Abstract (translated by Google)
增加机器学习的可扩展性以处理大量数据是一项具有挑战性的任务。放大方法有一些限制。在本文中，我们提出了基于MapReduce的CNN-ELM在分类器级的扩展方法。地图过程是对某些数据分区进行的CNN-ELM培训。它涉及许多可以异步训练的CNN-ELM模型。减少过程是所有CNN-ELM权重的平均值作为最终的训练结果。这种方法比单独训练的单个CNN-ELM模型节省了大量训练时间。这种方法还通过结合规模扩大和扩大规模来提高机器学习的可扩展性。我们在扩展MNIST数据集和非MNIST数据集实验中验证了我们的方法。然而，由于需要仔细考虑额外的迭代学习参数以及需要仔细选择的训练数据分布，所以它具有一些缺点。需要进一步研究使用更复杂的图像数据集。

##### URL
[https://arxiv.org/abs/1610.02373](https://arxiv.org/abs/1610.02373)

##### PDF
[https://arxiv.org/pdf/1610.02373](https://arxiv.org/pdf/1610.02373)

