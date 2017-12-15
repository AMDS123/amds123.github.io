---
layout: post
title: "Automated Resolution Selection for Image Segmentation"
date: 2016-05-22 17:09:29
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Fares Al-Qunaieer, Hamid R. Tizhoosh, Shahryar Rahnamayan
mathjax: true
---

* content
{:toc}

##### Abstract
It is well-known in image processing that computational cost increases rapidly with the number and dimensions of the images to be processed. Several fields, such as medical imaging, routinely use numerous very large images, which might also be 3D and/or captured at several frequency bands, all adding to the computational expense. Multiresolution analysis is a method of increasing the efficiency of the segmentation process. One multiresolution approach is the coarse-to-fine segmentation strategy, whereby the segmentation starts at a coarse resolution and is then fine-tuned during subsequent steps. The starting resolution for segmentation is generally selected arbitrarily with no clear selection criteria. The research reported in this paper showed that starting from different resolutions for image segmentation results in different accuracies and computational times, even for images of the same category (depicting similar scenes or objects). An automated method for resolution selection for an input image would thus be beneficial. This paper introduces a framework for the automated selection of the best resolution for image segmentation. We propose a measure for defining the best resolution based on user/system criteria, offering a trade-off between accuracy and computation time. A learning approach is then introduced for the selection of the resolution, whereby extracted image features are mapped to the previously determined best resolution. In the learning process, class (i.e., resolution) distribution is generally imbalanced, making effective learning from the data difficult. Experiments conducted with three datasets using two different segmentation algorithms show that the resolutions selected through learning enable much faster segmentation than the original ones, while retaining at least the original accuracy.

##### Abstract (translated by Google)
在图像处理中众所周知的是，随着要处理的图像的数量和尺寸，计算成本迅速增加。诸如医学成像之类的几个领域通常使用许多非常大的图像，这些图像也可能是3D和/或在几个频带被捕获的，这些都增加了计算成本。多分辨率分析是提高分割过程效率的一种方法。一种多分辨率方法是从粗到细的分割策略，其中分割以粗分辨率开始，然后在随后的步骤中进行微调。分割的起始分辨率一般是任意选择的，没有明确的选择标准。本文报道的研究表明，从不同的分辨率开始，对于同一类别的图像（描绘相似的场景或物体），会导致不同的精度和计算时间。因此，对输入图像进行分辨率选择的自动化方法将是有益的。本文介绍了自动选择图像分割最佳分辨率的框架。我们提出一个基于用户/系统标准来定义最佳分辨率的方法，在精度和计算时间之间进行权衡。然后引入学习方法来选择分辨率，由此将提取的图像特征映射到之前确定的最佳分辨率。在学习过程中，课堂（即分辨率）的分布一般是不平衡的，难以有效地学习数据。使用两种不同的分割算法对三个数据集进行的实验显示，通过学习选择的分辨率使得分割比原始分割快得多，同时至少保持原始精度。

##### URL
[https://arxiv.org/abs/1605.06820](https://arxiv.org/abs/1605.06820)

##### PDF
[https://arxiv.org/pdf/1605.06820](https://arxiv.org/pdf/1605.06820)

