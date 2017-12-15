---
layout: post
title: "Deep FisherNet for Object Classification"
date: 2016-07-31 03:56:30
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Peng Tang, Xinggang Wang, Baoguang Shi, Xiang Bai, Wenyu Liu, Zhuowen Tu
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the great success of convolutional neural networks (CNN) for the image classification task on datasets like Cifar and ImageNet, CNN's representation power is still somewhat limited in dealing with object images that have large variation in size and clutter, where Fisher Vector (FV) has shown to be an effective encoding strategy. FV encodes an image by aggregating local descriptors with a universal generative Gaussian Mixture Model (GMM). FV however has limited learning capability and its parameters are mostly fixed after constructing the codebook. To combine together the best of the two worlds, we propose in this paper a neural network structure with FV layer being part of an end-to-end trainable system that is differentiable; we name our network FisherNet that is learnable using backpropagation. Our proposed FisherNet combines convolutional neural network training and Fisher Vector encoding in a single end-to-end structure. We observe a clear advantage of FisherNet over plain CNN and standard FV in terms of both classification accuracy and computational efficiency on the challenging PASCAL VOC object classification task.

##### Abstract (translated by Google)
尽管卷积神经网络（CNN）在Cifar和ImageNet等数据集上的图像分类任务取得了巨大的成功，但CNN的表示能力在处理尺寸和杂波变化较大的目标图像方面仍然有限，Fisher矢量（FV）已被证明是一种有效的编码策略。 FV通过将局部描述符与通用生成高斯混合模型（GMM）聚合来对图像进行编码。然而，FV具有有限的学习能力，并且其构造码本后其参数大多是固定的。为了把两个世界中最好的结合起来，我们在本文中提出了一个FV层作为端到端可训练系统的一部分的神经网络结构，我们将我们的网络命名为使用反向传播学习的FisherNet。我们提出的FisherNet将卷积神经网络训练和Fisher矢量编码结合在一个单一的端到端结构中。我们观察到FisherNet在纯CNN和标准FV方面的明显优势，就分类准确性和计算效率而言，在具有挑战性的PASCAL VOC对象分类任务方面具有优势。

##### URL
[https://arxiv.org/abs/1608.00182](https://arxiv.org/abs/1608.00182)

##### PDF
[https://arxiv.org/pdf/1608.00182](https://arxiv.org/pdf/1608.00182)

