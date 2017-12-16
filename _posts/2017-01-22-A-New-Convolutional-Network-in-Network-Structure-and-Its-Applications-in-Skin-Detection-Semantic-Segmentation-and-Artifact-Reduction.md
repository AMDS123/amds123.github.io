---
layout: post
title: "A New Convolutional Network-in-Network Structure and Its Applications in Skin Detection, Semantic Segmentation, and Artifact Reduction"
date: 2017-01-22 17:16:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification Deep_Learning Prediction Detection
author: Yoonsik Kim, Insung Hwang, Nam Ik Cho
mathjax: true
---

* content
{:toc}

##### Abstract
The inception network has been shown to provide good performance on image classification problems, but there are not much evidences that it is also effective for the image restoration or pixel-wise labeling problems. For image restoration problems, the pooling is generally not used because the decimated features are not helpful for the reconstruction of an image as the output. Moreover, most deep learning architectures for the restoration problems do not use dense prediction that need lots of training parameters. From these observations, for enjoying the performance of inception-like structure on the image based problems we propose a new convolutional network-in-network structure. The proposed network can be considered a modification of inception structure where pool projection and pooling layer are removed for maintaining the entire feature map size, and a larger kernel filter is added instead. Proposed network greatly reduces the number of parameters on account of removed dense prediction and pooling, which is an advantage, but may also reduce the receptive field in each layer. Hence, we add a larger kernel than the original inception structure for not increasing the depth of layers. The proposed structure is applied to typical image-to-image learning problems, i.e., the problems where the size of input and output are same such as skin detection, semantic segmentation, and compression artifacts reduction. Extensive experiments show that the proposed network brings comparable or better results than the state-of-the-art convolutional neural networks for these problems.

##### Abstract (translated by Google)
初始网络已被证明在图像分类问题上提供了良好的性能，但没有太多的证据表明，它也是有效的图像恢复或像素标签问题。对于图像恢复问题，通常不使用池化，因为抽取的特征对于将图像重建为输出没有帮助。而且，对于复原问题，大多数深度学习架构不使用需要大量训练参数的密集预测。从这些观察中，为了在基于图像的问题上享受起始样结构的性能，我们提出了一种新的卷积网络网络结构。所提出的网络可以被认为是初始结构的修改，其中为了维持整个特征映射的大小而去除了池投影和汇聚层，并且增加了更大的内核过滤器。提出的网络由于去除了密集预测和共享而大大减少了参数的数量，这是一个优点，但是也可能减少每层中的接受域。因此，为了不增加层的深度，我们添加比原始结构更大的内核。所提出的结构适用于典型的图像学习问题，即输入和输出大小相同的问题，如皮肤检测，语义分割和压缩伪影减少。大量的实验表明，与现有技术的卷积神经网络相比，所提出的网络具有可比的或更好的结果。

##### URL
[https://arxiv.org/abs/1701.06190](https://arxiv.org/abs/1701.06190)

##### PDF
[https://arxiv.org/pdf/1701.06190](https://arxiv.org/pdf/1701.06190)

