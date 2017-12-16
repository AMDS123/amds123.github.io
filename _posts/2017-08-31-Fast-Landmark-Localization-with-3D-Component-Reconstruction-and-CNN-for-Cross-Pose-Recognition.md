---
layout: post
title: "Fast Landmark Localization with 3D Component Reconstruction and CNN for Cross-Pose Recognition"
date: 2017-08-31 06:26:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Detection Face_Detection Recognition Face_Recognition
author: Gee-Sern (Jison)Hsu, Hung-Cheng Shie, Cheng-Hua Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Two approaches are proposed for cross-pose face recognition, one is based on the 3D reconstruction of facial components and the other is based on the deep Convolutional Neural Network (CNN). Unlike most 3D approaches that consider holistic faces, the proposed approach considers 3D facial components. It segments a 2D gallery face into components, reconstructs the 3D surface for each component, and recognizes a probe face by component features. The segmentation is based on the landmarks located by a hierarchical algorithm that combines the Faster R-CNN for face detection and the Reduced Tree Structured Model for landmark localization. The core part of the CNN-based approach is a revised VGG network. We study the performances with different settings on the training set, including the synthesized data from 3D reconstruction, the real-life data from an in-the-wild database, and both types of data combined. We investigate the performances of the network when it is employed as a classifier or designed as a feature extractor. The two recognition approaches and the fast landmark localization are evaluated in extensive experiments, and compared to stateof-the-art methods to demonstrate their efficacy.

##### Abstract (translated by Google)
提出了两种用于交叉姿态人脸识别的方法，一种是基于面部分量的三维重建，另一种是基于深度卷积神经网络（CNN）。与大多数考虑整体面部的3D方法不同，所提出的方法考虑3D面部分量。它将2D图库的脸部分割成组件，重构每个组件的3D表面，并通过组件特征识别探测面。该分割基于通过结合用于面部检测的更快的R-CNN和用于地标定位的缩减树结构化模型的分层算法定位的地标。基于CNN的方法的核心部分是修订的VGG网络。我们在训练集上研究不同设置的性能，包括三维重建的合成数据，野外数据库中的实际数据以及两种数据的组合。当它被用作分类器或被设计为特征提取器时，我们调查网络的性能。这两种识别方法和快速地标本地化在广泛的实验中进行评估，并与最先进的方法进行比较，以证明其功效。

##### URL
[https://arxiv.org/abs/1708.09580](https://arxiv.org/abs/1708.09580)

##### PDF
[https://arxiv.org/pdf/1708.09580](https://arxiv.org/pdf/1708.09580)

