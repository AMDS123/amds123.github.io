---
layout: post
title: "Tree-Cut for Probabilistic Image Segmentation"
date: 2015-06-11 21:55:06
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation Inference Quantitative
author: Shell X. Hu, Christopher K. I. Williams, Sinisa Todorovic
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new probabilistic generative model for image segmentation, i.e. the task of partitioning an image into homogeneous regions. Our model is grounded on a mid-level image representation, called a region tree, in which regions are recursively split into subregions until superpixels are reached. Given the region tree, image segmentation is formalized as sampling cuts in the tree from the model. Inference for the cuts is exact, and formulated using dynamic programming. Our tree-cut model can be tuned to sample segmentations at a particular scale of interest out of many possible multiscale image segmentations. This generalizes the common notion that there should be only one correct segmentation per image. Also, it allows moving beyond the standard single-scale evaluation, where the segmentation result for an image is averaged against the corresponding set of coarse and fine human annotations, to conduct a scale-specific evaluation. Our quantitative results are comparable to those of the leading gPb-owt-ucm method, with the notable advantage that we additionally produce a distribution over all possible tree-consistent segmentations of the image.

##### Abstract (translated by Google)
本文提出了一种新的图像分割的概率生成模型，即将图像划分为均匀区域的任务。我们的模型是基于一个中间级的图像表示，称为区域树，其中区域被递归地分割成子区域，直到达到超像素。给定区域树，图像分割被形式化为来自模型的树中的采样切割。推断切割是确切的，并使用动态规划制定。我们的树切模型可以被调整以在许多可能的多尺度图像分割中以特定的感兴趣的比例对分割样本进行采样。这概括了每个图像应该只有一个正确分割的常见概念。此外，它允许移动超出标准单尺度评估，其中图像的分割结果与对应的一组粗糙和精细的人注释进行平均，以进行特定尺度的评估。我们的定量结果与领先的gPb-owt-ucm方法相比，具有显着的优势，即我们还可以在图像的所有可能的树一致分割上生成一个分布。

##### URL
[https://arxiv.org/abs/1506.03852](https://arxiv.org/abs/1506.03852)

##### PDF
[https://arxiv.org/pdf/1506.03852](https://arxiv.org/pdf/1506.03852)

