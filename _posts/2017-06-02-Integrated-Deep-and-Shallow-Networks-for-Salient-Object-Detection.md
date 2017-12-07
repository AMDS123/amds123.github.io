---
layout: post
title: "Integrated Deep and Shallow Networks for Salient Object Detection"
date: 2017-06-02 00:52:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Jing Zhang, Bo Li, Yuchao Dai, Fatih Porikli, Mingyi He
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network (CNN) based salient object detection methods have achieved state-of-the-art performance and outperform those unsupervised methods with a wide margin. In this paper, we propose to integrate deep and unsupervised saliency for salient object detection under a unified framework. Specifically, our method takes results of unsupervised saliency (Robust Background Detection, RBD) and normalized color images as inputs, and directly learns an end-to-end mapping between inputs and the corresponding saliency maps. The color images are fed into a Fully Convolutional Neural Networks (FCNN) adapted from semantic segmentation to exploit high-level semantic cues for salient object detection. Then the results from deep FCNN and RBD are concatenated to feed into a shallow network to map the concatenated feature maps to saliency maps. Finally, to obtain a spatially consistent saliency map with sharp object boundaries, we fuse superpixel level saliency map at multi-scale. Extensive experimental results on 8 benchmark datasets demonstrate that the proposed method outperforms the state-of-the-art approaches with a margin.

##### Abstract (translated by Google)
基于深度卷积神经网络（CNN）的突出目标检测方法已经取得了最新的性能，并且在很大程度上优于那些无监督的方法。在本文中，我们建议在一个统一的框架下，将显着物体检测的深度和无监督显着性结合起来。具体来说，我们的方法采用无监督显着性（鲁棒背景检测，RBD）和归一化彩色图像作为输入的结果，并直接学习输入和相应的显着图之间的端到端映射。彩色图像被馈送到从语义分割改造的全卷积神经网络（FCNN）中，以利用用于显着对象检测的高级语义提示。然后将来自深FCNN和RBD的结果串联起来，馈入浅层网络，将连接的特征映射映射到显着图。最后，为了获得具有尖锐物体边界的空间一致的显着图，我们在多尺度上融合了超像素级显着图。在8个基准数据集上的广泛的实验结果表明，所提出的方法优于具有余量的最先进的方法。

##### URL
[https://arxiv.org/abs/1706.00530](https://arxiv.org/abs/1706.00530)

##### PDF
[https://arxiv.org/pdf/1706.00530](https://arxiv.org/pdf/1706.00530)

