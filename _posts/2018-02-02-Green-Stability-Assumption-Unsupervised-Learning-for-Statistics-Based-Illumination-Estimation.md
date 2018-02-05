---
layout: post
title: "Green Stability Assumption: Unsupervised Learning for Statistics-Based Illumination Estimation"
date: 2018-02-02 17:19:40
categories: arXiv_CV
tags: arXiv_CV
author: Nikola Banić, Sven Lončarić
mathjax: true
---

* content
{:toc}

##### Abstract
In the image processing pipeline of almost every digital camera there is a part dedicated to computational color constancy i.e. to removing the influence of illumination on the colors of the image scene. Some of the best known illumination estimation methods are the so called statistics-based methods. They are less accurate than the learning-based illumination estimation methods, but they are faster and simpler to implement in embedded systems, which is one of the reasons for their widespread usage. Although in the relevant literature it often appears as if they require no training, this is not true because they have parameter values that need to be fine-tuned in order to be more accurate. In this paper it is first shown that the accuracy of statistics-based methods reported in most papers was not obtained by means of the necessary cross-validation, but by using the whole benchmark datasets for both training and testing. After that the corrected results are given for the best known benchmark datasets. Finally, the so called green stability assumption is proposed that can be used to fine-tune the values of the parameters of the statistics-based methods by using only non-calibrated images without known ground-truth illumination. The obtained accuracy is practically the same as when using calibrated training images, but the whole process is much faster. The experimental results are presented and discussed. The source code is available at this http URL

##### Abstract (translated by Google)
在几乎每个数码相机的图像处理流水线中，都有一个专用于计算色彩恒定性的部分，即去除照明对图像场景的色彩的影响。一些最着名的照度估计方法是所谓的基于统计学的方法。它们不如基于学习的照明估计方法准确，但是它们在嵌入式系统中实现更快，更简单，这是其广泛使用的原因之一。尽管在相关文献中经常表现为好像不需要训练，但这是不正确的，因为它们的参数值需要进行微调，以便更准确。本文首先表明，大多数论文中统计方法的准确性不是通过必要的交叉验证获得的，而是通过使用整个基准数据集进行训练和测试。之后，针对最知名的基准数据集给出校正的结果。最后，提出了所谓的绿色稳定性假设，通过仅使用没有已知地面实况照明的非校准图像，可以用来微调基于统计的方法的参数值。获得的准确度与使用校准训练图像几乎相同，但是整个过程要快得多。实验结果进行了介绍和讨论。源代码在这个http URL中可用

##### URL
[https://arxiv.org/abs/1802.00776](https://arxiv.org/abs/1802.00776)

##### PDF
[https://arxiv.org/pdf/1802.00776](https://arxiv.org/pdf/1802.00776)

