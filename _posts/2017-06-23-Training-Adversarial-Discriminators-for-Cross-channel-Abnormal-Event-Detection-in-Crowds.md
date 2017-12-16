---
layout: post
title: "Training Adversarial Discriminators for Cross-channel Abnormal Event Detection in Crowds"
date: 2017-06-23 13:06:33
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative Detection
author: Mahdyar Ravanbakhsh, Enver Sangineto, Moin Nabi, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Abnormal crowd behaviour detection attracts a large interest due to its importance in video surveillance scenarios. However, the ambiguity and the lack of sufficient "abnormal" ground truth data makes end-to-end training of large deep networks hard in this domain. In this paper we propose to use Generative Adversarial Nets (GANs), which are trained to generate only the "normal" distribution of the data. During the adversarial GAN training, a discriminator "D" is used as a supervisor for the generator network "G" and vice versa. At testing time we use "D" to solve our discriminative task (abnormality detection), where "D" has been trained without the need of manually-annotated abnormal data. Moreover, in order to prevent "G" learn a trivial identity function, we use a cross-channel approach, forcing "G" to transform raw-pixel data in motion information and vice versa. The quantitative results on standard benchmarks show that our method outperforms previous state-of-the-art methods in both the frame-level and the pixel-level evaluation.

##### Abstract (translated by Google)
异常人群行为检测由于其在视频监控场景中的重要性而引起广泛关注。然而，模糊性和缺乏足够的“异常”的地面真实数据，使得这个领域的大型深度网络端到端的训练变得困难。在本文中，我们建议使用生成敌对​​网络（GAN），这些网络被训练成仅产生数据的“正常”分布。在对抗性的GAN训练期间，鉴别器“D”被用作发生器网络“G”的管理者，反之亦然。在测试时间，我们用“D”来解决我们的区分任务（异常检测），其中“D”已经被训练而不需要手动注释的异常数据。此外，为了防止“G”学习一个微不足道的身份函数，我们使用交叉通道的方法，迫使“G”运动信息中的原始像素数据变换，反之亦然。标准基准的定量结果表明，我们的方法在帧级和像素级评估中均优于先前的最新方法。

##### URL
[https://arxiv.org/abs/1706.07680](https://arxiv.org/abs/1706.07680)

##### PDF
[https://arxiv.org/pdf/1706.07680](https://arxiv.org/pdf/1706.07680)

