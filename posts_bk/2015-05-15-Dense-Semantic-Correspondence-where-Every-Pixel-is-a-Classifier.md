---
layout: post
title: "Dense Semantic Correspondence where Every Pixel is a Classifier"
date: 2015-05-15 18:04:07
categories: arXiv_CV
tags: arXiv_CV Detection Recognition
author: Hilton Bristow, Jack Valmadre, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
Determining dense semantic correspondences across objects and scenes is a difficult problem that underpins many higher-level computer vision algorithms. Unlike canonical dense correspondence problems which consider images that are spatially or temporally adjacent, semantic correspondence is characterized by images that share similar high-level structures whose exact appearance and geometry may differ. Motivated by object recognition literature and recent work on rapidly estimating linear classifiers, we treat semantic correspondence as a constrained detection problem, where an exemplar LDA classifier is learned for each pixel. LDA classifiers have two distinct benefits: (i) they exhibit higher average precision than similarity metrics typically used in correspondence problems, and (ii) unlike exemplar SVM, can output globally interpretable posterior probabilities without calibration, whilst also being significantly faster to train. We pose the correspondence problem as a graphical model, where the unary potentials are computed via convolution with the set of exemplar classifiers, and the joint potentials enforce smoothly varying correspondence assignment.

##### Abstract (translated by Google)
确定跨对象和场景的密集语义对应关系是许多高级计算机视觉算法的一个难题。与考虑空间上或时间上相邻的图像的规范密集对应问题不同，语义对应的特征在于共享类似的高级结构的图像，其精确的外观和几何形状可能不同。受到物体识别文献和近期关于快速估计线性分类器的研究的启发，我们将语义对应作为一个约束检测问题，其中每个像素学习一个示例LDA分类器。 LDA分类器有两个不同的好处：（1）它们比对应性问题中通常使用的相似性度量表现出更高的平均精确度;（2）与典型SVM不同，能够输出全局可解释的后验概率而不需要校准，同时训练速度也快得多。我们把对应问题作为一个图形模型，通过与样本分类器的集合进行卷积来计算一元电位，并且联合电位强制平滑地改变对应关系分配。

##### URL
[https://arxiv.org/abs/1505.04143](https://arxiv.org/abs/1505.04143)

##### PDF
[https://arxiv.org/pdf/1505.04143](https://arxiv.org/pdf/1505.04143)

