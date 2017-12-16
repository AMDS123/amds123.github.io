---
layout: post
title: "Understanding Deep Representations through Random Weights"
date: 2017-04-02 17:13:55
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yao Shu, Man Zhu, Kun He, John Hopcroft, Pan Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We systematically study the deep representation of random weight CNN (convolutional neural network) using the DeCNN (deconvolutional neural network) architecture. We first fix the weights of an untrained CNN, and for each layer of its feature representation, we train a corresponding DeCNN to reconstruct the input image. As compared with the pre-trained CNN, the DeCNN trained on a random weight CNN can reconstruct images more quickly and accurately, no matter which type of random distribution for the CNN's weights. It reveals that every layer of the random CNN can retain photographically accurate information about the image. We then let the DeCNN be untrained, i.e. the overall CNN-DeCNN architecture uses only random weights. Strikingly, we can reconstruct all position information of the image for low layer representations but the colors change. For high layer representations, we can still capture the rough contours of the image. We also change the number of feature maps and the shape of the feature maps and gain more insight on the random function of the CNN-DeCNN structure. Our work reveals that the purely random CNN-DeCNN architecture substantially contributes to the geometric and photometric invariance due to the intrinsic symmetry and invertible structure, but it discards the colormetric information due to the random projection.

##### Abstract (translated by Google)
我们系统地研究了使用DeCNN（反卷积神经网络）架构的随机加权CNN（卷积神经网络）的深度表示。我们首先确定一个未经训练的CNN的权重，并且对于它的每个特征表示层，我们训练一个相应的DeCNN来重建输入图像。与预先训练的CNN相比，使用随机加权CNN训练的DeCNN可以更快，更准确地重建图像，而不管CNN的权重是哪种类型的随机分布。它揭示了随机CNN的每一层都可以保留关于图像的照片上准确的信息。然后，我们让DeCNN未经训练，即整个CNN-DeCNN体系结构只使用随机权重。引人注目的是，我们可以重构低层表示的图像的所有位置信息，但颜色会改变。对于高层表示，我们仍然可以捕捉图像的粗糙轮廓。我们还改变了特征映射的数量和特征映射的形状，并对CNN-DeCNN结构的随机函数有了更深入的了解。我们的工作揭示了纯粹的随机CNN-DeCNN结构由于固有的对称性和可逆结构而大大地贡献了几何和光度不变性，但是由于随机投影丢弃了颜色信息。

##### URL
[https://arxiv.org/abs/1704.00330](https://arxiv.org/abs/1704.00330)

##### PDF
[https://arxiv.org/pdf/1704.00330](https://arxiv.org/pdf/1704.00330)

