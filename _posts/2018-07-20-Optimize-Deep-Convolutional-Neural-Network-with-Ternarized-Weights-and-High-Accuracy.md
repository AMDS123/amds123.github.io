---
layout: post
title: "Optimize Deep Convolutional Neural Network with Ternarized Weights and High Accuracy"
date: 2018-07-20 17:36:05
categories: arXiv_CV
tags: arXiv_CV CNN
author: Zhezhi He, Boqing Gong, Deliang Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolution neural network has achieved great success in many artificial intelligence applications. However, its enormous model size and massive computation cost have become the main obstacle for deployment of such powerful algorithm in the low power and resource-limited embedded systems. As the countermeasure to this problem, in this work, we propose statistical weight scaling and residual expansion methods to reduce the bit-width of the whole network weight parameters to ternary values (i.e. -1, 0, +1), with the objectives to greatly reduce model size, computation cost and accuracy degradation caused by the model compression. With about 16x model compression rate, our ternarized ResNet-32/44/56 could outperform full-precision counterparts by 0.12%, 0.24% and 0.18% on CIFAR- 10 dataset. We also test our ternarization method with AlexNet and ResNet-18 on ImageNet dataset, which both achieve the best top-1 accuracy compared to recent similar works, with the same 16x compression rate. If further incorporating our residual expansion method, compared to the full-precision counterpart, our ternarized ResNet-18 even improves the top-5 accuracy by 0.61% and merely degrades the top-1 accuracy only by 0.42% for the ImageNet dataset, with 8x model compression rate. It outperforms the recent ABC-Net by 1.03% in top-1 accuracy and 1.78% in top-5 accuracy, with around 1.25x higher compression rate and more than 6x computation reduction due to the weight sparsity.

##### Abstract (translated by Google)
深度卷积神经网络在许多人工智能应用中取得了巨大成功。然而，其巨大的模型尺寸和巨大的计算成本已经成为在低功率和资源有限的嵌入式系统中部署这种强大算法的主要障碍。作为该问题的对策，在这项工作中，我们提出统计权重缩放和残差扩展方法，以将整个网络权重参数的比特宽度减少到三元值（即-1,0，+ 1），目标是大大减少了模型压缩造成的模型尺寸，计算成本和精度下降。凭借约16倍的模型压缩率，我们的三角形ResNet-32/44/56在CIFAR-10数据集上的性能优于全精度对应物0.12％，0.24％和0.18％。我们还在ImageNet数据集上使用AlexNet和ResNet-18测试我们的三元化方法，与最近的类似工作相比，它们都具有相同的16倍压缩率，达到了最佳的前1精度。如果进一步结合我们的残余膨胀方法，与全精密对应物相比，我们的三维ResNet-18甚至可以将前5精度提高0.61％，并且仅将ImageNet数据集的前1精度降低0.42％，其中8x模型压缩率。它在前1精度方面优于最近的ABC-Net 1.03％，在前5精度方面优于1.78％，由于重量稀疏，压缩率提高约1.25倍，计算量减少6倍以上。

##### URL
[http://arxiv.org/abs/1807.07948](http://arxiv.org/abs/1807.07948)

##### PDF
[http://arxiv.org/pdf/1807.07948](http://arxiv.org/pdf/1807.07948)

