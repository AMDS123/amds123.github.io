---
layout: post
title: 'Image to Image Translation for Domain Adaptation'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: [arXiv_CV]
author: Zak Murez, Soheil Kolouri, David Kriegman, Ravi Ramamoorthi, Kyungnam Kim
---

* content
{:toc}

##### Abstract
We propose a general framework for unsupervised domain adaptation, which allows deep neural networks trained on a source domain to be tested on a different target domain without requiring any training annotations in the target domain. This is achieved by adding extra networks and losses that help regularize the features extracted by the backbone encoder network. To this end we propose the novel use of the recently proposed unpaired image-toimage translation framework to constrain the features extracted by the encoder network. Specifically, we require that the features extracted are able to reconstruct the images in both domains. In addition we require that the distribution of features extracted from images in the two domains are indistinguishable. Many recent works can be seen as specific cases of our general framework. We apply our method for domain adaptation between MNIST, USPS, and SVHN datasets, and Amazon, Webcam and DSLR Office datasets in classification tasks, and also between GTA5 and Cityscapes datasets for a segmentation task. We demonstrate state of the art performance on each of these datasets.

##### Abstract (translated by Google)
我们提出了一个无监督领域适应的通用框架，允许在源域上训练的深度神经网络在不同的目标域上进行测试，而不需要目标域中的任何训练注释。这是通过增加额外的网络和损失来实现的，这些网络和损失有助于调整主干编码器网络提取的特征。为此，我们提出了最近提出的不成对的图像到图像转换框架的新颖用途，以约束编码器网络提取的特征。具体而言，我们要求提取的特征能够重建两个域中的图像。此外，我们要求从两个域中的图像中提取的特征的分布是不可区分的。最近的许多作品可以看作是我们总体框架的具体案例。我们将我们的方法应用于MNIST，USPS和SVHN数据集之间的域适配，以及分类任务中的Amazon，Webcam和DSLR Office数据集以及GTA5和Cityscapes数据集之间的分割任务。我们在每个这些数据集上展示最先进的性能。

##### URL
[http://arxiv.org/abs/1712.00479](http://arxiv.org/abs/1712.00479)

