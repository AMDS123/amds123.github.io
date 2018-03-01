---
layout: post
title: "IM2HEIGHT: Height Estimation from Single Monocular Imagery via Fully Residual Convolutional-Deconvolutional Network"
date: 2018-02-28 03:32:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction Quantitative
author: Lichao Mou, Xiao Xiang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we tackle a very novel problem, namely height estimation from a single monocular remote sensing image, which is inherently ambiguous, and a technically ill-posed problem, with a large source of uncertainty coming from the overall scale. We propose a fully convolutional-deconvolutional network architecture being trained end-to-end, encompassing residual learning, to model the ambiguous mapping between monocular remote sensing images and height maps. Specifically, it is composed of two parts, i.e., convolutional sub-network and deconvolutional sub-network. The former corresponds to feature extractor that transforms the input remote sensing image to high-level multidimensional feature representation, whereas the latter plays the role of a height generator that produces height map from the feature extracted from the convolutional sub-network. Moreover, to preserve fine edge details of estimated height maps, we introduce a skip connection to the network, which is able to shuttle low-level visual information, e.g., object boundaries and edges, directly across the network. To demonstrate the usefulness of single-view height prediction, we show a practical example of instance segmentation of buildings using estimated height map. This paper, for the first time in the remote sensing community, attempts to estimate height from monocular vision. The proposed network is validated using a large-scale high resolution aerial image data set covered an area of Berlin. Both visual and quantitative analysis of the experimental results demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)
在本文中，我们解决了一个非常新颖的问题，即单一的单眼遥感图像的高度估计，这本质上是模棱两可的，还有一个技术上不适当的问题，总体规模有很大的不确定性来源。我们提出了一个全面的卷积 - 反卷积网络架构，通过端对端训练，包含残差学习，模拟单眼遥感图像和高度图之间的模糊映射。具体来说，它由两部分组成，即卷积子网和解卷积子网。前者对应于特征提取器，将输入的遥感图像转换为高级多维特征表示，而后者则扮演高度发生器的角色，该高度发生器根据从卷积子网络提取的特征生成高度图。此外，为了保留估计的高度图的细节边缘细节，我们引入了到网络的跳跃连接，该网络能够直接穿过网络穿透低级视觉信息，例如对象边界和边缘。为了演示单视图高度预测的有用性，我们使用估计的高度图显示了建筑物实例分割的实例。本文首次在遥感领域尝试从单眼视觉估计身高。拟议的网络使用涵盖柏林地区的大规模高分辨率航空图像数据集进行验证。对实验结果的视觉和定量分析都证明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1802.10249](http://arxiv.org/abs/1802.10249)

##### PDF
[http://arxiv.org/pdf/1802.10249](http://arxiv.org/pdf/1802.10249)

