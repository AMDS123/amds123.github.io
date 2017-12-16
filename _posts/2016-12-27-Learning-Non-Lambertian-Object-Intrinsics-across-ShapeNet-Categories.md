---
layout: post
title: "Learning Non-Lambertian Object Intrinsics across ShapeNet Categories"
date: 2016-12-27 06:38:43
categories: arXiv_CV
tags: arXiv_CV Classification
author: Jian Shi, Yue Dong, Hao Su, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the non-Lambertian object intrinsic problem of recovering diffuse albedo, shading, and specular highlights from a single image of an object. We build a large-scale object intrinsics database based on existing 3D models in the ShapeNet database. Rendered with realistic environment maps, millions of synthetic images of objects and their corresponding albedo, shading, and specular ground-truth images are used to train an encoder-decoder CNN. Once trained, the network can decompose an image into the product of albedo and shading components, along with an additive specular component. Our CNN delivers accurate and sharp results in this classical inverse problem of computer vision, sharp details attributed to skip layer connections at corresponding resolutions from the encoder to the decoder. Benchmarked on our ShapeNet and MIT intrinsics datasets, our model consistently outperforms the state-of-the-art by a large margin. We train and test our CNN on different object categories. Perhaps surprising especially from the CNN classification perspective, our intrinsics CNN generalizes very well across categories. Our analysis shows that feature learning at the encoder stage is more crucial for developing a universal representation across categories. We apply our synthetic data trained model to images and videos downloaded from the internet, and observe robust and realistic intrinsics results. Quality non-Lambertian intrinsics could open up many interesting applications such as image-based albedo and specular editing.

##### Abstract (translated by Google)
我们考虑从物体的单个图像恢复漫反射，阴影和镜面高光的非朗伯物体内在问题。我们在ShapeNet数据库中基于现有的三维模型构建了一个大型的对象内在数据库。用逼真的环境地图渲染，数以百万计的对象合成图像及其相应的反照率，阴影和镜面地面实况图像被用来训练编码器 - 解码器CNN。一旦训练好了，网络就可以将图像分解成反照率和阴影成分的产物以及可加镜面反射成分。我们的CNN在这个经典的计算机视觉反演问题中提供了准确和清晰的结果，在编码器和解码器的相应分辨率下，跳跃层连接引起的锐利细节。基于我们的ShapeNet和MIT内在数据集，我们的模型始终优于最先进的技术。我们在不同的对象类别上训练和测试我们的CNN。也许令人惊讶的是，尤其是从CNN分类的角度来看，我们的内在CNN在各个类别之间进行了很好的概括。我们的分析表明，编码器阶段的特征学习对于跨类别开发通用表示更为重要。我们将我们的合成数据训练模型应用于从互联网上下载的图像和视频，并观察强大而真实的内在结果。高质量的非朗伯内部函数可以打开许多有趣的应用程序，例如基于图像的反照率和镜面编辑。

##### URL
[https://arxiv.org/abs/1612.08510](https://arxiv.org/abs/1612.08510)

##### PDF
[https://arxiv.org/pdf/1612.08510](https://arxiv.org/pdf/1612.08510)

