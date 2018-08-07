---
layout: post
title: "Defense Against Adversarial Attacks with Saak Transform"
date: 2018-08-06 09:01:41
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Sibo Song, Yueru Chen, Ngai-Man Cheung, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) are known to be vulnerable to adversarial perturbations, which imposes a serious threat to DNN-based decision systems. In this paper, we propose to apply the lossy Saak transform to adversarially perturbed images as a preprocessing tool to defend against adversarial attacks. Saak transform is a recently-proposed state-of-the-art for computing the spatial-spectral representations of input images. Empirically, we observe that outputs of the Saak transform are very discriminative in differentiating adversarial examples from clean ones. Therefore, we propose a Saak transform based preprocessing method with three steps: 1) transforming an input image to a joint spatial-spectral representation via the forward Saak transform, 2) apply filtering to its high-frequency components, and, 3) reconstructing the image via the inverse Saak transform. The processed image is found to be robust against adversarial perturbations. We conduct extensive experiments to investigate various settings of the Saak transform and filtering functions. Without harming the decision performance on clean images, our method outperforms state-of-the-art adversarial defense methods by a substantial margin on both the CIFAR-10 and ImageNet datasets. Importantly, our results suggest that adversarial perturbations can be effectively and efficiently defended using state-of-the-art frequency analysis.

##### Abstract (translated by Google)
已知深度神经网络（DNN）容易受到对抗性扰动的影响，这对基于DNN的决策系统构成严重威胁。在本文中，我们建议将有损Saak变换应用于对抗扰动的图像，作为防御对抗性攻击的预处理工具。 Saak变换是最近提出的用于计算输入图像的空间光谱表示的最新技术。根据经验，我们观察到Saak变换的输出在区分对抗性实例和干净实例方面具有很大的区别性。因此，我们提出了一种基于Saak变换的预处理方法，包括三个步骤：1）通过前向Saak变换将输入图像变换为联合空间光谱表示，2）对其高频分量应用滤波，以及3）重建图像通过逆Saak变换。发现经处理的图像对抗对抗性扰动是鲁棒的。我们进行了大量实验来研究Saak变换和滤波函数的各种设置。在不损害清晰图像的决策性能的情况下，我们的方法在CIFAR-10和ImageNet数据集上都大大超过了最先进的对抗防御方法。重要的是，我们的结果表明，使用最先进的频率分析可以有效和有效地防御对抗性扰动。

##### URL
[https://arxiv.org/abs/1808.01785](https://arxiv.org/abs/1808.01785)

##### PDF
[https://arxiv.org/pdf/1808.01785](https://arxiv.org/pdf/1808.01785)

