---
layout: post
title: "Gaussian Processes with Context-Supported Priors for Active Object Localization"
date: 2017-09-20 06:47:26
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Anthony D. Rhodes, Jordan Witte, Melanie Mitchell, Bruno Jedynak
mathjax: true
---

* content
{:toc}

##### Abstract
We devise an algorithm using a Bayesian optimization framework in conjunction with contextual visual data for the efficient localization of objects in still images. Recent research has demonstrated substantial progress in object localization and related tasks for computer vision. However, many current state-of-the-art object localization procedures still suffer from inaccuracy and inefficiency, in addition to failing to provide a principled and interpretable system amenable to high-level vision tasks. We address these issues with the current research. Our method encompasses an active search procedure that uses contextual data to generate initial bounding-box proposals for a target object. We train a convolutional neural network to approximate an offset distance from the target object. Next, we use a Gaussian Process to model this offset response signal over the search space of the target. We then employ a Bayesian active search for accurate localization of the target. In experiments, we compare our approach to a state-of-theart bounding-box regression method for a challenging pedestrian localization task. Our method exhibits a substantial improvement over this baseline regression method.

##### Abstract (translated by Google)
我们设计了一个算法，使用贝叶斯优化框架结合上下文可视化数据，在静止图像中有效地定位对象。最近的研究已经在计算机视觉的目标定位和相关任务方面取得了实质性进展然而，目前许多最先进的对象本地化程序，除了没有提供一个适合高层次视觉任务的原则性和可解释的系统之外，还存在着不准确和低效率的问题。我们用当前的研究来解决这些问题。我们的方法包括使用上下文数据来为目标对象生成初始边界框提议的主动搜索过程。我们训练一个卷积神经网络来逼近与目标物体的偏移距离。接下来，我们使用高斯过程来在目标的搜索空间上对偏移响应信号进行建模。然后，我们采用贝叶斯主动搜索来准确定位目标。在实验中，我们将我们的方法与现有的边界框回归方法进行比较，以对具有挑战性的行人定位任务进行比较。我们的方法比这个基线回归方法有了显着的改进。

##### URL
[https://arxiv.org/abs/1703.08653](https://arxiv.org/abs/1703.08653)

##### PDF
[https://arxiv.org/pdf/1703.08653](https://arxiv.org/pdf/1703.08653)

