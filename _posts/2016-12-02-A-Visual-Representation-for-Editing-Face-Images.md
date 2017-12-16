---
layout: post
title: "A Visual Representation for Editing Face Images"
date: 2016-12-02 00:07:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Jiajun Lu, Kalyan Sunkavalli, Nathan Carr, Sunil Hadap, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new approach for editing face images, which enables numerous exciting applications including face relighting, makeup transfer and face detail editing. Our face edits are based on a visual representation, which includes geometry, face segmentation, albedo, illumination and detail map. To recover our visual representation, we start by estimating geometry using a morphable face model, then decompose the face image to recover the albedo, and then shade the geometry with the albedo and illumination. The residual between our shaded geometry and the input image produces our detail map, which carries high frequency information that is either insufficiently or incorrectly captured by our shading process. By manipulating the detail map, we can edit face images with reality and identity preserved. Our representation allows various applications. First, it allows a user to directly manipulate various illumination. Second, it allows non-parametric makeup transfer with input face's distinctive identity features preserved. Third, it allows non-parametric modifications to the face appearance by transferring details. For face relighting and detail editing, we evaluate via a user study and our method outperforms other methods. For makeup transfer, we evaluate via an online attractiveness evaluation system, and can reliably make people look younger and more attractive. We also show extensive qualitative comparisons to existing methods, and have significant improvements over previous techniques.

##### Abstract (translated by Google)
我们提出了一种编辑人脸图像的新方法，可以实现许多令人兴奋的应用，包括人脸重新照明，化妆转移和脸部细节编辑。我们的脸部编辑基于视觉表现，其中包括几何，脸部分割，反照率，照明和细节地图。为了恢复我们的视觉表现，我们首先使用形变人脸模型估计几何，然后分解人脸图像以恢复反照率，然后用反照率和照明对几何图形进行阴影处理。我们的阴影几何图形和输入图像之间的残差产生了我们的细节图，其中载有高频信息，这些信息要么被我们的阴影处理不足或不正确地捕获。通过操作细节图，我们可以编辑保存有真实性和身份的人脸图像。我们的表示允许各种应用。首先，它允许用户直接操纵各种照明。其次，它允许保留输入脸部独特身份特征的非参数化妆转移。第三，它允许通过传送细节来对脸部外观进行非参数修改。对于脸部重新照明和细节编辑，我们通过用户研究进行评估，我们的方法胜过其他方法。对于化妆转移，我们通过在线吸引力评估系统进行评估，并可靠地让人们看起来更年轻，更有吸引力。我们还对现有的方法进行了大量的定性比较，并比以前的技术有了显着的改进。

##### URL
[https://arxiv.org/abs/1612.00522](https://arxiv.org/abs/1612.00522)

##### PDF
[https://arxiv.org/pdf/1612.00522](https://arxiv.org/pdf/1612.00522)

