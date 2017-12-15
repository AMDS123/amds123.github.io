---
layout: post
title: "FireCaffe: near-linear acceleration of deep neural network training on compute clusters"
date: 2016-01-08 06:50:36
categories: arXiv_CV
tags: arXiv_CV
author: Forrest N. Iandola, Khalid Ashraf, Matthew W. Moskewicz, Kurt Keutzer
mathjax: true
---

* content
{:toc}

##### Abstract
Long training times for high-accuracy deep neural networks (DNNs) impede research into new DNN architectures and slow the development of high-accuracy DNNs. In this paper we present FireCaffe, which successfully scales deep neural network training across a cluster of GPUs. We also present a number of best practices to aid in comparing advancements in methods for scaling and accelerating the training of deep neural networks. The speed and scalability of distributed algorithms is almost always limited by the overhead of communicating between servers; DNN training is not an exception to this rule. Therefore, the key consideration here is to reduce communication overhead wherever possible, while not degrading the accuracy of the DNN models that we train. Our approach has three key pillars. First, we select network hardware that achieves high bandwidth between GPU servers -- Infiniband or Cray interconnects are ideal for this. Second, we consider a number of communication algorithms, and we find that reduction trees are more efficient and scalable than the traditional parameter server approach. Third, we optionally increase the batch size to reduce the total quantity of communication during DNN training, and we identify hyperparameters that allow us to reproduce the small-batch accuracy while training with large batch sizes. When training GoogLeNet and Network-in-Network on ImageNet, we achieve a 47x and 39x speedup, respectively, when training on a cluster of 128 GPUs.

##### Abstract (translated by Google)
高精度深度神经网络（DNN）的训练时间长，阻碍了对新的DNN体系结构的研究，并且导致高精度DNN的开发速度减慢。在本文中，我们展示了FireCaffe，它成功地通过GPU集群扩展了深度神经网络训练。我们还提出了一些最佳实践，以帮助比较在缩放和加速深度神经网络训练的方法方面的进展。分布式算法的速度和可扩展性几乎总是受到服务器之间通信开销的限制。 DNN培训不是这个规则的例外。因此，这里主要考虑的是尽可能减少通信开销，同时不降低我们训练的DNN模型的精度。我们的方法有三个关键支柱。首先，我们选择在GPU服务器之间实现高带宽的网络硬件 -  Infiniband或Cray互连对此非常理想。其次，我们考虑了一些通信算法，我们发现，减少树比传统的参数服务器方法更有效率和可扩展性。第三，我们可以选择增加批量以减少DNN训练期间的总通信量，并且确定超参数，使我们能够在大批量训练的同时重现小批量的精度。在ImageNet上培训GoogLeNet和Network-in-Network时，在128个GPU集群上训练时，分别实现了47倍和39倍的加速。

##### URL
[https://arxiv.org/abs/1511.00175](https://arxiv.org/abs/1511.00175)

##### PDF
[https://arxiv.org/pdf/1511.00175](https://arxiv.org/pdf/1511.00175)

