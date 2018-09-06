---
layout: post
title: "Temporally Coherent Video Harmonization Using Adversarial Networks"
date: 2018-09-05 08:01:15
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Haozhi Huang, Senzhe Xu, Junxiong Cai, Wei Liu, Shimin Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Compositing is one of the most important editing operations for images and videos. The process of improving the realism of composite results is often called harmonization. Previous approaches for harmonization mainly focus on images. In this work, we take one step further to attack the problem of video harmonization. Specifically, we train a convolutional neural network in an adversarial way, exploiting a pixel-wise disharmony discriminator to achieve more realistic harmonized results and introducing a temporal loss to increase temporal consistency between consecutive harmonized frames. Thanks to the pixel-wise disharmony discriminator, we are also able to relieve the need of input foreground masks. Since existing video datasets which have ground-truth foreground masks and optical flows are not sufficiently large, we propose a simple yet efficient method to build up a synthetic dataset supporting supervised training of the proposed adversarial network. Experiments show that training on our synthetic dataset generalizes well to the real-world composite dataset. Also, our method successfully incorporates temporal consistency during training and achieves more harmonious results than previous methods.

##### Abstract (translated by Google)
合成是图像和视频最重要的编辑操作之一。改善复合结果的真实性的过程通常称为协调。以前的协调方法主要集中在图像上。在这项工作中，我们更进一步，以解决视频协调问题。具体来说，我们以对抗的方式训练卷积神经网络，利用像素方式的不和谐鉴别器来实现更真实的协调结果，并引入时间损失以增加连续协调帧之间的时间一致性。由于像素方式的不和谐鉴别器，我们还能够减轻输入前景掩模的需要。由于具有地面实况前景掩模和光流的现有视频数据集不够大，我们提出了一种简单而有效的方法来建立支持所提出的对抗网络的监督训练的合成数据集。实验表明，对我们的合成数据集的训练很好地概括了真实世界的复合数据集。此外，我们的方法成功地在训练期间结合了时间一致性，并且比以前的方法实现了更加和谐

##### URL
[http://arxiv.org/abs/1809.01372](http://arxiv.org/abs/1809.01372)

##### PDF
[http://arxiv.org/pdf/1809.01372](http://arxiv.org/pdf/1809.01372)

