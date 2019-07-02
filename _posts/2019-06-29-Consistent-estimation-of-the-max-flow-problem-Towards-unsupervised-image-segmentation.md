---
layout: post
title: "Consistent estimation of the max-flow problem: Towards unsupervised image segmentation"
date: 2019-06-29 20:50:32
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ashif Sikandar Iquebal, Satish Bukkapatnam
mathjax: true
---

* content
{:toc}

##### Abstract
Advances in the image-based diagnostics of complex biological and manufacturing processes have brought unsupervised image segmentation to the forefront of enabling automated, on the fly decision making. However, most existing unsupervised segmentation approaches are either computationally complex or require manual parameter selection (e.g., flow capacities in max-flow/min-cut segmentation). In this work, we present a fully unsupervised segmentation approach using a continuous max-flow formulation over the image domain while optimally estimating the flow parameters from the image characteristics. More specifically, we show that the maximum a posteriori estimate of the image labels can be formulated as a continuous max-flow problem given the flow capacities are known. The flow capacities are then iteratively obtained by employing a novel Markov random field prior over the image domain. We present theoretical results to establish the posterior consistency of the flow capacities. We compare the performance of our approach on two real-world case studies including brain tumor image segmentation and defect identification in additively manufactured components using electron microscopic images. Comparative results with several state-of-the-art supervised as well as unsupervised methods suggest that the present method performs statistically similar to the supervised methods, but results in more than 90% improvement in the Dice score when compared to the state-of-the-art unsupervised methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00220](http://arxiv.org/abs/1811.00220)

##### PDF
[http://arxiv.org/pdf/1811.00220](http://arxiv.org/pdf/1811.00220)

