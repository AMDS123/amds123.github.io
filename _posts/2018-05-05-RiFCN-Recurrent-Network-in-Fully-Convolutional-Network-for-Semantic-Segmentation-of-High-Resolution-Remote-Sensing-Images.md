---
layout: post
title: "RiFCN: Recurrent Network in Fully Convolutional Network for Semantic Segmentation of High Resolution Remote Sensing Images"
date: 2018-05-05 18:00:43
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Classification
author: Lichao Mou, Xiao Xiang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation in high resolution remote sensing images is a fundamental and challenging task. Convolutional neural networks (CNNs), such as fully convolutional network (FCN) and SegNet, have shown outstanding performance in many segmentation tasks. One key pillar of these successes is mining useful information from features in convolutional layers for producing high resolution segmentation maps. For example, FCN nonlinearly combines high-level features extracted from last convolutional layers; whereas SegNet utilizes a deconvolutional network which takes as input only coarse, high-level feature maps of the last convolutional layer. However, how to better fuse multi-level convolutional feature maps for semantic segmentation of remote sensing images is underexplored. In this work, we propose a novel bidirectional network called recurrent network in fully convolutional network (RiFCN), which is end-to-end trainable. It has a forward stream and a backward stream. The former is a classification CNN architecture for feature extraction, which takes an input image and produces multi-level convolutional feature maps from shallow to deep; while in the later, to achieve accurate boundary inference and semantic segmentation, boundary-aware high resolution feature maps in shallower layers and high-level but low-resolution features are recursively embedded into the learning framework (from deep to shallow) to generate a fused feature representation that draws a holistic picture of not only high-level semantic information but also low-level fine-grained details. Experimental results on two widely-used high resolution remote sensing data sets for semantic segmentation tasks, ISPRS Potsdam and Inria Aerial Image Labeling Data Set, demonstrate competitive performance obtained by the proposed methodology compared to other studied approaches.

##### Abstract (translated by Google)
高分辨率遥感图像中的语义分割是一项基础性和具有挑战性的任务。卷积神经网络（CNN），如完全卷积网络（FCN）和SegNet，在许多分割任务中表现出色。这些成功的关键支柱之一就是从卷积图层中的特征中挖掘出有用的信息来生成高分辨率的分割图。例如，FCN非线性地结合从最后的卷积层提取的高级特征;而SegNet利用一个去卷积网络，该网络只输入最后一个卷积层的粗糙，高级特征图。但是，如何更好地融合多级卷积特征地图用于遥感图像的语义分割尚处于探索阶段。在这项工作中，我们提出了一个新的双向网络，称为全卷积网络（RiFCN）中的循环网络，它是端到端可训练的。它有一个前向流和一个后向流。前者是一种用于特征提取的分类CNN体系结构，它采用输入图像并生成从浅到深的多级卷积特征图;而后来，为了实现准确的边界推理和语义分割，在浅层中的边界感知高分辨率特征映射和高水平但低分辨率的特征被递归地嵌入到学习框架中（从深到浅）以产生融合特征表示，不仅可以绘制高级语义信息的整体画面，还可以绘制低级细粒度细节。针对语义分割任务的两种广泛使用的高分辨率遥感数据集ISPRS Potsdam和Inria航空图像标记数据集的实验结果证明了与其他研究方法相比，所提出方法获得的竞争性能。

##### URL
[http://arxiv.org/abs/1805.02091](http://arxiv.org/abs/1805.02091)

##### PDF
[http://arxiv.org/pdf/1805.02091](http://arxiv.org/pdf/1805.02091)

