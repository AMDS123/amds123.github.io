---
layout: post
title: "Query-Free Attacks on Industry-Grade Face Recognition Systems under Resource Constraints"
date: 2018-02-13 08:44:58
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Face Recognition Face_Recognition
author: Di Tang, XiaoFeng Wang, Kehuan Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
To attack a deep neural network (DNN) based Face Recognition (FR) system, one needs to build \textit{substitute} models to simulate the target, so the adversarial examples discovered could also mislead the target. Such \textit{transferability} is achieved in recent studies through querying the target to obtain data for training the substitutes. A real-world target, likes the FR system of law enforcement, however, is less accessible to the adversary. To attack such a system, a substitute with similar quality as the target is needed to identify their common defects. This is hard since the adversary often does not have the enough resources to train such a model (hundreds of millions of images for training a commercial FR system). We found in our research, however, that a resource-constrained adversary could still effectively approximate the target's capability to recognize \textit{specific} individuals, by training \textit{biased} substitutes on additional images of those who want to evade recognition (the subject) or the victims to be impersonated (called Point of Interest, or PoI). This is made possible by a new property we discovered, called \textit{Nearly Local Linearity} (NLL), which models the observation that an ideal DNN model produces the image representations whose distances among themselves truthfully describe the differences in the input images seen by human. By simulating this property around the PoIs using the additional subject or victim data, we significantly improve the transferability of black-box impersonation attacks by nearly 50\%. Particularly, we successfully attacked a commercial system trained over 20 million images, using 4 million images and 1/5 of the training time but achieving 60\% transferability in an impersonation attack and 89\% in a dodging attack.

##### Abstract (translated by Google)
为了攻击基于深度神经网络（DNN）的人脸识别（FR）系统，需要建立\ textit {替代}模型来模拟目标，因此发现的敌对案例也可能误导目标。在最近的研究中通过查询目标以获得用于培训替代品的数据来实现这种可转移性。然而，一个真实世界的目标，就像法律系统的执法体系，对手不那么容易接近。为了攻击这样一个系统，需要一个与目标质量相似的替代品来识别它们的共同缺陷。这很难，因为对手经常没有足够的资源来训练这样一个模型（用于培训商用FR系统的数亿张图片）。然而，在我们的研究中，我们发现资源受限的对手仍然可以有效地接近目标识别特定个体的能力，这是通过对那些想要逃避识别的人的额外图像进行训练，主题）或受害者被假冒（称为Point of Interest，或PoI）。这可以通过我们发现的一种新属性来实现，这种属性叫做\ textit {近似局部线性}（NLL），它对理想的DNN模型产生的图像表示进行建模，该图像表示之间的距离如实地描述了输入图像中的差异人类。通过使用附加主题或受害者数据模拟PoI的这一特性，我们将黑盒模拟攻击的可转移性显着提高了近50％。特别是，我们成功攻击了一个训练超过2000万张图像的商业系统，使用了400万张图像和1/5的训练时间，但在假冒攻击中实现了60％的可转移性，在躲避攻击中达到了89％。

##### URL
[https://arxiv.org/abs/1802.09900](https://arxiv.org/abs/1802.09900)

##### PDF
[https://arxiv.org/pdf/1802.09900](https://arxiv.org/pdf/1802.09900)

