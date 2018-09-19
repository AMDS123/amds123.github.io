---
layout: post
title: "Déjà Vu: an empirical evaluation of the memorization properties of ConvNets"
date: 2018-09-17 18:25:08
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Alexandre Sablayrolles, Matthijs Douze, Cordelia Schmid, Hervé Jégou
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks memorize part of their training data, which is why strategies such as data augmentation and drop-out are employed to mitigate overfitting. This paper considers the related question of "membership inference", where the goal is to determine if an image was used during training. We consider it under three complementary angles. We show how to detect which dataset was used to train a model, and in particular whether some validation images were used at train time. We then analyze explicit memorization and extend classical random label experiments to the problem of learning a model that predicts if an image belongs to an arbitrary set. Finally, we propose a new approach to infer membership when a few of the top layers are not available or have been fine-tuned, and show that lower layers still carry information about the training samples. To support our findings, we conduct large-scale experiments on Imagenet and subsets of YFCC-100M with modern architectures such as VGG and Resnet.

##### Abstract (translated by Google)
卷积神经网络记忆其部分训练数据，这就是采用数据增加和辍学等策略来减轻过度拟合的原因。本文考虑了“会员推理”的相关问题，其目的是确定在培训期间是否使用了图像。我们在三个互补的角度考虑它。我们展示了如何检测用于训练模型的数据集，特别是在列车时间是否使用了一些验证图像。然后，我们分析显式记忆并将经典随机标签实验扩展到学习模型的问题，该模型预测图像是否属于任意集合。最后，我们提出了一种新的方法来推断成员资格，当一些顶层不可用或已经微调时，并显示较低层仍然携带有关训练样本的信息。为了支持我们的研究结果，我们利用现代架构（如VGG和Resnet）对Imagenet和YFCC-100M子集进行了大规模实验。

##### URL
[https://arxiv.org/abs/1809.06396](https://arxiv.org/abs/1809.06396)

##### PDF
[https://arxiv.org/pdf/1809.06396](https://arxiv.org/pdf/1809.06396)

