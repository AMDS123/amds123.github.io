---
layout: post
title: "MobileFaceNets: Efficient CNNs for Accurate Real-time Face Verification on Mobile Devices"
date: 2018-05-28 02:38:01
categories: arXiv_CV
tags: arXiv_CV Face Inference
author: Sheng Chen, Yang Liu, Xiang Gao, Zhen Han
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we proposed a class of extremely efficient CNN models, MobileFaceNets, which use less than 1 million parameters and are specifically tailored for high-accuracy real-time face verification on mobile and embedded devices. We first make a simple analysis on the weakness of common mobile networks for face verification. The weakness has been well overcome by our specifically designed MobileFaceNets. Under the same experimental conditions, our MobileFaceNets achieve significantly superior accuracy as well as more than 2 times actual speedup over MobileNetV2. After trained by ArcFace loss on the refined MS-Celeb-1M from scratch, our single MobileFaceNet model of 4.0MB size achieves 99.55% face verification accuracy on LFW and 92.59% TAR@FAR1e-6 on MegaFace Challenge 1, which is even comparable to some state-of-the-art big CNN models of hundreds MB size. The fastest one of our MobileFaceNets has an actual inference time of 18 milliseconds on a mobile phone. Our experiments on LFW, AgeDB, and MegaFace show that our MobileFaceNets achieve significantly improved efficiency compared with state-of-the-art lightweight and mobile CNNs for face verification.

##### Abstract (translated by Google)
在本文中，我们提出了一类极其高效的CNN模型MobileFaceNets，它使用的参数少于100万，专门为移动和嵌入式设备上的高精度实时人脸验证量身定制。我们首先对普通移动网络面部验证的弱点做一个简单的分析。我们专门设计的MobileFaceNets已经很好地克服了这个弱点。在相同的实验条件下，我们的MobileFaceNets比MobileNetV2实现了更高的精度以及超过2倍的实际加速比。经过精致MS-Celeb-1M的ArcFace损失培训后，4.0MB大小的单一MobileFaceNet模型在LFW上的面部验证准确率达到99.55％，在MegaFace Challenge 1上达到92.59％TAR @ FAR1e-6，这甚至可以与一些数百MB大小的现代艺术大型CNN模型。我们最快的MobileFaceNets在手机上的实际推断时间为18毫秒。我们在LFW，AgeDB和MegaFace上的实验表明，与最先进的轻量级和移动CNN进行人脸验证相比，我们的MobileFaceNets实现了显着提高的效率。

##### URL
[http://arxiv.org/abs/1804.07573](http://arxiv.org/abs/1804.07573)

##### PDF
[http://arxiv.org/pdf/1804.07573](http://arxiv.org/pdf/1804.07573)

