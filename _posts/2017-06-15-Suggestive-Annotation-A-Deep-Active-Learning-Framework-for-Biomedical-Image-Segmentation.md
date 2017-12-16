---
layout: post
title: "Suggestive Annotation: A Deep Active Learning Framework for Biomedical Image Segmentation"
date: 2017-06-15 05:01:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Lin Yang, Yizhe Zhang, Jianxu Chen, Siyuan Zhang, Danny Z. Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation is a fundamental problem in biomedical image analysis. Recent advances in deep learning have achieved promising results on many biomedical image segmentation benchmarks. However, due to large variations in biomedical images (different modalities, image settings, objects, noise, etc), to utilize deep learning on a new application, it usually needs a new set of training data. This can incur a great deal of annotation effort and cost, because only biomedical experts can annotate effectively, and often there are too many instances in images (e.g., cells) to annotate. In this paper, we aim to address the following question: With limited effort (e.g., time) for annotation, what instances should be annotated in order to attain the best performance? We present a deep active learning framework that combines fully convolutional network (FCN) and active learning to significantly reduce annotation effort by making judicious suggestions on the most effective annotation areas. We utilize uncertainty and similarity information provided by FCN and formulate a generalized version of the maximum set cover problem to determine the most representative and uncertain areas for annotation. Extensive experiments using the 2015 MICCAI Gland Challenge dataset and a lymph node ultrasound image segmentation dataset show that, using annotation suggestions by our method, state-of-the-art segmentation performance can be achieved by using only 50% of training data.

##### Abstract (translated by Google)
图像分割是生物医学图像分析中的一个基本问题。深度学习的最新进展在许多生物医学图像分割基准上取得了有希望的结果。然而，由于生物医学图像（不同形态，图像设置，对象，噪声等）的巨大差异，为了在新应用中使用深度学习，通常需要一组新的训练数据。由于只有生物医学专家可以有效地进行注释，并且通常在图像（例如细胞）中有太多的实例需要注释，这可能会招致大量的注释工作和成本。在本文中，我们旨在解决以下问题：用有限的注解（例如，时间）来标注哪些实例以获得最佳性能？我们提出了一个深度积极的学习框架，结合完全卷积网络（FCN）和主动学习，通过对最有效的注释区域提出明智的建议，大大减少了注释的工作量。我们利用FCN提供的不确定性和相似性信息，制定最大集覆盖问题的广义版本，确定最具代表性和不确定性的注释领域。使用2015 MICCAI腺体挑战数据集和淋巴结超声图像分割数据集的大量实验表明，使用我们的方法的注释建议，只使用50％的训练数据就可以实现最先进的分割性能。

##### URL
[https://arxiv.org/abs/1706.04737](https://arxiv.org/abs/1706.04737)

##### PDF
[https://arxiv.org/pdf/1706.04737](https://arxiv.org/pdf/1706.04737)

