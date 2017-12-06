---
layout: post
title: 'Constrained Manifold Learning for Hyperspectral Imagery Visualization'
date: 2017-12-06 10:01:55
categories: arXiv_CV
tags: arXiv_CV
author: Danping Liao, Yuntao Qian, Yuan Yan Tang
---

* content
{:toc}

##### Abstract
Displaying the large number of bands in a hyper- spectral image (HSI) on a trichromatic monitor is important for HSI processing and analysis system. The visualized image shall convey as much information as possible from the original HSI and meanwhile facilitate image interpretation. However, most existing methods display HSIs in false color, which contradicts with user experience and expectation. In this paper, we propose a visualization approach based on constrained manifold learning, whose goal is to learn a visualized image that not only preserves the manifold structure of the HSI but also has natural colors. Manifold learning preserves the image structure by forcing pixels with similar signatures to be displayed with similar colors. A composite kernel is applied in manifold learning to incorporate both the spatial and spectral information of HSI in the embedded space. The colors of the output image are constrained by a corresponding natural-looking RGB image, which can either be generated from the HSI itself (e.g., band selection from the visible wavelength) or be captured by a separate device. Our method can be done at instance-level and feature-level. Instance-level learning directly obtains the RGB coordinates for the pixels in the HSI while feature-level learning learns an explicit mapping function from the high dimensional spectral space to the RGB space. Experimental results demonstrate the advantage of the proposed method in information preservation and natural color visualization.

##### Abstract (translated by Google)
在HSI处理和分析系统中，在三色监视器上显示高光谱图像（HSI）中的大量条带是重要的。可视化的图像应该传达尽可能多的原始HSI信息，同时便于图像解译。但是，现有的方法大都是假彩色的，这与用户的体验和期望相矛盾。在本文中，我们提出了一种基于约束流形学习的可视化方法，其目标是学习一个可视化的图像，不仅保留HSI的流形结构，而且具有自然色彩。流形学习通过强制具有相似签名的像素以相似的颜色显示来保持图像结构。将复合核应用于流形学习，将HSI的空间和光谱信息同时嵌入到嵌入空间中。输出图像的颜色受到相应的自然的RGB图像的约束，该自然的RGB图像可以从HSI本身（例如，从可见波长的带选择）生成或由单独的设备捕获。我们的方法可以在实例级和功能级完成。实例级学习直接获得HSI中像素的RGB坐标，而特征级学习则学习从高维光谱空间到RGB空间的显式映射函数。实验结果表明了该方法在信息保存和自然色可视化中的优势。

##### URL
[https://arxiv.org/abs/1712.01657](https://arxiv.org/abs/1712.01657)

