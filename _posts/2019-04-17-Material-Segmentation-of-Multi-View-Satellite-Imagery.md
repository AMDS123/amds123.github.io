---
layout: post
title: "Material Segmentation of Multi-View Satellite Imagery"
date: 2019-04-17 23:52:20
categories: arXiv_AI
tags: arXiv_AI Sparse Segmentation Semantic_Segmentation Classification Prediction Recognition
author: Matthew Purri, Jia Xue, Kristin Dana, Matthew Leotta, Dan Lipsa, Zhixin Li, Bo Xu, Jie Shan
mathjax: true
---

* content
{:toc}

##### Abstract
Material recognition methods use image context and local cues for pixel-wise classification. In many cases only a single image is available to make a material prediction. Image sequences, routinely acquired in applications such as mutliview stereo, can provide a sampling of the underlying reflectance functions that reveal pixel-level material attributes. We investigate multi-view material segmentation using two datasets generated for building material segmentation and scene material segmentation from the SpaceNet Challenge satellite image dataset. In this paper, we explore the impact of multi-angle reflectance information by introducing the \textit{reflectance residual encoding}, which captures both the multi-angle and multispectral information present in our datasets. The residuals are computed by differencing the sparse-sampled reflectance function with a dictionary of pre-defined dense-sampled reflectance functions. Our proposed reflectance residual features improves material segmentation performance when integrated into pixel-wise and semantic segmentation architectures. At test time, predictions from individual segmentations are combined through softmax fusion and refined by building segment voting. We demonstrate robust and accurate pixelwise segmentation results using the proposed material segmentation pipeline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08537](http://arxiv.org/abs/1904.08537)

##### PDF
[http://arxiv.org/pdf/1904.08537](http://arxiv.org/pdf/1904.08537)

