---
layout: post
title: "Conditional Image-to-Image Translation"
date: 2018-05-01 09:23:07
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Jianxin Lin, Yingce Xia, Tao Qin, Zhibo Chen, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation tasks have been widely investigated with Generative Adversarial Networks (GANs) and dual learning. However, existing models lack the ability to control the translated results in the target domain and their results usually lack of diversity in the sense that a fixed image usually leads to (almost) deterministic translation result. In this paper, we study a new problem, conditional image-to-image translation, which is to translate an image from the source domain to the target domain conditioned on a given image in the target domain. It requires that the generated image should inherit some domain-specific features of the conditional image from the target domain. Therefore, changing the conditional image in the target domain will lead to diverse translation results for a fixed input image from the source domain, and therefore the conditional input image helps to control the translation results. We tackle this problem with unpaired data based on GANs and dual learning. We twist two conditional translation models (one translation from A domain to B domain, and the other one from B domain to A domain) together for inputs combination and reconstruction while preserving domain independent features. We carry out experiments on men's faces from-to women's faces translation and edges to shoes&bags translations. The results demonstrate the effectiveness of our proposed method.

##### Abstract (translated by Google)
生成敌对网络（GAN）和双重学习已经广泛研究了图像到图像的翻译任务。然而，现有模型缺乏控制目标域中翻译结果的能力，并且它们的结果通常缺乏多样性，因为固定图像通常导致（几乎）确定性翻译结果。在本文中，我们研究了一个新问题，即有条件的图像到图像转换，即将图像从源域转换到目标域中给定图像上的目标域。它要求生成的图像应从目标域继承条件图像的某些特定于域的功能。因此，改变目标域中的条件图像将导致来自源域的固定输入图像的各种翻译结果，并且因此条件输入图像有助于控制翻译结果。我们用基于GAN和双重学习的不成对数据解决了这个问题。我们将两个条件翻译模型（一个从A域到B域，另一个从B域到A域）转换为输入组合和重构，同时保留域独立特征。我们对男性的脸部进行实验，从女性的脸部翻译和边缘到鞋子和书包的翻译。结果证明了我们提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1805.00251](https://arxiv.org/abs/1805.00251)

##### PDF
[https://arxiv.org/pdf/1805.00251](https://arxiv.org/pdf/1805.00251)

