---
layout: post
title: "Deformable GANs for Pose-based Human Image Generation"
date: 2017-12-29 22:58:31
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Detection
author: Aliaksandr Siarohin, Enver Sangineto, Stephane Lathuiliere, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we address the problem of generating person images conditioned on a given pose. Specifically, given an image of a person and a target pose, we synthesize a new image of that person in the novel pose. In order to deal with pixel-to-pixel misalignments caused by the pose differences, we introduce deformable skip connections in the generator of our Generative Adversarial Network. Moreover, a nearest-neighbour loss is proposed instead of the common $L_1$ and $L_2$ losses in order to match the details of the generated image with the target image. We test out approach using photos of persons in different poses and we compare our method with previous work in this area showing state-of-the-art results in two benchmarks. Our method can be applied to the wider field of deformable object generation, provided that the pose of the articulated object can be extracted using a keypoint detector.

##### Abstract (translated by Google)
在本文中，我们解决了在给定姿势下产生人物图像的问题。具体来说，给定一个人的形象和一个目标姿势，我们合成一个新的姿势的人的形象。为了处理由姿态差异引起的像素到像素的不对齐，我们在生成对手网络的生成器中引入可变形的跳跃连接。此外，为了使生成的图像的细节与目标图像匹配，提出了最近邻居丢失而不是共同的$ L_1 $和$ L_2 $损失。我们使用不同姿势的人物的照片来测试方法，并且将我们的方法与这个领域的先前的工作进行比较，以两个基准显示最新的结果。假设可以使用关键点检测器来提取关节物体的姿态，那么我们的方法可以应用于更广泛的可变形物体生成领域。

##### URL
[http://arxiv.org/abs/1801.00055](http://arxiv.org/abs/1801.00055)

##### PDF
[http://arxiv.org/pdf/1801.00055](http://arxiv.org/pdf/1801.00055)

