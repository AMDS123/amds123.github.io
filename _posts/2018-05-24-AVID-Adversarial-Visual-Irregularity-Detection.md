---
layout: post
title: "AVID: Adversarial Visual Irregularity Detection"
date: 2018-05-24 06:23:45
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning Detection
author: Mohammad Sabokrou, Masoud Pourreza, Mohsen Fayyaz, Rahim Entezari, Mahmood Fathy, J&#xfc;rgen Gall, Ehsan Adeli
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time detection of irregularities in visual data is very invaluable and useful in many prospective applications including surveillance, patient monitoring systems, etc. With the surge of deep learning methods in the recent years, researchers have tried a wide spectrum of methods for different applications. However, for the case of irregularity or anomaly detection in videos, training an end-to-end model is still an open challenge, since often irregularity is not well-defined and there are not enough irregular samples to use during training. In this paper, inspired by the success of generative adversarial networks (GANs) for training deep models in unsupervised or self-supervised settings, we propose an end-to-end deep network for detection and fine localization of irregularities in videos (and images). Our proposed architecture is composed of two networks, which are trained in competing with each other while collaborating to find the irregularity. One network works as a pixel-level irregularity $I$npainter, and the other works as a patch-level $D$etector. After an adversarial self-supervised training, in which $I$ tries to fool $D$ into accepting its inpainted output as regular (normal), the two networks collaborate to detect and fine-segment the irregularity in any given testing video. Our results on three different datasets (one synthetic and two video datasets) show that our proposed method can not only outperform the state-of-the-art but also to fine-segment the irregularity.

##### Abstract (translated by Google)
实时检测视觉数据中的不规则性在包括监视，患者监测系统等在内的许多预期应用中非常宝贵和有用。随着近年来深度学习方法的激增，研究人员已经尝试了多种方法用于不同的应用。但是，对于视频中出现不规则或异常检测的情况，对端到端模型进行培训仍然是一个公开挑战，因为经常出现的不规则性不明确，并且在训练期间没有足够的不规则样本。在本文中，受到生成对抗网络（GAN）在无监督或自我监督环境中训练深度模型的成功启发，我们提出了一个端到端的深度网络，用于检测和精确定位视频（和图像）中的不规则性， 。我们提出的架构由两个网络组成，这两个网络经过相互竞争的训练，同时协作寻找不规则性。一个网络可用作像素级别的不规则性$ I $ npainter，另一个网络可用作修补程序级别的$ D $ etector。经过对抗性自我监督训练，其中$ I $试图欺骗$ D $以接受其修复后的输出为常规（正常），两个网络协作检测并细分任何给定测试视频中的不规则性。我们在三个不同数据集（一个合成数据集和两个视频数据集）上的结果表明，我们提出的方法不仅可以胜过最新的技术，而且可以细化不规则性。

##### URL
[http://arxiv.org/abs/1805.09521](http://arxiv.org/abs/1805.09521)

##### PDF
[http://arxiv.org/pdf/1805.09521](http://arxiv.org/pdf/1805.09521)

