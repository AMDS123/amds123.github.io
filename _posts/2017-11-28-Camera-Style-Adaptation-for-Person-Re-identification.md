---
layout: post
title: "Camera Style Adaptation for Person Re-identification"
date: 2017-11-28 14:01:30
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification GAN Person_Re-identification
author: Zhun Zhong, Liang Zheng, Zhedong Zheng, Shaozi Li, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Being a cross-camera retrieval task, person re-identification suffers from image style variations caused by different cameras. The art implicitly addresses this problem by learning a camera-invariant descriptor subspace. In this paper, we explicitly consider this challenge by introducing camera style (CamStyle) adaptation. CamStyle can serve as a data augmentation approach that smooths the camera style disparities. Specifically, with CycleGAN, labeled training images can be style-transferred to each camera, and, along with the original training samples, form the augmented training set. This method, while increasing data diversity against over-fitting, also incurs a considerable level of noise. In the effort to alleviate the impact of noise, the label smooth regularization (LSR) is adopted. The vanilla version of our method (without LSR) performs reasonably well on few-camera systems in which over-fitting often occurs. With LSR, we demonstrate consistent improvement in all systems regardless of the extent of over-fitting. We also report competitive accuracy compared with the state of the art.

##### Abstract (translated by Google)
作为一个跨摄像头检索任务，人重新识别遭受不同相机造成的图像风格变化。该技术通过学习相机不变描述符子空间隐含地解决了这个问题。在本文中，我们通过引入相机风格（CamStyle）适应性来明确地考虑这个挑战。 CamStyle可以作为一种数据增强方法来平滑相机风格差异。具体来说，通过CycleGAN，标记的训练图像可以被转移到每个相机，并且与原始训练样本一起形成增强训练集合。这种方法在增加数据多样性的同时，也会产生相当程度的噪音。为了减轻噪声的影响，采用标签平滑正则化（LSR）。我们的方法的香草版本（没有LSR）在少数相机系统中经常发生过度拟合，表现相当好。通过LSR，我们证明了所有系统的持续改进，不管过度的程度如何。与最先进的技术相比，我们也报告了竞争的准确性。

##### URL
[https://arxiv.org/abs/1711.10295](https://arxiv.org/abs/1711.10295)

##### PDF
[https://arxiv.org/pdf/1711.10295](https://arxiv.org/pdf/1711.10295)

