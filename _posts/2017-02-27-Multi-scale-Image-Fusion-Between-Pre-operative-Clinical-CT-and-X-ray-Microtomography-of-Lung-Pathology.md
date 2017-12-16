---
layout: post
title: "Multi-scale Image Fusion Between Pre-operative Clinical CT and X-ray Microtomography of Lung Pathology"
date: 2017-02-27 06:04:52
categories: arXiv_CV
tags: arXiv_CV GAN Face Optimization Quantitative
author: Holger R. Roth, Kai Nagara, Hirohisa Oda, Masahiro Oda, Tomoshi Sugiyama, Shota Nakamura, Kensaku Mori
mathjax: true
---

* content
{:toc}

##### Abstract
Computational anatomy allows the quantitative analysis of organs in medical images. However, most analysis is constrained to the millimeter scale because of the limited resolution of clinical computed tomography (CT). X-ray microtomography ($\mu$CT) on the other hand allows imaging of ex-vivo tissues at a resolution of tens of microns. In this work, we use clinical CT to image lung cancer patients before partial pneumonectomy (resection of pathological lung tissue). The resected specimen is prepared for $\mu$CT imaging at a voxel resolution of 50 $\mu$m (0.05 mm). This high-resolution image of the lung cancer tissue allows further insides into understanding of tumor growth and categorization. For making full use of this additional information, image fusion (registration) needs to be performed in order to re-align the $\mu$CT image with clinical CT. We developed a multi-scale non-rigid registration approach. After manual initialization using a few landmark points and rigid alignment, several levels of non-rigid registration between down-sampled (in the case of $\mu$CT) and up-sampled (in the case of clinical CT) representations of the image are performed. Any non-lung tissue is ignored during the computation of the similarity measure used to guide the registration during optimization. We are able to recover the volume differences introduced by the resection and preparation of the lung specimen. The average ($\pm$ std. dev.) minimum surface distance between $\mu$CT and clinical CT at the resected lung surface is reduced from 3.3 $\pm$ 2.9 (range: [0.1, 15.9]) to 2.3 mm $\pm$ 2.8 (range: [0.0, 15.3]) mm. The alignment of clinical CT with $\mu$CT will allow further registration with even finer resolutions of $\mu$CT (up to 10 $\mu$m resolution) and ultimately with histopathological microscopy images for further macro to micro image fusion that can aid medical image analysis.

##### Abstract (translated by Google)
计算解剖学允许定量分析医学图像中的器官。然而，由于临床计算机断层扫描（CT）的分辨率有限，大多数分析被限制在毫米级别。另一方面，X射线显微摄影（$ \ mu $ CT）允许以数十微米的分辨率对离体组织进行成像。在这项工作中，我们使用临床CT对肺癌患者进行部分全肺切除术（切除病理性肺组织）。切除的标本准备在体素分辨率为50美元/米（0.05毫米）的$ \ mu $ CT成像。这种肺癌组织的高分辨率图像可以进一步了解肿瘤生长和分类。为了充分利用这些附加信息，需要执行图像融合（注册）以便将$ \ mu $ CT图像与临床CT重新对齐。我们开发了一种多尺度的非刚性注册方法。在使用几个界标点和刚性对准的手动初始化之后，在下采样（在$ \ mu $ CT的情况下）和向上采样的（在临床CT的情况下）图像之间的几个级别的非刚性配准执行。在计算用于指导优化期间的配准的相似性度量时，忽略任何非肺部组织。我们能够恢复由切除和准备肺标本引起的体积差异。 $ \ mu $ CT与切除的肺表面的临床CT之间的平均（$ \ pm $ std。dev。）最小表面距离从3.3 $ / pm $ 2.9（范围：[0.1,15.9]）降低到2.3 mm $ \ pm $ 2.8（范围：[0.0，15.3]）毫米。临床CT与$ \ mu $ CT的对齐将允许进一​​步注册更高分辨率的$ \ mu $ CT（最高可达10美元/分钟），并最终用组织病理学显微镜图像进一步进行宏观到微观的图像融合。可以帮助医学图像分析。

##### URL
[https://arxiv.org/abs/1702.08155](https://arxiv.org/abs/1702.08155)

##### PDF
[https://arxiv.org/pdf/1702.08155](https://arxiv.org/pdf/1702.08155)

