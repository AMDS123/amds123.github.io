---
layout: post
title: "A Multiresolution Convolutional Neural Network with Partial Label Training for Annotating Reflectance Confocal Microscopy Images of Skin"
date: 2018-08-23 01:09:52
categories: arXiv_CV
tags: arXiv_CV CNN
author: Alican Bozkurt, Kivanc Kose, Christi Alessi-Fox, Melissa Gill, Dana H. Brooks, Jennifer G. Dy, Milind Rajadhyaksha
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a new multiresolution "nested encoder-decoder" convolutional network architecture and use it to annotate morphological patterns in reflectance confocal microscopy (RCM) images of human skin for aiding cancer diagnosis. Skin cancers are the most common types of cancers, melanoma being the deadliest among them. RCM is an effective, non-invasive pre-screening tool for skin cancer diagnosis, with the required cellular resolution. However, images are complex, low-contrast, and highly variable, so that clinicians require months to years of expert-level training to be able to make accurate assessments. In this paper, we address classifying 4 key clinically important structural/textural patterns in RCM images. The occurrence and morphology of these patterns are used by clinicians for diagnosis of melanomas. The large size of RCM images, the large variance of pattern size, the large-scale range over which patterns appear, the class imbalance in collected images, and the lack of fully-labeled images all make this a challenging problem to address, even with automated machine learning tools. We designed a novel nested U-net architecture to cope with these challenges, and a selective loss function to handle partial labeling. Trained and tested on 56 melanoma-suspicious, partially labeled, 12k x 12k pixel images, our network automatically annotated diagnostic patterns with high sensitivity and specificity, providing consistent labels for unlabeled sections of the test images. Providing such annotation will aid clinicians in achieving diagnostic accuracy, and perhaps more important, dramatically facilitate clinical training, thus enabling much more rapid adoption of RCM into widespread clinical use process. In addition, our adaptation of U-net architecture provides an intrinsically multiresolution deep network that may be useful in other challenging biomedical image analysis applications.

##### Abstract (translated by Google)
我们描述了一种新的多分辨率“嵌套编码器 - 解码器”卷积网络结构，并用它来注释人体皮肤的反射共聚焦显微镜（RCM）图像中的形态模式，以帮助诊断癌症。皮肤癌是最常见的癌症类型，黑色素瘤是其中最致命的癌症。 RCM是一种有效的，非侵入性的预筛查工具，用于皮肤癌诊断，具有所需的细胞分辨率。然而，图像复杂，低对比度和高度可变，因此临床医生需要数月至数年的专家级培训才能进行准确的评估。在本文中，我们讨论了RCM图像中4个关键临床重要结构/纹理模式的分类。临床医生使用这些模式的出现和形态来诊断黑素瘤。 RCM图像的大尺寸，图案尺寸的大变化，图案出现的大范围，收集图像中的类不平衡以及缺乏完全标记的图像都使得这一问题难以解决，即使是自动化机器学习工具。我们设计了一种新颖的嵌套U-net架构来应对这些挑战，并设计了一种选择性丢失功能来处理部分标记。我们的网络对56个黑色素瘤 - 可疑，部分标记的12k x 12k像素图像进行了培训和测试，自动注释了具有高灵敏度和特异性的诊断模式，为未标记的测试图像部分提供了一致的标签。提供这样的注释将有助于临床医生实现诊断准确性，并且可能更重要的是，大大促进临床培训，从而使RCM能够更快地被广泛应用于广泛的临床使用过程中。此外，我们对U-net架构的改编提供了一种本质上多分辨率的深度网络，可用于其他具有挑战性的生物医学图像分析应用。

##### URL
[http://arxiv.org/abs/1802.02213](http://arxiv.org/abs/1802.02213)

##### PDF
[http://arxiv.org/pdf/1802.02213](http://arxiv.org/pdf/1802.02213)

