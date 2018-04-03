---
layout: post
title: "Fixed-sized representation learning from Offline Handwritten Signatures of different sizes"
date: 2018-04-02 11:07:01
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning
author: Luiz G. Hafemann, Robert Sabourin, Luiz S. Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
Methods for learning feature representations for Offline Handwritten Signature Verification have been successfully proposed in recent literature, using Deep Convolutional Neural Networks to learn representations from signature pixels. Such methods reported large performance improvements compared to handcrafted feature extractors. However, they also introduced an important constraint: the inputs to the neural networks must have a fixed size, while signatures vary significantly in size between different users. In this paper we propose addressing this issue by learning a fixed-sized representation from variable-sized signatures by modifying the network architecture, using Spatial Pyramid Pooling. We also investigate the impact of the resolution of the images used for training, and the impact of adapting (fine-tuning) the representations to new operating conditions (different acquisition protocols, such as writing instruments and scan resolution). On the GPDS dataset, we achieve results comparable with the state-of-the-art, while removing the constraint of having a maximum size for the signatures to be processed. We also show that using higher resolutions (300 or 600dpi) can improve performance when skilled forgeries from a subset of users are available for feature learning, but lower resolutions (around 100dpi) can be used if only genuine signatures are used. Lastly, we show that fine-tuning can improve performance when the operating conditions change.

##### Abstract (translated by Google)
在最近的文献中已经成功地提出了用于离线手写签名验证的学习特征表示的方法，使用深度卷积神经网络来学习来自签名像素的表示。与手工制作的特征提取器相比，这些方法报告有大的性能改进。然而，他们还引入了一个重要的约束：神经网络的输入必须具有固定的大小，而不同用户之间的签名大小差别很大。在本文中，我们提出通过使用空间金字塔池来修改网络体系结构，通过从可变大小的签名中学习固定大小的表示来解决这个问题。我们还研究了用于训练的图像分辨率的影响，以及适应（微调）表示对新操作条件（不同的采集协议，如书写工具和扫描分辨率）的影响。在GPDS数据集上，我们实现了与最先进技术相媲美的结果，同时消除了要处理签名的最大大小的限制。我们还表明，使用更高的分辨率（300或600dpi）可以提高性能，当来自用户子集的熟练伪造可用于特征学习时，如果只使用真正的签名，则可以使用较低的分辨率（大约100dpi）。最后，我们证明，当操作条件改变时，微调可以提高性能。

##### URL
[http://arxiv.org/abs/1804.00448](http://arxiv.org/abs/1804.00448)

##### PDF
[http://arxiv.org/pdf/1804.00448](http://arxiv.org/pdf/1804.00448)

