---
layout: post
title: "High quality ultrasonic multi-line transmission through deep learning"
date: 2018-08-23 16:07:59
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Sanketh Vedula, Ortal Senouf, Grigoriy Zurakhov, Alex M. Bronstein, Michael Zibulevsky, Oleg Michailovich, Dan Adam, Diana Gaitini
mathjax: true
---

* content
{:toc}

##### Abstract
Frame rate is a crucial consideration in cardiac ultrasound imaging and 3D sonography. Several methods have been proposed in the medical ultrasound literature aiming at accelerating the image acquisition. In this paper, we consider one such method called \textit{multi-line transmission} (MLT), in which several evenly separated focused beams are transmitted simultaneously. While MLT reduces the acquisition time, it comes at the expense of a heavy loss of contrast due to the interactions between the beams (cross-talk artifact). In this paper, we introduce a data-driven method to reduce the artifacts arising in MLT. To this end, we propose to train an end-to-end convolutional neural network consisting of correction layers followed by a constant apodization layer. The network is trained on pairs of raw data obtained through MLT and the corresponding \textit{single-line transmission} (SLT) data. Experimental evaluation demonstrates significant improvement both in the visual image quality and in objective measures such as contrast ratio and contrast-to-noise ratio, while preserving resolution unlike traditional apodization-based methods. We show that the proposed method is able to generalize well across different patients and anatomies on real and phantom data.

##### Abstract (translated by Google)
帧率是心脏超声成像和3D超声检查的关键考虑因素。在医学超声文献中已经提出了几种旨在加速图像采集的方法。在本文中，我们考虑一种称为\ textit {多线传输}（MLT）的方法，其中几个均匀分离的聚焦光束同时传输。虽然MLT减少了采集时间，但是由于光束之间的相互作用（串扰伪像）导致对比度严重损失。在本文中，我们介绍了一种数据驱动方法，以减少MLT中出现的伪像。为此，我们建议训练一个端到端的卷积神经网络，该网络由校正层和一个恒定的变迹层组成。通过MLT和相应的\ textit {单行传输}（SLT）数据获得的原始数据对训练网络。实验评估表明在视觉图像质量和客观测量（例如对比度和对比度噪声比）方面的显着改进，同时保持分辨率不同于传统的基于变迹的方法。我们表明，所提出的方法能够很好地概括不同的患者和真实和幻像数据的解剖。

##### URL
[http://arxiv.org/abs/1808.07819](http://arxiv.org/abs/1808.07819)

##### PDF
[http://arxiv.org/pdf/1808.07819](http://arxiv.org/pdf/1808.07819)

