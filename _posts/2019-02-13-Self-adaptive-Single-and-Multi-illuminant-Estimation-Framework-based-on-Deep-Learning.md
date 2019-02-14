---
layout: post
title: "Self-adaptive Single and Multi-illuminant Estimation Framework based on Deep Learning"
date: 2019-02-13 02:12:55
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: Yongjie Liu, Sijie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Illuminant estimation plays a key role in digital camera pipeline system, it aims at reducing color casting effect due to the influence of non-white illuminant. Recent researches handle this task by using Convolution Neural Network (CNN) as a mapping function from input image to a single illumination vector. However, global mapping approaches are difficult to deal with scenes under multi-light-sources. In this paper, we proposed a self-adaptive single and multi-illuminant estimation framework, which includes the following novelties: (1) Learning local self-adaptive kernels from the entire image for illuminant estimation with encoder-decoder CNN structure; (2) Providing confidence measurement for the prediction; (3) Clustering-based iterative fitting for computing single and multi-illumination vectors. The proposed global-to-local aggregation is able to predict multi-illuminant regionally by utilizing global information instead of training in patches, as well as brings significant improvement for single illuminant estimation. We outperform the state-of-the-art methods on standard benchmarks with the largest relative improvement of 16%. In addition, we collect a dataset contains over 13k images for illuminant estimation and evaluation. The code and dataset is available on https://github.com/LiamLYJ/KPF_WB

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04705](http://arxiv.org/abs/1902.04705)

##### PDF
[http://arxiv.org/pdf/1902.04705](http://arxiv.org/pdf/1902.04705)

