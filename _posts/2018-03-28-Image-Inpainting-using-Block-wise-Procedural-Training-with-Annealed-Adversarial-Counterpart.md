---
layout: post
title: "Image Inpainting using Block-wise Procedural Training with Annealed Adversarial Counterpart"
date: 2018-03-28 02:28:01
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Chao Yang, Yuhang Song, Xiaofeng Liu, Qingming Tang, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep generative models have shown promising potential in image inpanting, which refers to the task of predicting missing pixel values of an incomplete image using the known context. However, existing methods can be slow or generate unsatisfying results with easily detectable flaws. In addition, there is often perceivable discontinuity near the holes and require further post-processing to blend the results. We present a new approach to address the difficulty of training a very deep generative model to synthesize high-quality photo-realistic inpainting. Our model uses conditional generative adversarial networks (conditional GANs) as the backbone, and we introduce a novel block-wise procedural training scheme to stabilize the training while we increase the network depth. We also propose a new strategy called adversarial loss annealing to reduce the artifacts. We further describe several losses specifically designed for inpainting and show their effectiveness. Extensive experiments and user-study show that our approach outperforms existing methods in several tasks such as inpainting, face completion and image harmonization. Finally, we show our framework can be easily used as a tool for interactive guided inpainting, demonstrating its practical value to solve common real-world challenges.

##### Abstract (translated by Google)
深度生成模型的最新进展已经显示出潜在的图像投影潜力，这是指使用已知上下文预测未完成图像的像素值缺失的任务。但是，现有的方法可能会变慢或产生不令人满意的结果，并且易于检测到缺陷。另外，孔附近通常会有可察觉的不连续性，需要进一步的后处理来混合结果。我们提出了一种新的方法来解决训练一个非常深刻的生成模型以综合高质量照片级逼真修补的难度。我们的模型使用条件生成对抗网络（条件GAN）作为骨干，并且我们引入了一种新颖的基于块的程序训练方案来稳定训练，同时增加网络深度。我们还提出了一种叫做敌对损失退火的新策略来减少伪像。我们进一步描述了几个专门用于修补和显示效果的损失。广泛的实验和用户研究表明，我们的方法在诸如修补，完成面部和图像协调等几项任务中优于现有方法。最后，我们展示了我们的框架可以很容易地用作交互式引导修补的工具，展示了它解决常见现实世界挑战的实用价值。

##### URL
[https://arxiv.org/abs/1803.08943](https://arxiv.org/abs/1803.08943)

##### PDF
[https://arxiv.org/pdf/1803.08943](https://arxiv.org/pdf/1803.08943)

