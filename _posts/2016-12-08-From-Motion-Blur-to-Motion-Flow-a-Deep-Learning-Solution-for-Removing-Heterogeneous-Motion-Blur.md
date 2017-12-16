---
layout: post
title: "From Motion Blur to Motion Flow: a Deep Learning Solution for Removing Heterogeneous Motion Blur"
date: 2016-12-08 10:05:57
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Dong Gong, Jie Yang, Lingqiao Liu, Yanning Zhang, Ian Reid, Chunhua Shen, Anton van den Hengel, Qinfeng Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Removing pixel-wise heterogeneous motion blur is challenging due to the ill-posed nature of the problem. The predominant solution is to estimate the blur kernel by adding a prior, but the extensive literature on the subject indicates the difficulty in identifying a prior which is suitably informative, and general. Rather than imposing a prior based on theory, we propose instead to learn one from the data. Learning a prior over the latent image would require modeling all possible image content. The critical observation underpinning our approach is thus that learning the motion flow instead allows the model to focus on the cause of the blur, irrespective of the image content. This is a much easier learning task, but it also avoids the iterative process through which latent image priors are typically applied. Our approach directly estimates the motion flow from the blurred image through a fully-convolutional deep neural network (FCN) and recovers the unblurred image from the estimated motion flow. Our FCN is the first universal end-to-end mapping from the blurred image to the dense motion flow. To train the FCN, we simulate motion flows to generate synthetic blurred-image-motion-flow pairs thus avoiding the need for human labeling. Extensive experiments on challenging realistic blurred images demonstrate that the proposed method outperforms the state-of-the-art.

##### Abstract (translated by Google)
由于问题的不合适性质，去除像素方面的异质运动模糊是具有挑战性的。主要的解决方案是通过添加一个先验来估计模糊核，但是关于这个主题的大量文献表明难以确定一个适当的信息和一般的先验。我们不是建立在理论基础上的先验，而是建议从数据中学习一个。在潜像上学习先验需要对所有可能的图像内容进行建模。因此，支持我们方法的关键观察是，学习运动流而不是使图像内容与模型关注模糊的原因。这是一个更容易的学习任务，但它也避免了通常应用潜像先验的迭代过程。我们的方法直接从模糊图像通过全卷积深度神经网络（FCN）估计运动流，并从估计的运动流中恢复未模糊的图像。我们的FCN是第一个从模糊图像到密集运动流程的通用端到端映射。为了训练FCN，我们模拟运动流来生成合成的模糊图像运动流对，从而避免了对人类标记的需要。对具有挑战性的逼真模糊图像进行大量的实验表明，所提出的方法胜过最先进的技术。

##### URL
[https://arxiv.org/abs/1612.02583](https://arxiv.org/abs/1612.02583)

##### PDF
[https://arxiv.org/pdf/1612.02583](https://arxiv.org/pdf/1612.02583)

