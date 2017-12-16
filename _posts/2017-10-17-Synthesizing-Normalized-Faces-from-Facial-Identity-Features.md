---
layout: post
title: "Synthesizing Normalized Faces from Facial Identity Features"
date: 2017-10-17 15:27:21
categories: arXiv_CV
tags: arXiv_CV Sparse Face Recognition
author: Forrester Cole, David Belanger, Dilip Krishnan, Aaron Sarna, Inbar Mosseri, William T. Freeman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for synthesizing a frontal, neutral-expression image of a person's face given an input face photograph. This is achieved by learning to generate facial landmarks and textures from features extracted from a facial-recognition network. Unlike previous approaches, our encoding feature vector is largely invariant to lighting, pose, and facial expression. Exploiting this invariance, we train our decoder network using only frontal, neutral-expression photographs. Since these photographs are well aligned, we can decompose them into a sparse set of landmark points and aligned texture maps. The decoder then predicts landmarks and textures independently and combines them using a differentiable image warping operation. The resulting images can be used for a number of applications, such as analyzing facial attributes, exposure and white balance adjustment, or creating a 3-D avatar.

##### Abstract (translated by Google)
我们提出了一种合成输入人脸照片的人脸的正面中性表情图像的方法。这是通过学习从面部识别网络中提取的特征生成面部标志和纹理来实现的。与以前的方法不同，我们的编码特征向量在很大程度上不受光照，姿态和面部表情的影响。利用这种不变性，我们仅使用正面的中性表达照片来训练我们的解码器网络。由于这些照片是完全对齐的，我们可以将它们分解成一组稀疏的界标点和对齐的纹理贴图。解码器然后独立预测地标和纹理，并使用可微分图像变形操作将它们组合。生成的图像可用于多种应用，如分析面部属性，曝光和白平衡调整，或创建3D头像。

##### URL
[https://arxiv.org/abs/1701.04851](https://arxiv.org/abs/1701.04851)

##### PDF
[https://arxiv.org/pdf/1701.04851](https://arxiv.org/pdf/1701.04851)

