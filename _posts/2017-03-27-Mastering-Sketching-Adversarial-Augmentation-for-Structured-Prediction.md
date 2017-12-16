---
layout: post
title: "Mastering Sketching: Adversarial Augmentation for Structured Prediction"
date: 2017-03-27 08:23:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Inference Prediction
author: Edgar Simo-Serra, Satoshi Iizuka, Hiroshi Ishikawa
mathjax: true
---

* content
{:toc}

##### Abstract
We present an integral framework for training sketch simplification networks that convert challenging rough sketches into clean line drawings. Our approach augments a simplification network with a discriminator network, training both networks jointly so that the discriminator network discerns whether a line drawing is a real training data or the output of the simplification network, which in turn tries to fool it. This approach has two major advantages. First, because the discriminator network learns the structure in line drawings, it encourages the output sketches of the simplification network to be more similar in appearance to the training sketches. Second, we can also train the simplification network with additional unsupervised data, using the discriminator network as a substitute teacher. Thus, by adding only rough sketches without simplified line drawings, or only line drawings without the original rough sketches, we can improve the quality of the sketch simplification. We show how our framework can be used to train models that significantly outperform the state of the art in the sketch simplification task, despite using the same architecture for inference. We additionally present an approach to optimize for a single image, which improves accuracy at the cost of additional computation time. Finally, we show that, using the same framework, it is possible to train the network to perform the inverse problem, i.e., convert simple line sketches into pencil drawings, which is not possible using the standard mean squared error loss. We validate our framework with two user tests, where our approach is preferred to the state of the art in sketch simplification 92.3% of the time and obtains 1.2 more points on a scale of 1 to 5.

##### Abstract (translated by Google)
我们提供了一个完整的框架，用于培训草图简化网络，将具有挑战性的粗略草图转化为清晰的线条图。我们的方法使用鉴别器网络来扩展简化网络，联合训练两个网络，使得鉴别器网络识别线条图是实际的训练数据还是简化网络的输出，这反过来又试图欺骗它。这种方法有两个主要优点。首先，由于鉴别器网络在线图中学习结构，鼓励简化网络的输出示意图与训练示意图在外观上更相似。其次，我们还可以用另外的无监督数据来训练简化网络，使用鉴别网络作为替代老师。因此，通过仅添加没有简化的线条图的粗略草图，或者仅添加没有原始草图的线条图，我们可以提高草图简化的质量。尽管使用相同的体系结构进行推理，但我们展示了如何使用我们的框架来训练在草图简化任务中显着优于现有技术的模型。我们另外提出了一种优化单个图像的方法，其以额外的计算时间为代价提高了精度。最后，我们表明，使用相同的框架，可以训练网络来执行反演问题，即将简单的线草图转换成铅笔图，这是使用标准均方误差损失所不可能的。我们用两个用户测试来验证我们的框架，其中我们的方法比草图简化的状态优先于92.3％的时间，并且在1到5的范围内获得1.2个更多的点。

##### URL
[https://arxiv.org/abs/1703.08966](https://arxiv.org/abs/1703.08966)

##### PDF
[https://arxiv.org/pdf/1703.08966](https://arxiv.org/pdf/1703.08966)

