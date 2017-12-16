---
layout: post
title: "Efficient Yet Deep Convolutional Neural Networks for Semantic Segmentation"
date: 2017-07-26 00:15:35
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Sharif Amit Kamran, Ali Shihab Sabbir
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic Segmentation using deep convolutional neural network pose more complex challenge for any GPU intensive work, as it has to compute million of parameters resulting to huge consumption of memory. Moreover, extracting finer features and conducting supervised training tends to increase the complexity furthermore. With the introduction of Fully Convolutional Neural Network, which uses finer strides and utilizes deconvolutional layers for upsampling, it has been a go to for any image segmentation task. We propose two segmentation architecture transferring weights from the popular classification neural net VGG19 and VGG16 which were trained on Imagenet classification dataset, transform all the fully connected layers to convolutional layers, use dilated convolution for decreasing the parameters, moreover we add more finer strides and attach four skip architectures which are concatenated with the deconvolutional layers in steps. We train on two stages, first with PASCAL VOC2012 training data and then with SBD training and validation set. With our model, FCN-2s-Dilated-VGG19 we yield better score for PASCAL VOC2012 test set with a meanIOU of 69 percent which is 1.8 percent better than FCN-8s. And with FCN-2s-Dilated-VGG16 we score a meanIOU of 67.6 percent. On the other hand our model consumes up to 10-20 percent less memory than FCN-8s for training with NVIDIA Pascal GPUs, making it more efficient and less memory consuming architecture for pixel-wise segmentation.

##### Abstract (translated by Google)
使用深度卷积神经网络的语义分割对于任何GPU密集型工作都提出了更复杂的挑战，因为它必须计算数以百万计的参数，导致巨大的内存消耗。而且，提取更精细的特征并进行监督训练往往会进一步增加复杂性。随着全卷积神经网络的出现，其使用更精细的步幅，并利用去卷积层进行上采样，已经成为任何图像分割任务的一部分。我们提出了两个分割结构，从流行的分类神经网络VGG19和VGG16中传递权重，在Imagenet分类数据集上进行训练，将所有完全连通的层转化为卷积层，使用扩张卷积减小参数，并且添加更多更精细的步幅四个跳过架构，它们与解卷积层级联在一起。我们分两个阶段进行培训，首先是PASCAL VOC2012培训数据，然后是SBD培训和验证集。在我们的FCN-2s-Dilated-VGG19模型中，PASCAL VOC2012测试组的得分更高，平均69％，比FCN-8好1.8％。 FCN-2s-Dilated-VGG16得分为67.6％。另一方面，与使用NVIDIA Pascal GPU进行培训的FCN-8相比，我们的模型消耗的内存减少了10-20％，从而使其在像素级分割方面更加高效，占用内存更少。

##### URL
[https://arxiv.org/abs/1707.08254](https://arxiv.org/abs/1707.08254)

##### PDF
[https://arxiv.org/pdf/1707.08254](https://arxiv.org/pdf/1707.08254)

