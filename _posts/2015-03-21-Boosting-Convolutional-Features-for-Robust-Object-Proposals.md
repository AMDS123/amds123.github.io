---
layout: post
title: "Boosting Convolutional Features for Robust Object Proposals"
date: 2015-03-21 20:54:39
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation CNN Image_Classification Classification Detection
author: Nikolaos Karianakis, Thomas J. Fuchs, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNNs) have demonstrated excellent performance in image classification, but still show room for improvement in object-detection tasks with many categories, in particular for cluttered scenes and occlusion. Modern detection algorithms like Regions with CNNs (Girshick et al., 2014) rely on Selective Search (Uijlings et al., 2013) to propose regions which with high probability represent objects, where in turn CNNs are deployed for classification. Selective Search represents a family of sophisticated algorithms that are engineered with multiple segmentation, appearance and saliency cues, typically coming with a significant run-time overhead. Furthermore, (Hosang et al., 2014) have shown that most methods suffer from low reproducibility due to unstable superpixels, even for slight image perturbations. Although CNNs are subsequently used for classification in top-performing object-detection pipelines, current proposal methods are agnostic to how these models parse objects and their rich learned representations. As a result they may propose regions which may not resemble high-level objects or totally miss some of them. To overcome these drawbacks we propose a boosting approach which directly takes advantage of hierarchical CNN features for detecting regions of interest fast. We demonstrate its performance on ImageNet 2013 detection benchmark and compare it with state-of-the-art methods.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）在图像分类中表现出优异的性能，但在许多类别的物体检测任务中仍然显示出改进空间，特别是对于混乱的场景和遮挡。像CNNs这样的现代检测算法（Girshick et al。，2014）依靠选择性搜索（Uijlings et al。，2013）来提出高概率的区域代表对象，而CNN则被用于分类。选择性搜索表示一系列复杂的算法，这些算法通过多重分割，外观和显着性提示进行设计，通常会带来显着的运行时间开销。此外，（Hosang等人，2014）已经表明，由于不稳定的超像素，大多数方法的再现性低，即使对于轻微的图像扰动也是如此。虽然CNN随后被用于顶级执行对象检测管道中的分类，但是当前的提议方法不知道这些模型如何解析对象及其丰富的学习表示。因此，他们可能会提出可能不像高级对象或完全错过其中一些地区的地区。为了克服这些缺点，我们提出了一种直接利用分层CNN特征快速检测感兴趣区域的提升方法。我们在ImageNet 2013检测基准上展示其性能，并将其与最先进的方法进行比较。

##### URL
[https://arxiv.org/abs/1503.06350](https://arxiv.org/abs/1503.06350)

##### PDF
[https://arxiv.org/pdf/1503.06350](https://arxiv.org/pdf/1503.06350)

