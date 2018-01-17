---
layout: post
title: "Constraint-free Natural Image Reconstruction from fMRI Signals Based on Convolutional Neural Network"
date: 2018-01-16 08:34:18
categories: arXiv_AI
tags: arXiv_AI Sparse CNN Optimization
author: Chi Zhang, Kai Qiao, Linyuan Wang, Li Tong, Ying Zeng, Bin Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, research on decoding brain activity based on functional magnetic resonance imaging (fMRI) has made remarkable achievements. However, constraint-free natural image reconstruction from brain activity is still a challenge. The existing methods simplified the problem by using semantic prior information or just reconstructing simple images such as letters and digitals. Without semantic prior information, we present a novel method to reconstruct nature images from fMRI signals of human visual cortex based on the computation model of convolutional neural network (CNN). Firstly, we extracted the units output of viewed natural images in each layer of a pre-trained CNN as CNN features. Secondly, we transformed image reconstruction from fMRI signals into the problem of CNN feature visualizations by training a sparse linear regression to map from the fMRI patterns to CNN features. By iteratively optimization to find the matched image, whose CNN unit features become most similar to those predicted from the brain activity, we finally achieved the promising results for the challenging constraint-free natural image reconstruction. As there was no use of semantic prior information of the stimuli when training decoding model, any category of images (not constraint by the training set) could be reconstructed theoretically. We found that the reconstructed images resembled the natural stimuli, especially in position and shape. The experimental results suggest that hierarchical visual features can effectively express the visual perception process of human brain.

##### Abstract (translated by Google)
近年来，基于功能磁共振成像（fMRI）的脑功能解码研究取得了令人瞩目的成就。然而，从大脑活动中进行无约束自然图像重建仍然是一个挑战。现有的方法通过使用语义先验信息或者仅仅重建简单的图像（例如字母和数字）来简化问题。在没有语义先验信息的情况下，基于卷积神经网络（CNN）的计算模型，提出了一种基于人视觉皮层的fMRI信号重建自然图像的新方法。首先，将预先训练的CNN的每一层的观看自然图像的单位输出提取为CNN特征。其次，通过训练一个稀疏的线性回归从fMRI模式到CNN特征的映射，我们将图像重建从fMRI信号转换成CNN特征可视化的问题。通过迭代优化找到匹配的图像，其CNN单元特征变得与大脑活动预测的图像最为相似，我们最终取得了有希望的成果，为有挑战性的无约束自然图像重建。由于在训练解码模型时没有使用刺激的语义先验信息，因此理论上可以重建任何类别的图像（不受训练集的约束）。我们发现，重建的图像类似于自然的刺激，特别是在位置和形状。实验结果表明，分层视觉特征能够有效地表达人脑的视觉感知过程。

##### URL
[http://arxiv.org/abs/1801.05151](http://arxiv.org/abs/1801.05151)

##### PDF
[http://arxiv.org/pdf/1801.05151](http://arxiv.org/pdf/1801.05151)

