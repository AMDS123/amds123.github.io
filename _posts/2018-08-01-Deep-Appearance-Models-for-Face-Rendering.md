---
layout: post
title: "Deep Appearance Models for Face Rendering"
date: 2018-08-01 15:13:48
categories: arXiv_CV
tags: arXiv_CV Face Inference
author: Stephen Lombardi, Jason Saragih, Tomas Simon, Yaser Sheikh
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a deep appearance model for rendering the human face. Inspired by Active Appearance Models, we develop a data-driven rendering pipeline that learns a joint representation of facial geometry and appearance from a multiview capture setup. Vertex positions and view-specific textures are modeled using a deep variational autoencoder that captures complex nonlinear effects while producing a smooth and compact latent representation. View-specific texture enables the modeling of view-dependent effects such as specularity. In addition, it can also correct for imperfect geometry stemming from biased or low resolution estimates. This is a significant departure from the traditional graphics pipeline, which requires highly accurate geometry as well as all elements of the shading model to achieve realism through physically-inspired light transport. Acquiring such a high level of accuracy is difficult in practice, especially for complex and intricate parts of the face, such as eyelashes and the oral cavity. These are handled naturally by our approach, which does not rely on precise estimates of geometry. Instead, the shading model accommodates deficiencies in geometry though the flexibility afforded by the neural network employed. At inference time, we condition the decoding network on the viewpoint of the camera in order to generate the appropriate texture for rendering. The resulting system can be implemented simply using existing rendering engines through dynamic textures with flat lighting. This representation, together with a novel unsupervised technique for mapping images to facial states, results in a system that is naturally suited to real-time interactive settings such as Virtual Reality (VR).

##### Abstract (translated by Google)
我们介绍了一种用于渲染人脸的深度模型。受Active Appearance Models的启发，我们开发了一个数据驱动的渲染管道，可以从多视图捕获设置中学习面部几何和外观的联合表示。顶点位置和视图特定纹理使用深变分自动编码器建模，该自动编码器捕获复杂的非线性效应，同时产生平滑和紧凑的潜在表示。视图特定纹理可以对视图相关效果（如镜面反射）进行建模。此外，它还可以校正源于偏差或低分辨率估计的不完美几何。这与传统的图形管道有很大不同，后者需要高度精确的几何图形以及阴影模型的所有元素，以通过物理启发的光传输实现真实感。在实践中获得如此高的准确度是困难的，特别是对于面部的复杂和复杂部分，例如睫毛和口腔。这些由我们的方法自然处理，不依赖于几何的精确估计。相反，阴影模型适应几何形状的缺陷，尽管所采用的神经网络提供了灵活性。在推理时，我们在相机的视点上调节解码网络，以便生成用于渲染的适当纹理。生成的系统可以通过具有平面照明的动态纹理简单地使用现有的渲染引擎来实现。该表示与用于将图像映射到面部状态的新颖无监督技术一起导致系统自然地适合于诸如虚拟现实（VR）的实时交互设置。

##### URL
[https://arxiv.org/abs/1808.00362](https://arxiv.org/abs/1808.00362)

##### PDF
[https://arxiv.org/pdf/1808.00362](https://arxiv.org/pdf/1808.00362)

