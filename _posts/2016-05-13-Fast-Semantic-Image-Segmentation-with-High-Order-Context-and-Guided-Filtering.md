---
layout: post
title: "Fast Semantic Image Segmentation with High Order Context and Guided Filtering"
date: 2016-05-13 07:21:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference
author: Falong Shen, Gang Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a fast and accurate semantic image segmentation approach that encodes not only the discriminative features from deep neural networks, but also the high-order context compatibility among adjacent objects as well as low level image features. We formulate the underlying problem as the conditional random field that embeds local feature extraction, clique potential construction, and guided filtering within the same framework, and provide an efficient coarse-to-fine solver. At the coarse level, we combine local feature representation and context interaction using a deep convolutional network, and directly learn the interaction from high order cliques with a message passing routine, avoiding time-consuming explicit graph inference for joint probability distribution. At the fine level, we introduce a guided filtering interpretation for the mean field algorithm, and achieve accurate object boundaries with 100+ faster than classic learning methods. The two parts are connected and jointly trained in an end-to-end fashion. Experimental results on Pascal VOC 2012 dataset have shown that the proposed algorithm outperforms the state-of-the-art, and that it achieves the rank 1 performance at the time of submission, both of which prove the effectiveness of this unified framework for semantic image segmentation.

##### Abstract (translated by Google)
本文描述了一种快速而准确的语义图像分割方法，不仅可以对来自深度神经网络的判别特征进行编码，而且还可以对相邻对象之间的高阶上下文兼容性以及低级别图像特征进行编码。我们把潜在的问题作为在同一个框架内嵌入局部特征提取，团体潜在构建和引导过滤的条件随机场，并提供一个有效的从粗到精的求解器。在粗糙的层次上，我们将深度卷积网络的局部特征表示和上下文交互相结合，直接通过消息传递例程来学习高阶派系之间的交互，避免了耗时的显式图推理对联合概率分布的影响。在精细水平上，我们引入了平均场算法的引导滤波解释，并且比传统学习方法快100倍以上，实现了精确的对象边界。这两个部分以端到端的方式相互连接和共同训练。 Pascal VOC 2012数据集的实验结果表明，所提出的算法性能优于现有技术，并且在提交时达到了1级的性能，两者都证明了这种统一的语义图像框架的有效性分割。

##### URL
[https://arxiv.org/abs/1605.04068](https://arxiv.org/abs/1605.04068)

##### PDF
[https://arxiv.org/pdf/1605.04068](https://arxiv.org/pdf/1605.04068)

