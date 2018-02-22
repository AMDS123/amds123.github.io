---
layout: post
title: "Load Balanced GANs for Multi-view Face Image Synthesis"
date: 2018-02-21 07:10:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Face
author: Jie Cao, Yibo Hu, Bing Yu, Ran He, Zhenan Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view face synthesis from a single image is an ill-posed problem and often suffers from serious appearance distortion. Producing photo-realistic and identity preserving multi-view results is still a not well defined synthesis problem. This paper proposes Load Balanced Generative Adversarial Networks (LB-GAN) to precisely rotate the yaw angle of an input face image to any specified angle. LB-GAN decomposes the challenging synthesis problem into two well constrained subtasks that correspond to a face normalizer and a face editor respectively. The normalizer first frontalizes an input image, and then the editor rotates the frontalized image to a desired pose guided by a remote code. In order to generate photo-realistic local details, the normalizer and the editor are trained in a two-stage manner and regulated by a conditional self-cycle loss and an attention based L2 loss. Exhaustive experiments on controlled and uncontrolled environments demonstrate that the proposed method not only improves the visual realism of multi-view synthetic images, but also preserves identity information well.

##### Abstract (translated by Google)
来自单个图像的多视图人脸合成是一个不适合的问题，并且经常遭受严重的外观失真。制作照片般真实和保持身份的多视图结果仍然是一个没有明确定义的综合问题。本文提出负载均衡生成对抗网络（LB-GAN），将输入人脸图像的偏航角精确地旋转到任意指定的角度。 LB-GAN将具有挑战性的合成问题分解为两个良好约束的子任务，分别对应于脸部归一化器和脸部编辑器。规范化器首先对输入图像进行正面化，然后编辑器将正面化图像旋转到由远程代码引导的期望姿势。为了生成相片逼真的局部细节，规范器和编辑器分两步进行训练，并受条件自循环丢失和基于注意力的L2损失的调节。在受控和非受控环境下进行详尽的实验表明，所提出的方法不仅提高了多视点合成图像的视觉真实感，而且还很好地保留了身份信息。

##### URL
[http://arxiv.org/abs/1802.07447](http://arxiv.org/abs/1802.07447)

##### PDF
[http://arxiv.org/pdf/1802.07447](http://arxiv.org/pdf/1802.07447)

