---
layout: post
title: "Deep Adversarial Context-Aware Landmark Detection for Ultrasound Imaging"
date: 2018-05-28 02:27:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Deep_Learning Detection
author: Ahmet Tuysuzoglu, Jeremy Tan, Kareem Eissa, Atilla P. Kiraly, Mamadou Diallo, Ali Kamen
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time localization of prostate gland in trans-rectal ultrasound images is a key technology that is required to automate the ultrasound guided prostate biopsy procedures. In this paper, we propose a new deep learning based approach which is aimed at localizing several prostate landmarks efficiently and robustly. We propose a multitask learning approach primarily to make the overall algorithm more contextually aware. In this approach, we not only consider the explicit learning of landmark locations, but also build-in a mechanism to learn the contour of the prostate. This multitask learning is further coupled with an adversarial arm to promote the generation of feasible structures. We have trained this network using ~4000 labeled trans-rectal ultrasound images and tested on an independent set of images with ground truth landmark locations. We have achieved an overall Dice score of 92.6% for the adversarially trained multitask approach, which is significantly better than the Dice score of 88.3% obtained by only learning of landmark locations. The overall mean distance error using the adversarial multitask approach has also improved by 20% while reducing the standard deviation of the error compared to learning landmark locations only. In terms of computational complexity both approaches can process the images in real-time using standard computer with a standard CUDA enabled GPU.

##### Abstract (translated by Google)
前列腺在经直肠超声图像中的实时定位是使超声引导的前列腺活检程序自动化所需的关键技术。在本文中，我们提出了一种新的基于深度学习的方法，其目的是有效和稳健地定位几个前列腺地标。我们提出一种多任务学习方法，主要是为了使整体算法更具上下文意识。在这种方法中，我们不仅考虑了地标位置的显式学习，还建立了学习前列腺轮廓的机制。这种多任务学习进一步与敌对的手段相结合，以促进可行结构的产生。我们已经使用〜4000标记的经直肠超声图像训练了该网络，并在具有地面真实地标位置的独立图像集上进行了测试。我们在对手训练的多任务方法中获得了92.6％的整体Dice分数，显着优于仅通过学习地标位置获得的Dice分数为88.3％。与仅学习地标位置相比，使用敌对多任务方法的整体平均距离误差也提高了20％，同时减少了误差的标准偏差。在计算复杂性方面，两种方法都可以使用标准CUDA GPU实时处理图像。

##### URL
[http://arxiv.org/abs/1805.10737](http://arxiv.org/abs/1805.10737)

##### PDF
[http://arxiv.org/pdf/1805.10737](http://arxiv.org/pdf/1805.10737)

