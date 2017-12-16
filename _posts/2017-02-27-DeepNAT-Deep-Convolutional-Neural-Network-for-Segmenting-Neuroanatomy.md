---
layout: post
title: "DeepNAT: Deep Convolutional Neural Network for Segmenting Neuroanatomy"
date: 2017-02-27 08:53:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Gradient_Descent
author: Christian Wachinger, Martin Reuter, Tassilo Klein
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce DeepNAT, a 3D Deep convolutional neural network for the automatic segmentation of NeuroAnaTomy in T1-weighted magnetic resonance images. DeepNAT is an end-to-end learning-based approach to brain segmentation that jointly learns an abstract feature representation and a multi-class classification. We propose a 3D patch-based approach, where we do not only predict the center voxel of the patch but also neighbors, which is formulated as multi-task learning. To address a class imbalance problem, we arrange two networks hierarchically, where the first one separates foreground from background, and the second one identifies 25 brain structures on the foreground. Since patches lack spatial context, we augment them with coordinates. To this end, we introduce a novel intrinsic parameterization of the brain volume, formed by eigenfunctions of the Laplace-Beltrami operator. As network architecture, we use three convolutional layers with pooling, batch normalization, and non-linearities, followed by fully connected layers with dropout. The final segmentation is inferred from the probabilistic output of the network with a 3D fully connected conditional random field, which ensures label agreement between close voxels. The roughly 2.7 million parameters in the network are learned with stochastic gradient descent. Our results show that DeepNAT compares favorably to state-of-the-art methods. Finally, the purely learning-based method may have a high potential for the adaptation to young, old, or diseased brains by fine-tuning the pre-trained network with a small training sample on the target application, where the availability of larger datasets with manual annotations may boost the overall segmentation accuracy in the future.

##### Abstract (translated by Google)
我们介绍DeepNAT，一种三维深度卷积神经网络，用于T1加权磁共振图像中神经解剖的自动分割。 DeepNAT是一种基于端到端的基于学习的脑分割方法，可共同学习抽象特征表示和多类分类。我们提出了一个基于三维补丁的方法，在这个方法中，我们不仅可以预测补丁的中心体素，而且还可以预测邻居，这被称为多任务学习。为了解决阶级失衡的问题，我们安排两个网络分层次，第一个分离前景和背景，第二个分析前景25个脑结构。由于补丁缺乏空间上下文，我们用坐标来补充它们。为此，我们引入了由Laplace-Beltrami算子的本征函数形成的一个新的脑体积的内在参数化。作为网络体系结构，我们使用三个卷积层，批量归一化和非线性，其次是完全连接的层和丢失。最终的分割是从网络的概率输出推断出一个三维完全连接的条件随机场，它确保了体素之间的标签一致性。通过随机梯度下降学习网络中大约270万个参数。我们的结果显示，DeepNAT与最先进的方法相比毫不逊色。最后，纯粹的基于学习的方法通过在目标应用程序上使用一个小的训练样本对预先训练好的网络进行微调，对于适应年轻的，老的或患病的大脑可能具有很高的潜力，手动注释可能会提高未来整体分割的准确性。

##### URL
[https://arxiv.org/abs/1702.08192](https://arxiv.org/abs/1702.08192)

##### PDF
[https://arxiv.org/pdf/1702.08192](https://arxiv.org/pdf/1702.08192)

