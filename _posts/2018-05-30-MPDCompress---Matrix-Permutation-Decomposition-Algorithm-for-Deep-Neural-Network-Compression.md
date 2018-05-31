---
layout: post
title: "MPDCompress - Matrix Permutation Decomposition Algorithm for Deep Neural Network Compression"
date: 2018-05-30 17:01:30
categories: arXiv_AI
tags: arXiv_AI Inference
author: Lazar Supic, Rawan Naous, Ranko Sredojevic, Aleksandra Faust, Vladimir Stojanovic
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have become the state-of-the-art technique for machine learning tasks in various applications. However, due to their size and the computational complexity, large DNNs are not readily deployable on edge devices in real-time. To manage complexity and accelerate computation, network compression techniques based on pruning and quantization have been proposed and shown to be effective in reducing network size. However, such network compression can result in irregular matrix structures that are mismatched with modern hardware-accelerated platforms, such as graphics processing units (GPUs) designed to perform the DNN matrix multiplications in a structured (block-based) way. We propose MPDCompress, a DNN compression algorithm based on matrix permutation decomposition via random mask generation. In-training application of the masks molds the synaptic weight connection matrix to a sub-graph separation format. Aided by the random permutations, a hardware-desirable block matrix is generated, allowing for a more efficient implementation and compression of the network. To show versatility, we empirically verify MPDCompress on several network models, compression rates, and image datasets. On the LeNet 300-100 model (MNIST dataset), Deep MNIST, and CIFAR10, we achieve 10 X network compression with less than 1% accuracy loss compared to non-compressed accuracy performance. On AlexNet for the full ImageNet ILSVRC-2012 dataset, we achieve 8 X network compression with less than 1% accuracy loss, with top-5 and top-1 accuracies of 79.6% and 56.4%, respectively. Finally, we observe that the algorithm can offer inference speedups across various hardware platforms, with 4 X faster operation achieved on several mobile GPUs.

##### Abstract (translated by Google)
深度神经网络（DNN）已成为各种应用中机器学习任务的最先进技术。但是，由于它们的大小和计算复杂性，大DNN不容易实时部署在边缘设备上。为了管理复杂性并加速计算，已经提出了基于剪枝和量化的网络压缩技术，并且显示其在减小网络尺寸方面是有效的。然而，这样的网络压缩会导致不规则的矩阵结构与现代硬件加速平台（例如被设计为以结构化（基于块）的方式执行DNN矩阵乘法的图形处理单元（GPU））不匹配。我们提出MPDCompress，一种基于通过随机掩模生成的矩阵置换分解的DNN压缩算法。面罩的训练中应用将突触权重连接矩阵模制为子图分离格式。在随机置换的帮助下，生成了一个硬件理想的块矩阵，从而实现了更高效的网络实现和压缩。为了展示多功能性，我们凭经验在多种网络模型，压缩率和图像数据集上验证了MPDCompress。在LeNet 300-100型号（MNIST数据集），Deep MNIST和CIFAR10上，我们实现了10倍网络压缩，与非压缩精度性能相比，精度损失小于1％。在完整的ImageNet ILSVRC-2012数据集的AlexNet上，我们实现了8倍网络压缩，准确度损失小于1％，前5位和前1位精度分别为79.6％和56.4％。最后，我们观察到该算法可以提供跨各种硬件平台的推理加速，在几个移动GPU上实现了4倍的更快速操作。

##### URL
[https://arxiv.org/abs/1805.12085](https://arxiv.org/abs/1805.12085)

##### PDF
[https://arxiv.org/pdf/1805.12085](https://arxiv.org/pdf/1805.12085)

