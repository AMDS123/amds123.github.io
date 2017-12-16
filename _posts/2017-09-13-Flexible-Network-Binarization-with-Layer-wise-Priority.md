---
layout: post
title: "Flexible Network Binarization with Layer-wise Priority"
date: 2017-09-13 14:14:15
categories: arXiv_CV
tags: arXiv_CV Detection
author: Lixue Zhuang, Yi Xu, Bingbing Ni, Hongteng Xu
mathjax: true
---

* content
{:toc}

##### Abstract
How to effectively approximate real-valued parameters with binary codes plays a central role in neural network binarization. In this work, we reveal an important fact that binarizing different layers has a widely-varied effect on the compression ratio of network and the loss of performance. Based on this fact, we propose a novel and flexible neural network binarization method by introducing the concept of layer-wise priority which binarizes parameters in inverse order of their layer depth. In each training step, our method selects a specific network layer, minimizes the discrepancy between the original real-valued weights and its binary approximations, and fine-tunes the whole network accordingly. During the iteration of the above process, it is significant that we can flexibly decide whether to binarize the remaining floating layers or not and explore a trade-off between the loss of performance and the compression ratio of model. The resulting binary network is applied for efficient pedestrian detection. Extensive experimental results on several benchmarks show that under the same compression ratio, our method achieves much lower miss rate and faster detection speed than the state-of-the-art neural network binarization method.

##### Abstract (translated by Google)
如何用二进制码有效逼近实值参数在神经网络二值化过程中起着至关重要的作用。在这项工作中，我们揭示了一个重要的事实，即不同层次的二值化对网络的压缩比和性能的损失有着广泛的影响。基于这个事实，我们提出了一种新颖灵活的神经网络二值化方法，引入了层次优先的概念，以参数的深度相反的顺序对参数进行二值化。在每个训练步骤中，我们的方法选择一个特定的网络层，最小化原始实值权重和二进制近似值之间的差异，并相应地调整整个网络。在上述过程的迭代过程中，我们可以灵活地决定是否对剩余浮层进行二值化处理，并探索性能损失与模型压缩比之间的折衷。由此产生的二进制网络被用于有效的行人检测。在多个基准测试中的广泛的实验结果表明，在相同的压缩比下，我们的方法比现有技术的神经网络二值化方法具有更低的失败率和更快的检测速度。

##### URL
[https://arxiv.org/abs/1709.04344](https://arxiv.org/abs/1709.04344)

##### PDF
[https://arxiv.org/pdf/1709.04344](https://arxiv.org/pdf/1709.04344)

