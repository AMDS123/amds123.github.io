---
layout: post
title: "Towards Robust Curve Text Detection with Conditional Spatial Expansion"
date: 2019-03-21 05:46:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Zichuan Liu, Guosheng Lin, Sheng Yang, Fayao Liu, Weisi Lin, Wang Ling Goh
mathjax: true
---

* content
{:toc}

##### Abstract
It is challenging to detect curve texts due to their irregular shapes and varying sizes. In this paper, we first investigate the deficiency of the existing curve detection methods and then propose a novel Conditional Spatial Expansion (CSE) mechanism to improve the performance of curve text detection. Instead of regarding the curve text detection as a polygon regression or a segmentation problem, we treat it as a region expansion process. Our CSE starts with a seed arbitrarily initialized within a text region and progressively merges neighborhood regions based on the extracted local features by a CNN and contextual information of merged regions. The CSE is highly parameterized and can be seamlessly integrated into existing object detection frameworks. Enhanced by the data-dependent CSE mechanism, our curve text detection system provides robust instance-level text region extraction with minimal post-processing. The analysis experiment shows that our CSE can handle texts with various shapes, sizes, and orientations, and can effectively suppress the false-positives coming from text-like textures or unexpected texts included in the same RoI. Compared with the existing curve text detection algorithms, our method is more robust and enjoys a simpler processing flow. It also creates a new state-of-art performance on curve text benchmarks with F-score of up to 78.4$\%$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08836](http://arxiv.org/abs/1903.08836)

##### PDF
[http://arxiv.org/pdf/1903.08836](http://arxiv.org/pdf/1903.08836)

