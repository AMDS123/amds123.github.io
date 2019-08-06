---
layout: post
title: "Simultaneous Semantic Segmentation and Outlier Detection in Presence of Domain Shift"
date: 2019-08-03 00:49:00
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Detection
author: Petra Bevandi&#x107;, Ivan Kre&#x161;o, Marin Or&#x161;i&#x107;, Sini&#x161;a &#x160;egvi&#x107;
mathjax: true
---

* content
{:toc}

##### Abstract
Recent success on realistic road driving datasets has increased interest in exploring robust performance in real-world applications. One of the major unsolved problems is to identify image content which can not be reliably recognized with a given inference engine. We therefore study approaches to recover a dense outlier map alongside the primary task with a single forward pass, by relying on shared convolutional features. We consider semantic segmentation as the primary task and perform extensive validation on WildDash val (inliers), LSUN val (outliers), and pasted objects from Pascal VOC 2007 (outliers). We achieve the best validation performance by training to discriminate inliers from pasted ImageNet-1k content, even though ImageNet-1k contains many road-driving pixels, and, at least nominally, fails to account for the full diversity of the visual world. The proposed two-head model performs comparably to the C-way multi-class model trained to predict uniform distribution in outliers, while outperforming several other validated approaches. We evaluate our best two models on the WildDash test dataset and set a new state of the art on the WildDash benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01098](http://arxiv.org/abs/1908.01098)

##### PDF
[http://arxiv.org/pdf/1908.01098](http://arxiv.org/pdf/1908.01098)

