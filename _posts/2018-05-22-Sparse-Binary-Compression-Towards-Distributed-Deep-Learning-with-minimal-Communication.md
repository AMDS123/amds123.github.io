---
layout: post
title: "Sparse Binary Compression: Towards Distributed Deep Learning with minimal Communication"
date: 2018-05-22 17:54:13
categories: arXiv_AI
tags: arXiv_AI Sparse CNN Deep_Learning
author: Felix Sattler, Simon Wiedemann, Klaus-Robert Müller, Wojciech Samek
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, progressively larger deep neural networks are trained on ever growing data corpora. As this trend is only going to increase in the future, distributed training schemes are becoming increasingly relevant. A major issue in distributed training is the limited communication bandwidth between contributing nodes or prohibitive communication cost in general. These challenges become even more pressing, as the number of computation nodes increases. To counteract this development we propose sparse binary compression (SBC), a compression framework that allows for a drastic reduction of communication cost for distributed training. SBC combines existing techniques of communication delay and gradient sparsification with a novel binarization method and optimal weight update encoding to push compression gains to new limits. By doing so, our method also allows us to smoothly trade-off gradient sparsity and temporal sparsity to adapt to the requirements of the learning task. Our experiments show, that SBC can reduce the upstream communication on a variety of convolutional and recurrent neural network architectures by more than four orders of magnitude without significantly harming the convergence speed in terms of forward-backward passes. For instance, we can train ResNet50 on ImageNet in the same number of iterations to the baseline accuracy, using $\times 3531$ less bits or train it to a $1\%$ lower accuracy using $\times 37208$ less bits. In the latter case, the total upstream communication required is cut from 125 terabytes to 3.35 gigabytes for every participating client.

##### Abstract (translated by Google)
目前，越来越大的深度神经网络在不断增长的数据语料库上得到训练。由于这种趋势在将来只会增加，分布式培训计划正变得越来越重要。分布式培训的一个主要问题是通常贡献节点之间的通信带宽有限或通信成本过高。随着计算节点数量的增加，这些挑战变得更加迫切。为了抵制这种发展，我们提出了稀疏二进制压缩（SBC），这是一种压缩框架，可以大幅降低分布式训练的通信成本。 SBC将现有的通信延迟和梯度稀疏技术与新颖的二值化方法和最佳重量更新编码相结合，将压缩增益推至新的极限。通过这样做，我们的方法还可以平滑地权衡梯度稀疏性和时间稀疏性，以适应学习任务的需求。我们的实验表明，SBC可以将各种卷积和递归神经网络架构上的上游通信减少四个数量级以上，而不会明显损害前向后向通过的收敛速度。例如，我们可以在ImageNet上以相同的迭代次数在基线精度上训练ResNet50，使用$ \ times 3531 $ less bits，或者使用$ \ times 37208 $ less位来训练它到$ 1 \％$更低的精度。在后一种情况下，对于每个参与客户，所需的总上游通信量从125 TB减少到3.35 GB。

##### URL
[https://arxiv.org/abs/1805.08768](https://arxiv.org/abs/1805.08768)

##### PDF
[https://arxiv.org/pdf/1805.08768](https://arxiv.org/pdf/1805.08768)

