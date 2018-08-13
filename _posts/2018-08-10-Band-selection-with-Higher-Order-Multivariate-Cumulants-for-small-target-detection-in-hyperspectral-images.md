---
layout: post
title: "Band selection with Higher Order Multivariate Cumulants for small target detection in hyperspectral images"
date: 2018-08-10 12:50:52
categories: arXiv_CV
tags: arXiv_CV Detection
author: Przemys&#x142;aw G&#x142;omb, Krzysztof Domino, Micha&#x142; Romaszewski, Micha&#x142; Cholewa
mathjax: true
---

* content
{:toc}

##### Abstract
In the small target detection problem a pattern to be located is on the order of magnitude less numerous than other patterns present in the dataset. This applies both to the case of supervised detection, where the known template is expected to match in just a few areas and unsupervised anomaly detection, as anomalies are rare by definition. This problem is frequently related to the imaging applications, i.e. detection within the scene acquired by a camera. To maximize available data about the scene, hyperspectral cameras are used; at each pixel, they record spectral data in hundreds of narrow bands. 
 The typical feature of hyperspectral imaging is that characteristic properties of target materials are visible in the small number of bands, where light of certain wavelength interacts with characteristic molecules. A target-independent band selection method based on statistical principles is a versatile tool for solving this problem in different practical applications. 
 Combination of a regular background and a rare standing out anomaly will produce a distortion in the joint distribution of hyperspectral pixels. Higher Order Cumulants Tensors are a natural `window' into this distribution, allowing to measure properties and suggest candidate bands for removal. While there have been attempts at producing band selection algorithms based on the 3 rd cumulant's tensor i.e. the joint skewness, the literature lacks a systematic analysis of how the order of the cumulant tensor used affects effectiveness of band selection in detection applications. In this paper we present an analysis of a general algorithm for band selection based on higher order cumulants. We discuss its usability related to the observed breaking points in performance, depending both on method order and the desired number of bands. Finally we perform experiments and evaluate these methods in a hyperspectral detection scenario.

##### Abstract (translated by Google)
在小目标检测问题中，要定位的图案的数量级比数据集中存在的其他图案少。这适用于监督检测的情况，其中已知模板预期仅在几个区域中匹配和无监督异常检测，因为异常在定义上是罕见的。该问题经常与成像应用有关，即由相机获取的场景内的检测。为了最大化有关场景的可用数据，使用高光谱相机;在每个像素处，它们以数百个窄带记录光谱数据。
 高光谱成像的典型特征是靶材料的特征性质在少数条带中可见，其中特定波长的光与特征分子相互作用。基于统计原理的与目标无关的频带选择方法是用于在不同实际应用中解决该问题的通用工具。
 常规背景和罕见的突出异常的组合将在高光谱像素的联合分布中产生失真。高阶累积量张量是这个分布的一个自然“窗口”，允许测量属性并建议候选带移除。虽然已经尝试基于第三累积量张量（即关节偏度）产生频带选择算法，但是文献缺乏对所使用的累积量张量的顺序如何影响检测应用中的频带选择的有效性的系统分析。在本文中，我们提出了一个基于高阶累积量的频带选择的一般算法的分析。我们根据方法顺序和所需的波段数来讨论与观察到的性能断点相关的可用性。最后，我们在高光谱检测场景中进行实验并评估这些方法。

##### URL
[http://arxiv.org/abs/1808.03513](http://arxiv.org/abs/1808.03513)

##### PDF
[http://arxiv.org/pdf/1808.03513](http://arxiv.org/pdf/1808.03513)

