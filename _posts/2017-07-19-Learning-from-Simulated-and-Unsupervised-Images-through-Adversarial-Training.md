---
layout: post
title: "Learning from Simulated and Unsupervised Images through Adversarial Training"
date: 2017-07-19 21:24:52
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Pose_Estimation Quantitative
author: Ashish Shrivastava, Tomas Pfister, Oncel Tuzel, Josh Susskind, Wenda Wang, Russ Webb
mathjax: true
---

* content
{:toc}

##### Abstract
With recent progress in graphics, it has become more tractable to train models on synthetic images, potentially avoiding the need for expensive annotations. However, learning from synthetic images may not achieve the desired performance due to a gap between synthetic and real image distributions. To reduce this gap, we propose Simulated+Unsupervised (S+U) learning, where the task is to learn a model to improve the realism of a simulator's output using unlabeled real data, while preserving the annotation information from the simulator. We develop a method for S+U learning that uses an adversarial network similar to Generative Adversarial Networks (GANs), but with synthetic images as inputs instead of random vectors. We make several key modifications to the standard GAN algorithm to preserve annotations, avoid artifacts, and stabilize training: (i) a 'self-regularization' term, (ii) a local adversarial loss, and (iii) updating the discriminator using a history of refined images. We show that this enables generation of highly realistic images, which we demonstrate both qualitatively and with a user study. We quantitatively evaluate the generated images by training models for gaze estimation and hand pose estimation. We show a significant improvement over using synthetic images, and achieve state-of-the-art results on the MPIIGaze dataset without any labeled real data.

##### Abstract (translated by Google)
随着最近在图形上的进步，在合成图像上训练模型变得更加容易处理，可能避免了昂贵的注释的需要。然而，由于合成图像和真实图像分布之间的差距，从合成图像学习可能不能达到期望的性能。为了减少这种差距，我们提出了模拟+无监督（S + U）学习，其中的任务是学习模型，以提高模拟器输出的真实性，使用未标记的真实数据，同时保留模拟器的注释信息。我们开发了一种S + U学习方法，使用类似于生成敌对网络（GAN）的对抗网络，但是使用合成图像作为输入而不是随机向量。我们对标准GAN算法进行了几个关键的修改，以保留注释，避免伪像，并稳定训练：（i）“自我正规化”术语，（ii）局部对抗性损失，以及（iii）使用历史更新鉴别器精致的图像。我们表明，这使得能够生成高度逼真的图像，我们在定性和用户研究中都展示了这一点。我们定量评估生成的图像通过训练模型的注视估计和手势估计。与使用合成图像相比，我们显示出了显着的改进，并且在MPIIGaze数据集上实现了最新的结果，而没有任何标记的真实数据。

##### URL
[https://arxiv.org/abs/1612.07828](https://arxiv.org/abs/1612.07828)

##### PDF
[https://arxiv.org/pdf/1612.07828](https://arxiv.org/pdf/1612.07828)

