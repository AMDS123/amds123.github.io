---
layout: post
title: "Efficient Yet Deep Convolutional Neural Networks for Semantic Segmentation"
date: 2017-12-23 15:36:35
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Semantic_Segmentation Classification
author: Sharif Amit Kamran, Muhammad Hasan, Ali Shihab Sabbir
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic Segmentation using deep convolutional neural network pose more complex challenge for any GPU intensive work, as it has to compute million of parameters resulting to huge consumption of memory. Moreover, extracting finer features and conducting supervised training tends to increase the complexity furthermore. With the introduction of Fully Convolutional Neural Network, which uses finer strides and utilizes deconvolutional layers for upsampling, it has been a go to for any image segmentation task. We propose two segmentation architecture transferring weights from the popular classification neural net VGG19 and VGG16 which were trained on Imagenet classification dataset, transform all the fully connected layers to convolutional layers, use dilated convolution for decreasing the parameters, moreover we add more finer strides and attach four skip architectures which are element-wise summed with the deconvolutional layers in steps. We train and test on different sparse and fine data-sets like Pascal VOC2012, Pascal-Context and NYUDv2 and show how better our model performs in this tasks. On the other hand our model consumes up to 10-20 percent less memory for training and testing with NVIDIA Pascal GPUs, making it more efficient and less memory consuming architecture for pixel-wise segmentation.

##### Abstract (translated by Google)
使用深度卷积神经网络的语义分割对于任何GPU密集型工作都提出了更复杂的挑战，因为它必须计算数以百万计的参数，导致巨大的内存消耗。而且，提取更精细的特征并进行监督训练往往会进一步增加复杂性。随着全卷积神经网络的出现，其使用更精细的步幅，并利用去卷积层进行上采样，已经成为任何图像分割任务的一部分。我们提出了两个分割结构，从流行的分类神经网络VGG19和VGG16中传递权重，在Imagenet分类数据集上进行训练，将所有完全连通的层转化为卷积层，使用扩张卷积减小参数，并且添加更多更精细的步幅四个跳跃体系结构，这些体系结构与解卷积层按照元素逐步求和。我们对Pascal VOC2012，Pascal-Context和NYUDv2等不同的稀疏和精细的数据集进行训练和测试，并展示我们的模型在这个任务中的表现如何更好。另一方面，我们的模型在使用NVIDIA Pascal GPU进行培训和测试时消耗的内存减少了10-20％，从而使得像素级分割的内存消耗架构更加高效，占用更少。

##### URL
[http://arxiv.org/abs/1707.08254](http://arxiv.org/abs/1707.08254)

##### PDF
[http://arxiv.org/pdf/1707.08254](http://arxiv.org/pdf/1707.08254)

