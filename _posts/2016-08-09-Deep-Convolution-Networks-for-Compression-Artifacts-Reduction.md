---
layout: post
title: "Deep Convolution Networks for Compression Artifacts Reduction"
date: 2016-08-09 12:11:51
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Relation
author: Ke Yu, Chao Dong, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Lossy compression introduces complex compression artifacts, particularly blocking artifacts, ringing effects and blurring. Existing algorithms either focus on removing blocking artifacts and produce blurred output, or restore sharpened images that are accompanied with ringing effects. Inspired by the success of deep convolutional networks (DCN) on superresolution, we formulate a compact and efficient network for seamless attenuation of different compression artifacts. To meet the speed requirement of real-world applications, we further accelerate the proposed baseline model by layer decomposition and joint use of large-stride convolutional and deconvolutional layers. This also leads to a more general CNN framework that has a close relationship with the conventional Multi-Layer Perceptron (MLP). Finally, the modified network achieves a speed up of 7.5 times with almost no performance loss compared to the baseline model. We also demonstrate that a deeper model can be effectively trained with features learned in a shallow network. Following a similar "easy to hard" idea, we systematically investigate three practical transfer settings and show the effectiveness of transfer learning in low-level vision problems. Our method shows superior performance than the state-of-the-art methods both on benchmark datasets and a real-world use case.

##### Abstract (translated by Google)
有损压缩引入了复杂的压缩失真，特别是阻塞伪影，振铃效果和模糊。现有的算法或者关注于消除块效应并产生模糊的输出，或者恢复伴随振铃效应的锐化图像。受深度卷积网络（DCN）超分辨率成功的启发，我们制定了一个紧凑高效的网络，用于不同压缩伪像的无缝衰减。为了满足实际应用的速度要求，我们进一步通过层分解和联合使用大步卷积和去卷积层来加速提出的基线模型。这也导致了与传统的多层感知器（MLP）密切相关的更一般的CNN框架。最后，修改后的网络实现了7.5倍的加速，与基准模型相比几乎没有性能损失。我们还证明了一个更深层次的模型可以用浅层网络中的特征进行有效的训练。在类似的“易到难”的思想下，我们系统地研究了三种实用的转换设置，并展示了转移学习在低级视觉问题中的有效性。我们的方法在基准数据集和真实世界的用例上都显示出优于最先进的方法的性能。

##### URL
[https://arxiv.org/abs/1608.02778](https://arxiv.org/abs/1608.02778)

##### PDF
[https://arxiv.org/pdf/1608.02778](https://arxiv.org/pdf/1608.02778)

