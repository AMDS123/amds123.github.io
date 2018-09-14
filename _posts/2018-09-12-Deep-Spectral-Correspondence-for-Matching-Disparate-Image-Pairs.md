---
layout: post
title: "Deep Spectral Correspondence for Matching Disparate Image Pairs"
date: 2018-09-12 19:33:26
categories: arXiv_CV
tags: arXiv_CV Salient
author: Arun CS Kumar, Shefali Srivastava, Anirban Mukhopadhyay, Suchendra M. Bhandarkar
mathjax: true
---

* content
{:toc}

##### Abstract
A novel, non-learning-based, saliency-aware, shape-cognizant correspondence determination technique is proposed for matching image pairs that are significantly disparate in nature. Images in the real world often exhibit high degrees of variation in scale, orientation, viewpoint, illumination and affine projection parameters, and are often accompanied by the presence of textureless regions and complete or partial occlusion of scene objects. The above conditions confound most correspondence determination techniques by rendering impractical the use of global contour-based descriptors or local pixel-level features for establishing correspondence. The proposed deep spectral correspondence (DSC) determination scheme harnesses the representational power of local feature descriptors to derive a complex high-level global shape representation for matching disparate images. The proposed scheme reasons about correspondence between disparate images using high-level global shape cues derived from low-level local feature descriptors. Consequently, the proposed scheme enjoys the best of both worlds, i.e., a high degree of invariance to affine parameters such as scale, orientation, viewpoint, illumination afforded by the global shape cues and robustness to occlusion provided by the low-level feature descriptors. While the shape-based component within the proposed scheme infers what to look for, an additional saliency-based component dictates where to look at thereby tackling the noisy correspondences arising from the presence of textureless regions and complex backgrounds. In the proposed scheme, a joint image graph is constructed using distances computed between interest points in the appearance (i.e., image) space. Eigenspectral decomposition of the joint image graph allows for reasoning about shape similarity to be performed jointly, in the appearance space and eigenspace.

##### Abstract (translated by Google)
提出了一种新颖的，基于非学习的，显着性感知的形状识别对应确定技术，用于匹配本质上明显不同的图像对。现实世界中的图像经常表现出尺度，方向，视点，照明和仿射投影参数的高度变化，并且通常伴随着无纹理区域的存在以及场景对象的完全或部分遮挡。上述条件通过使用基于全局轮廓的描述符或局部像素级特征来建立对应关系而变得不切实际，从而使大多数对应确定技术混淆。所提出的深谱对应（DSC）确定方案利用局部特征描述符的表示能力来导出用于匹配不同图像的复杂高级全局形状表示。所提出的方案使用从低级局部特征描述符导出的高级全局形状提示来推断不同图像之间的对应关系。因此，所提出的方案享有两个世界中的最佳方案，即，仿射参数的高度不变性，例如由全局形状线索提供的比例，取向，视点，照明以及由低级特征描述符提供的对遮挡的鲁棒性。虽然所提出的方案中基于形状的组件推断出要寻找的内容，但是附加的基于显着性的组件决定了在哪里查看，从而解决了由无纹理区域和复杂背景的存在引起的噪声对应。在所提出的方案中，使用在外观（即图像）空间中的兴趣点之间计算的距离来构建联合图像图。联合图像图的特征谱分解允许在外观空间和本征空间中联合执行关于形状相似性的推理。

##### URL
[http://arxiv.org/abs/1809.04642](http://arxiv.org/abs/1809.04642)

##### PDF
[http://arxiv.org/pdf/1809.04642](http://arxiv.org/pdf/1809.04642)

