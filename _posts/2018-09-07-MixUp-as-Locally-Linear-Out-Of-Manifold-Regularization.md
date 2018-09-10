---
layout: post
title: "MixUp as Locally Linear Out-Of-Manifold Regularization"
date: 2018-09-07 14:26:17
categories: arXiv_AI
tags: arXiv_AI Regularization Classification
author: Hongyu Guo, Yongyi Mao, Richong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
MixUp, a data augmentation approach through mixing random samples, has been shown to be able to significantly improve the predictive accuracy of the current art of deep neural networks. The power of MixUp, however, is mostly established empirically and its working and effectiveness have not been explained in any depth. In this paper, we develop a theoretical understanding for MixUp as a form of out-of-manifold regularization, which constrains the model on the input space beyond the data manifold. This analytical study also enables us to identify MixUp's limitation caused by manifold intrusion, where synthetic samples collide with real examples of the manifold. Such intrusion gives rise to over regularization and thereby under-fitting. To address this issue, we further propose a novel regularizer, where mixing policies are adaptively learned from the data and a manifold intrusion loss is embraced as to avoid collision with the data manifold. We empirically show, using several benchmark datasets, our regularizer's effectiveness in terms of over regularization avoiding and accuracy improvement upon current art of deep classification models and MixUp.

##### Abstract (translated by Google)
MixUp是一种通过混合随机样本的数据增强方法，已被证明能够显着提高当前深度神经网络技术的预测精度。然而，MixUp的力量大多是凭经验建立的，其工作和效果尚未得到任何深度解释。在本文中，我们开发了对MixUp的理论理解，作为流形外正规化的一种形式，它将模型限制在数据流形之外的输入空间上。这项分析研究还使我们能够识别由流形侵入引起的MixUp限制，其中合成样本与流形的实例相冲突。这种入侵导致过度正规化，从而导致不合适。为了解决这个问题，我们进一步提出了一种新颖的正则化器，其中混合策略是从数据中自适应地学习的，并且包含歧管入侵损失以避免与数据流形的冲突。我们使用几个基准数据集来实证地展示了我们的正则化器在超正则化避免和当前深度分类模型和MixUp的精度改进方面的有效性。

##### URL
[http://arxiv.org/abs/1809.02499](http://arxiv.org/abs/1809.02499)

##### PDF
[http://arxiv.org/pdf/1809.02499](http://arxiv.org/pdf/1809.02499)

