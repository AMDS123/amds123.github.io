---
layout: post
title: "Unsupervised Learning with Stein's Unbiased Risk Estimator"
date: 2018-05-26 20:01:15
categories: arXiv_CV
tags: arXiv_CV CNN
author: Christopher A. Metzler, Ali Mousavi, Reinhard Heckel, Richard G. Baraniuk
mathjax: true
---

* content
{:toc}

##### Abstract
Learning from unlabeled and noisy data is one of the grand challenges of machine learning. As such, it has seen a flurry of research with new ideas proposed continuously. In this work, we revisit a classical idea: Stein's Unbiased Risk Estimator (SURE). We show that, in the context of image recovery, SURE and its generalizations can be used to train convolutional neural networks (CNNs) for a range of image denoising and recovery problems {\em without any ground truth data.} 
 Specifically, our goal is to reconstruct an image $x$ from a {\em noisy} linear transformation (measurement) of the image. We consider two scenarios: one where no additional data is available and one where we have measurements of other images that are drawn from the same noisy distribution as $x$, but have no access to the clean images. Such is the case, for instance, in the context of medical imaging, microscopy, and astronomy, where noise-less ground truth data is rarely available. 
 We show that in this situation, SURE can be used to estimate the mean-squared-error loss associated with an estimate of $x$. Using this estimate of the loss, we train networks to perform denoising and compressed sensing recovery. In addition, we also use the SURE framework to partially explain and improve upon an intriguing results presented by Ulyanov et al. in "Deep Image Prior": that a network initialized with random weights and fit to a single noisy image can effectively denoise that image.

##### Abstract (translated by Google)
从无标签和嘈杂的数据中学习是机器学习的巨大挑战之一。因此，它不断提出新思路的研究。在这项工作中，我们重新审视了一个经典的想法：Stein的无偏风险评估（SURE）。我们表明，在图像恢复的背景下，SURE及其推广可用于训练卷积神经网络（CNN），用于一系列图像去噪和恢复问题{\ em没有任何地面实况数据。}
 具体而言，我们的目标是从图像的一个{\ em噪声}线性变换（测量）中重建图像$ x $。我们考虑两种情况：一种是没有额外数据可用的情况，另一种情况是我们测量的其他图像的测量值来自与$ x $相同的噪音分布，但无法访问干净的图像。例如，在医学成像，显微镜和天文学的情况下就是这种情况，其中很少有无噪声的地面真实数据。
 我们证明在这种情况下，SURE可以用来估计与$ x $的估计相关的均方误差损失。使用这种损失估计，我们训练网络执行去噪和压缩感知恢复。此外，我们还使用SURE框架对Ulyanov等人提出的有趣结果进行部分解释和改进。在“Deep Image Prior”中：使用随机权重进行初始化并适合单个噪声图像的网络可以有效地消除该图像。

##### URL
[http://arxiv.org/abs/1805.10531](http://arxiv.org/abs/1805.10531)

##### PDF
[http://arxiv.org/pdf/1805.10531](http://arxiv.org/pdf/1805.10531)

