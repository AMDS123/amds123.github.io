---
layout: post
title: "Deeply Learning the Messages in Message Passing Inference"
date: 2015-09-08 04:29:45
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference Prediction
author: Guosheng Lin, Chunhua Shen, Ian Reid, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep structured output learning shows great promise in tasks like semantic image segmentation. We proffer a new, efficient deep structured model learning scheme, in which we show how deep Convolutional Neural Networks (CNNs) can be used to estimate the messages in message passing inference for structured prediction with Conditional Random Fields (CRFs). With such CNN message estimators, we obviate the need to learn or evaluate potential functions for message calculation. This confers significant efficiency for learning, since otherwise when performing structured learning for a CRF with CNN potentials it is necessary to undertake expensive inference for every stochastic gradient iteration. The network output dimension for message estimation is the same as the number of classes, in contrast to the network output for general CNN potential functions in CRFs, which is exponential in the order of the potentials. Hence CNN message learning has fewer network parameters and is more scalable for cases that a large number of classes are involved. We apply our method to semantic image segmentation on the PASCAL VOC 2012 dataset. We achieve an intersection-over-union score of 73.4 on its test set, which is the best reported result for methods using the VOC training images alone. This impressive performance demonstrates the effectiveness and usefulness of our CNN message learning method.

##### Abstract (translated by Google)
深度结构的输出学习在语义图像分割等任务中显示出巨大的前景。我们提供了一个新的，高效的深层结构模型学习方案，其中我们展示了如何使用深度卷积神经网络（CNN）来估计带有条件随机场（CRF）的结构化预测的消息传递推断中的消息。使用这种CNN消息估计器，我们避免了需要学习或评估消息计算的潜在功能。这为学习提供了显着的效率，因为否则当执行具有CNN潜力的CRF的结构学习时，有必要对每个随机梯度迭代进行昂贵的推理。用于消息估计的网络输出维度与类别的数量相同，与CRF中一般的CNN潜在函数的网络输出相比，这是潜在的顺序的指数。因此，CNN消息学习具有较少的网络参数，并且对于涉及大量类的情况而言更具可扩展性。我们将我们的方法应用于PASCAL VOC 2012数据集上的语义图像分割。我们在其测试集上获得了73.4的交叉点整合得分，这是单独使用VOC训练图像的方法的最佳报告结果。这一令人印象深刻的表现证明了我们的CNN消息学习方法的有效性和实用性。

##### URL
[https://arxiv.org/abs/1506.02108](https://arxiv.org/abs/1506.02108)

##### PDF
[https://arxiv.org/pdf/1506.02108](https://arxiv.org/pdf/1506.02108)

