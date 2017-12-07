---
layout: post
title: "Learning to decompose for object detection and instance segmentation"
date: 2016-05-11 02:55:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Eunbyung Park, Alexander C. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep convolutional neural networks(CNNs) have achieved remarkable results on object detection and segmentation, pre- and post-processing steps such as region proposals and non-maximum suppression(NMS), have been required. These steps result in high computational complexity and sensitivity to hyperparameters, e.g. thresholds for NMS. In this work, we propose a novel end-to-end trainable deep neural network architecture, which consists of convolutional and recurrent layers, that generates the correct number of object instances and their bounding boxes (or segmentation masks) given an image, using only a single network evaluation without any pre- or post-processing steps. We have tested on detecting digits in multi-digit images synthesized using MNIST, automatically segmenting digits in these images, and detecting cars in the KITTI benchmark dataset. The proposed approach outperforms a strong CNN baseline on the synthesized digits datasets and shows promising results on KITTI car detection.

##### Abstract (translated by Google)
虽然深度卷积神经网络（CNNs）在物体检测和分割方面取得了显着的成果，但是还需要预处理和后处理步骤，如区域提议和非最大抑制（NMS）。这些步骤导致对超参数的计算复杂性和灵敏度高，例如， NMS门槛。在这项工作中，我们提出了一个新的端到端的可训练的深度神经网络体系结构，它由卷积层和递归层组成，在给定图像的情况下生成正确数量的对象实例及其边界框（或分割掩模）单一网络评估，无需任何预处理或后处理步骤。我们已经测试了使用MNIST合成的多位图像中的数字，自动分割这些图像中的数字，并在KITTI基准数据集中检测汽车。所提出的方法在综合数字数据集上优于CNN的强基线，并且在KITTI车检测上显示出有希望的结果。

##### URL
[https://arxiv.org/abs/1511.06449](https://arxiv.org/abs/1511.06449)

##### PDF
[https://arxiv.org/pdf/1511.06449](https://arxiv.org/pdf/1511.06449)

