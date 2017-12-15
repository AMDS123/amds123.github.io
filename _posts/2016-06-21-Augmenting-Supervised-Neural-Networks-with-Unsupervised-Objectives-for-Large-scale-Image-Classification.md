---
layout: post
title: "Augmenting Supervised Neural Networks with Unsupervised Objectives for Large-scale Image Classification"
date: 2016-06-21 14:12:52
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Deep_Learning
author: Yuting Zhang, Kibok Lee, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised learning and supervised learning are key research topics in deep learning. However, as high-capacity supervised neural networks trained with a large amount of labels have achieved remarkable success in many computer vision tasks, the availability of large-scale labeled images reduced the significance of unsupervised learning. Inspired by the recent trend toward revisiting the importance of unsupervised learning, we investigate joint supervised and unsupervised learning in a large-scale setting by augmenting existing neural networks with decoding pathways for reconstruction. First, we demonstrate that the intermediate activations of pretrained large-scale classification networks preserve almost all the information of input images except a portion of local spatial details. Then, by end-to-end training of the entire augmented architecture with the reconstructive objective, we show improvement of the network performance for supervised tasks. We evaluate several variants of autoencoders, including the recently proposed "what-where" autoencoder that uses the encoder pooling switches, to study the importance of the architecture design. Taking the 16-layer VGGNet trained under the ImageNet ILSVRC 2012 protocol as a strong baseline for image classification, our methods improve the validation-set accuracy by a noticeable margin.

##### Abstract (translated by Google)
无监督学习和监督学习是深度学习的重要研究课题。然而，随着高容量监督神经网络的大量标签训练在许多计算机视觉任务中取得了显着的成功，大规模标记图像的可用性降低了无监督学习的意义。受近期重新审视无监督学习重要性的趋势的启发，我们通过对现有的神经网络进行解码路径的重建来调查大规模环境下的联合监督学习和无监督学习。首先，我们证明，预训练的大规模分类网络的中间激活保留了几乎所有的输入图像的信息，除了一部分局部空间细节。然后，通过对整个增强型体系结构进行端到端的重建目标训练，显示出对于监督任务的网络性能的改善。我们评估了几种自编码器的变体，包括最近提出的使用编码器池切换器的“what-where”autoencoder来研究体系结构设计的重要性。采用ImageNet ILSVRC 2012协议下的16层VGGNet作为图像分类的强大基准，我们的方法提高了验证集的准确性，并显着提高了准确率。

##### URL
[https://arxiv.org/abs/1606.06582](https://arxiv.org/abs/1606.06582)

##### PDF
[https://arxiv.org/pdf/1606.06582](https://arxiv.org/pdf/1606.06582)

