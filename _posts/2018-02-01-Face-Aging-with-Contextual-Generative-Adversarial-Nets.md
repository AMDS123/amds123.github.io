---
layout: post
title: "Face Aging with Contextual Generative Adversarial Nets"
date: 2018-02-01 10:52:21
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Attention GAN Face
author: Si Liu, Yao Sun, Defa Zhu, Renda Bao, Wei Wang, Xiangbo Shu, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Face aging, which renders aging faces for an input face, has attracted extensive attention in the multimedia research. Recently, several conditional Generative Adversarial Nets (GANs) based methods have achieved great success. They can generate images fitting the real face distributions conditioned on each individual age group. However, these methods fail to capture the transition patterns, e.g., the gradual shape and texture changes between adjacent age groups. In this paper, we propose a novel Contextual Generative Adversarial Nets (C-GANs) to specifically take it into consideration. The C-GANs consists of a conditional transformation network and two discriminative networks. The conditional transformation network imitates the aging procedure with several specially designed residual blocks. The age discriminative network guides the synthesized face to fit the real conditional distribution. The transition pattern discriminative network is novel, aiming to distinguish the real transition patterns with the fake ones. It serves as an extra regularization term for the conditional transformation network, ensuring the generated image pairs to fit the corresponding real transition pattern distribution. Experimental results demonstrate the proposed framework produces appealing results by comparing with the state-of-the-art and ground truth. We also observe performance gain for cross-age face verification.

##### Abstract (translated by Google)
人脸老化，使人脸老化，在多媒体研究中引起了广泛的关注。最近，一些基于条件生成对抗网络（GANs）的方法取得了巨大的成功。他们可以生成适合每个年龄段的真实脸部分布的图像。然而，这些方法不能捕捉到过渡模式，例如相邻年龄组之间的渐变形状和纹理变化。在本文中，我们提出了一个新的上下文生成对抗网络（C-GANs）来具体考虑。 C-GAN由一个条件转换网络和两个判别网络组成。条件转换网络用几个专门设计的残差块模拟老化过程。年龄判断网络引导合成的人脸以适应真实的条件分布。转换模式识别网络是新颖的，旨在区分真实的转换模式和假冒的转换模式。它作为条件转换网络的一个额外的正则化项，确保生成的图像对符合相应的实际转换模式分布。实验结果表明，提出的框架通过与最先进的和基本事实的比较产生有吸引力的结果。我们也观察到跨年龄人脸验证的性能增益。

##### URL
[http://arxiv.org/abs/1802.00237](http://arxiv.org/abs/1802.00237)

##### PDF
[http://arxiv.org/pdf/1802.00237](http://arxiv.org/pdf/1802.00237)

