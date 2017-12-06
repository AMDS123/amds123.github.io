---
layout: post
title: "Joint Embedding and Classification for SAR Target Recognition"
date: 2017-12-05 07:45:18
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Recognition
author: Jiayun Wang, Patrick Virtue, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning can be an effective and efficient means to automatically detect and classify targets in synthetic aperture radar (SAR) images, but it is critical for trained neural networks to be robust to variations that exist between training and test environments. The layers in a neural network can be understood to be successive transformations of an input image into embedded feature representations and ultimately into a semantic class label. To address the overfitting problem in SAR target classification, we train neural networks to optimize the spatial clustering of points in the embedded space in addition to optimizing the final classification score. We demonstrate that networks trained with this dual embedding and classification loss outperform networks with only a classification loss. We study placing the embedding loss after different network layers and and found that applying the embedding loss on the classification space results in the best the SAR classification performance. Finally, our visualization of the network's ten-dimensional classification space supports our claim that the embedding loss encourages a better embedding, namely greater separation between target class clusters for both training and testing partitions of the MSTAR dataset.

##### Abstract (translated by Google)
深度学习是自动检测和分类合成孔径雷达（SAR）图像中目标的有效手段，但对于训练好的神经网络对训练和测试环境之间存在的变化的鲁棒性至关重要。神经网络中的层可以被理解为输入图像到嵌入的特征表示的连续变换，并最终成为语义类别标签。为了解决SAR目标分类中的过拟合问题，除了优化最终的分类分数之外，还对训练好的神经网络进行训练，以优化嵌入空间中的点的空间聚类。我们证明，使用这种双重嵌入和分类损失训练的网络只有分类丢失才能胜过网络。我们研究了在不同网络层之后的嵌入损失，发现在分类空间上应用嵌入损耗导致了SAR分类性能的最好。最后，我们的网络十维分类空间的可视化支持我们的声明，即嵌入损失鼓励更好的嵌入，即在MSTAR数据集的训练和测试分区的目标类集群之间更大的分离。

##### URL
[http://arxiv.org/abs/1712.01511](http://arxiv.org/abs/1712.01511)

