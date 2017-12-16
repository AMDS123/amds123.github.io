---
layout: post
title: "Conditional CycleGAN for Attribute Guided Face Image Generation"
date: 2017-05-28 17:37:23
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN Face
author: Yongyi Lu, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art techniques in Generative Adversarial Networks (GANs) such as cycleGAN is able to learn the mapping of one image domain $X$ to another image domain $Y$ using unpaired image data. We extend the cycleGAN to ${\it Conditional}$ cycleGAN such that the mapping from $X$ to $Y$ is subjected to attribute condition $Z$. Using face image generation as an application example, where $X$ is a low resolution face image, $Y$ is a high resolution face image, and $Z$ is a set of attributes related to facial appearance (e.g. gender, hair color, smile), we present our method to incorporate $Z$ into the network, such that the hallucinated high resolution face image $Y'$ not only satisfies the low resolution constrain inherent in $X$, but also the attribute condition prescribed by $Z$. Using face feature vector extracted from face verification network as $Z$, we demonstrate the efficacy of our approach on identity-preserving face image super-resolution. Our approach is general and applicable to high-quality face image generation where specific facial attributes can be controlled easily in the automatically generated results.

##### Abstract (translated by Google)
生成敌对网络（GAN）中的最先进技术（例如cycleGAN）能够学习使用不成对的图像数据将一个图像域$ X $映射到另一个图像域$ Y $。我们将cycleGAN扩展到$ {\ it Conditional} $ cycleGAN，使得从$ X $到$ Y $的映射受到属性条件$ Z $的影响。使用人脸图像生成作为应用实例，其中$ X $是低分辨率人脸图像，$ Y $是高分辨率人脸图像，$ Z $是与面部外观相关的一组属性（例如性别，头发颜色，微笑），我们提出了将$ Z $纳入网络的方法，使得幻觉的高分辨率人脸图像$ Y'$不仅满足$ X $中固有的低分辨率约束，还满足$ Z所规定的属性条件$。使用从人脸验证网络中提取的人脸特征向量作为$ Z $，我们证明了我们的方法在保持人脸图像超分辨率方面的有效性。我们的方法是通用的，适用于高质量的人脸图像生成，在自动生成的结果中可以轻松控制特定的面部属性。

##### URL
[https://arxiv.org/abs/1705.09966](https://arxiv.org/abs/1705.09966)

##### PDF
[https://arxiv.org/pdf/1705.09966](https://arxiv.org/pdf/1705.09966)

