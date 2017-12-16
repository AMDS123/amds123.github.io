---
layout: post
title: "Pedestrian Alignment Network for Large-scale Person Re-identification"
date: 2017-07-03 05:48:54
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Re-identification Object_Detection Attention Person_Re-identification Embedding CNN Detection
author: Zhedong Zheng, Liang Zheng, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (person re-ID) is mostly viewed as an image retrieval problem. This task aims to search a query person in a large image pool. In practice, person re-ID usually adopts automatic detectors to obtain cropped pedestrian images. However, this process suffers from two types of detector errors: excessive background and part missing. Both errors deteriorate the quality of pedestrian alignment and may compromise pedestrian matching due to the position and scale variances. To address the misalignment problem, we propose that alignment can be learned from an identification procedure. We introduce the pedestrian alignment network (PAN) which allows discriminative embedding learning and pedestrian alignment without extra annotations. Our key observation is that when the convolutional neural network (CNN) learns to discriminate between different identities, the learned feature maps usually exhibit strong activations on the human body rather than the background. The proposed network thus takes advantage of this attention mechanism to adaptively locate and align pedestrians within a bounding box. Visual examples show that pedestrians are better aligned with PAN. Experiments on three large-scale re-ID datasets confirm that PAN improves the discriminative ability of the feature embeddings and yields competitive accuracy with the state-of-the-art methods.

##### Abstract (translated by Google)
人重新识别（人员重新识别）大多被视为图像检索问题。该任务旨在搜索大型图像池中的查询人员。在实践中，人们通常采用自动检测器来获取裁剪后的行人图像。然而，这个过程有两种类型的检测器错误：背景过度和部分缺失。这两个错误都会恶化行人对齐的质量，并可能由于位置和尺度差异而损害行人匹配。为了解决错位问题，我们提出可以从识别程序中学习对齐。我们介绍了行人对齐网络（PAN），它允许有区别的嵌入学习和行人对齐，无需额外的注释。我们的关键观察是，当卷积神经网络（CNN）学习区分不同身份时，学习的特征地图通常对人体而不是背景表现出强烈的激励。因此，所提出的网络利用这种注意机制来在边界框内自适应地定位和对准行人。视觉例子表明，行人与PAN更好地对齐。在三个大规模的再认证数据集上的实验证实，PAN提高了特征嵌入的判别能力，并且利用最先进的方法产生了竞争精度。

##### URL
[https://arxiv.org/abs/1707.00408](https://arxiv.org/abs/1707.00408)

##### PDF
[https://arxiv.org/pdf/1707.00408](https://arxiv.org/pdf/1707.00408)

