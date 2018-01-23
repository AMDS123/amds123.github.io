---
layout: post
title: "Staff line Removal using Generative Adversarial Networks"
date: 2018-01-22 15:35:51
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Recognition
author: Aishik Konwer, Ayan Kumar Bhunia, Abir Bhowmick, Ankan Kumar Bhunia, Prithaj Banerjee, Partha Pratim Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Staff line removal is a crucial pre-processing step in Optical Music Recognition. It is a challenging task to simultaneously reduce the noise and also retain the quality of music symbol context in ancient degraded music score images. In this paper we propose a novel approach for staff line removal, based on Generative Adversarial Networks. We convert staff line images into patches and feed them into a U-Net, used as Generator. The Generator intends to produce staff-less images at the output. Then the Discriminator does binary classification and differentiates between the generated fake staff-less image and real ground truth staff less image. For training, we use a Loss function which is a weighted combination of L2 loss and Adversarial loss. L2 loss minimizes the difference between real and fake staff-less image. Adversarial loss helps to retrieve more high quality textures in generated images. Thus our architecture supports solutions which are closer to ground truth and it reflects in our results. For evaluation we consider the ICDAR/GREC 2013 staff removal database. Our method achieves superior performance in comparison to other conventional approaches.

##### Abstract (translated by Google)
光学音乐识别中的人员线删除是一个关键的预处理步骤。同时降低噪声，同时保留古代退化乐谱图像中音乐符号语境的质量也是一项具有挑战性的任务。在本文中，我们提出了一种基于生成敌对网络的人员排队新方法。我们将工作人员的线条图像转换成补丁，并把它们送入U-Net，用作发生器。发生器打算在输出中产生无人影像。然后鉴别者进行二元分类，并区分生成的假人员形象和真实的地面人员形象。对于训练，我们使用损失函数，这是L2损失和对抗性损失的加权组合。 L2损失最大限度地减少了真实和虚假的无人影像之间的差异。对抗性损失有助于在生成的图像中检索更高质量的纹理。因此，我们的架构支持更贴近实际情况的解决方案，并反映在我们的结果中。为了评估，我们考虑了ICDAR / GREC 2013员工移除数据库。与其他传统方法相比，我们的方法实现了卓越的性能。

##### URL
[https://arxiv.org/abs/1801.07141](https://arxiv.org/abs/1801.07141)

##### PDF
[https://arxiv.org/pdf/1801.07141](https://arxiv.org/pdf/1801.07141)

