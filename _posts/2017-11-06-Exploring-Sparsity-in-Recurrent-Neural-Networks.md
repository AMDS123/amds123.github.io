---
layout: post
title: "Exploring Sparsity in Recurrent Neural Networks"
date: 2017-11-06 22:10:47
categories: arXiv_CL
tags: arXiv_CL Sparse Inference RNN
author: Sharan Narang, Erich Elsen, Gregory Diamos, Shubho Sengupta
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNN) are widely used to solve a variety of problems and as the quantity of data and the amount of available compute have increased, so have model sizes. The number of parameters in recent state-of-the-art networks makes them hard to deploy, especially on mobile phones and embedded devices. The challenge is due to both the size of the model and the time it takes to evaluate it. In order to deploy these RNNs efficiently, we propose a technique to reduce the parameters of a network by pruning weights during the initial training of the network. At the end of training, the parameters of the network are sparse while accuracy is still close to the original dense neural network. The network size is reduced by 8x and the time required to train the model remains constant. Additionally, we can prune a larger dense network to achieve better than baseline performance while still reducing the total number of parameters significantly. Pruning RNNs reduces the size of the model and can also help achieve significant inference time speed-up using sparse matrix multiply. Benchmarks show that using our technique model size can be reduced by 90% and speed-up is around 2x to 7x.

##### Abstract (translated by Google)
递归神经网络（RNN）被广泛用于解决各种问题，随着数据量和可用计算量的增加，模型大小也随之增加。近来最先进的网络中的参数数量使其难以部署，特别是在移动电话和嵌入式设备上。面临的挑战是由于模型的大小和评估所需的时间。为了有效地部署这些RNN，我们提出了一种在网络初始训练期间通过削减权重来减少网络参数的技术。在训练结束时，网络的参数是稀疏的，而精度仍然接近于原始稠密神经网络。网络规模减少了8倍，训练模型所需的时间保持不变。另外，我们可以修剪一个更大的密集网络，以获得比基准性能更好的效果，同时仍然显着减少参数总数。修剪RNN减小了模型的大小，并且还可以使用稀疏矩阵乘法帮助实现显着的推理时间加速。基准测试表明，使用我们的技术模型大小可以减少90％，速度提高约2倍到7倍。

##### URL
[https://arxiv.org/abs/1704.05119](https://arxiv.org/abs/1704.05119)

##### PDF
[https://arxiv.org/pdf/1704.05119](https://arxiv.org/pdf/1704.05119)

