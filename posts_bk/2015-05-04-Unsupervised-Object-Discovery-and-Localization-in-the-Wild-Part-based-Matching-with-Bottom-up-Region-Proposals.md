---
layout: post
title: "Unsupervised Object Discovery and Localization in the Wild: Part-based Matching with Bottom-up Region Proposals"
date: 2015-05-04 16:18:58
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Minsu Cho, Suha Kwak, Cordelia Schmid, Jean Ponce
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses unsupervised discovery and localization of dominant objects from a noisy image collection with multiple object classes. The setting of this problem is fully unsupervised, without even image-level annotations or any assumption of a single dominant class. This is far more general than typical colocalization, cosegmentation, or weakly-supervised localization tasks. We tackle the discovery and localization problem using a part-based region matching approach: We use off-the-shelf region proposals to form a set of candidate bounding boxes for objects and object parts. These regions are efficiently matched across images using a probabilistic Hough transform that evaluates the confidence for each candidate correspondence considering both appearance and spatial consistency. Dominant objects are discovered and localized by comparing the scores of candidate regions and selecting those that stand out over other regions containing them. Extensive experimental evaluations on standard benchmarks demonstrate that the proposed approach significantly outperforms the current state of the art in colocalization, and achieves robust object discovery in challenging mixed-class datasets.

##### Abstract (translated by Google)
本文介绍了无监督的发现和从多个对象类嘈杂的图像集合主要对象的本地化。这个问题的设置完全没有监督，甚至没有图像级别的注释或任何一个统治阶级的假设。这比典型的共定位，共分层，或者弱监督的本地化任务要普遍得多。我们使用基于部分的区域匹配方法来处理发现和定位问题：我们使用现成的区域提议来为对象和对象部分形成一组候选边界框。这些区域使用概率霍夫（Hough）变换在图像之间有效地匹配，该变换评估每个候选对应关系的置信度，考虑外观和空间一致性。通过比较候选区域的分数并选择在其他区域中突出显示的区域来发现并定位显性物体。对标准基准的大量实验评估表明，所提出的方法明显优于共定位技术的当前状态，并且在具有挑战性的混合类数据集中实现了强大的对象发现。

##### URL
[https://arxiv.org/abs/1501.06170](https://arxiv.org/abs/1501.06170)

##### PDF
[https://arxiv.org/pdf/1501.06170](https://arxiv.org/pdf/1501.06170)

