---
layout: post
title: "Faster Than Real-time Facial Alignment: A 3D Spatial Transformer Network Approach in Unconstrained Poses"
date: 2017-09-08 16:58:53
categories: arXiv_CV
tags: arXiv_CV Face
author: Chandrasekhar Bhagavatula, Chenchen Zhu, Khoa Luu, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
Facial alignment involves finding a set of landmark points on an image with a known semantic meaning. However, this semantic meaning of landmark points is often lost in 2D approaches where landmarks are either moved to visible boundaries or ignored as the pose of the face changes. In order to extract consistent alignment points across large poses, the 3D structure of the face must be considered in the alignment step. However, extracting a 3D structure from a single 2D image usually requires alignment in the first place. We present our novel approach to simultaneously extract the 3D shape of the face and the semantically consistent 2D alignment through a 3D Spatial Transformer Network (3DSTN) to model both the camera projection matrix and the warping parameters of a 3D model. By utilizing a generic 3D model and a Thin Plate Spline (TPS) warping function, we are able to generate subject specific 3D shapes without the need for a large 3D shape basis. In addition, our proposed network can be trained in an end-to-end framework on entirely synthetic data from the 300W-LP dataset. Unlike other 3D methods, our approach only requires one pass through the network resulting in a faster than real-time alignment. Evaluations of our model on the Annotated Facial Landmarks in the Wild (AFLW) and AFLW2000-3D datasets show our method achieves state-of-the-art performance over other 3D approaches to alignment.

##### Abstract (translated by Google)
面部对齐涉及在具有已知语义含义的图像上找到一组标志点。然而，标志点的这种语义意义常常在二维方法中丢失，其中地标被移动到可见边界或者当面部姿态改变时被忽略。为了在大姿势中提取一致的对准点，必须在对准步骤中考​​虑面部的3D结构。但是，从单个2D图像中提取3D结构通常首先需要对齐。我们提出了我们的新方法，通过三维空间变换网络（3DSTN）同时提取面部的三维形状和语义一致的2D对齐，以模拟相机投影矩阵和三维模型的翘曲参数。通过使用通用的3D模型和薄板样条（TPS）翘曲功能，我们可以生成主题特定的3D形状，而不需要大的3D形状基础。另外，我们提出的网络可以在300W-LP数据集的完全合成数据的端到端框架中进行培训。与其他3D方法不同的是，我们的方法只需要一次通过网络就可以实现比实时更快的对齐。我们在野外注解面部标志（AFLW）和AFLW2000-3D数据集上的模型评估显示，我们的方法实现了与其他3D对齐方法相比最先进的性能。

##### URL
[https://arxiv.org/abs/1707.05653](https://arxiv.org/abs/1707.05653)

##### PDF
[https://arxiv.org/pdf/1707.05653](https://arxiv.org/pdf/1707.05653)

