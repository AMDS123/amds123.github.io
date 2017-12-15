---
layout: post
title: "A deep convolutional neural network approach to single-particle recognition in cryo-electron microscopy"
date: 2016-12-31 07:22:21
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Recognition
author: Yanan Zhu, Qi Ouyang, Youdong Mao
mathjax: true
---

* content
{:toc}

##### Abstract
Background: Single-particle cryo-electron microscopy (cryo-EM) has become a popular tool for structural determination of biological macromolecular complexes. High-resolution cryo-EM reconstruction often requires hundreds of thousands of single-particle images. Particle extraction from experimental micrographs thus can be laborious and presents a major practical bottleneck in cryo-EM structural determination. Existing computational methods of particle picking often use low-resolution templates as inputs for particle matching, making it possible to cause reference-dependent bias. It is critical to develop a highly efficient template-free method to automatically recognize particle images from cryo-EM micrographs. Results: We developed a deep learning-based algorithmic framework, DeepEM, for single-particle recognition from noisy cryo-EM micrographs, enabling automated particle picking, selection and verification in an integrated fashion. The kernel of DeepEM is built upon a convolutional neural network (CNN) of eight layers, which can be recursively trained to be highly "knowledgeable". Our approach exhibits improved performance and high precision when tested on the standard KLH dataset. Application of DeepEM to several challenging experimental cryo-EM datasets demonstrates its capability in avoiding selection of un-wanted particles and non-particles even when true particles contain fewer features. Conclusions: The DeepEM method derived from a deep CNN allows automated particle extraction from raw cryo-EM micrographs in the absence of templates, which demonstrated improved performance, objectivity and accuracy. Application of this novel approach is expected to free the labor involved in single-particle verification, thus promoting the efficiency of cryo-EM data processing.

##### Abstract (translated by Google)
背景：单粒子低温电子显微镜（cryo-EM）已成为生物大分子复合物结构测定的流行工具。高分辨率冷冻电镜重建通常需要数十万个单颗粒图像。因此从实验显微照片中提取颗粒可能是费力的，并且在冷冻电镜结构测定中呈现出主要的实际瓶颈。现有的粒子拾取计算方法通常使用低分辨率模板作为粒子匹配的输入，使得引起参考依赖的偏差成为可能。开发一种高效的无模板方法来自动识别来自冷冻电镜显微照片的颗粒图像是至关重要的。结果：我们开发了深度学习算法框架DeepEM，用于从噪声冷冻电镜显微照片进行单粒子识别，从而实现自动化的粒子拾取，选择和验证。 DeepEM的核心是建立在八层的卷积神经网络（CNN）之上，可以被递归地训练成高度“有知识”的。我们的方法在标准KLH数据集上进行测试时性能更高，精度更高。将DeepEM应用于几个具有挑战性的实验性冷冻电镜数据集，证明了即使当真实的颗粒包含较少的特征时，其也避免选择不需要的颗粒和非颗粒。结论：由深CNN得到的DeepEM方法允许在没有模板的情况下从原始冷冻电镜显微照片中自动提取颗粒，这证明了改进的性能，客观性和准确性。预计这种新方法的应用将释放单颗粒验证中的劳动，从而提高冷冻电镜数据处理的效率。

##### URL
[https://arxiv.org/abs/1605.05543](https://arxiv.org/abs/1605.05543)

##### PDF
[https://arxiv.org/pdf/1605.05543](https://arxiv.org/pdf/1605.05543)

