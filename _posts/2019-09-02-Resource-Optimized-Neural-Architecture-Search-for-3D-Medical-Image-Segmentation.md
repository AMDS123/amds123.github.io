---
layout: post
title: "Resource Optimized Neural Architecture Search for 3D Medical Image Segmentation"
date: 2019-09-02 05:08:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Reinforcement_Learning Deep_Learning
author: Woong Bae, Seungho Lee, Yeha Lee, Beomhee Park, Minki Chung, Kyu-Hwan Jung
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search (NAS), a framework which automates the task of designing neural networks, has recently been actively studied in the field of deep learning. However, there are only a few NAS methods suitable for 3D medical image segmentation. Medical 3D images are generally very large; thus it is difficult to apply previous NAS methods due to their GPU computational burden and long training time. We propose the resource-optimized neural architecture search method which can be applied to 3D medical segmentation tasks in a short training time (1.39 days for 1GB dataset) using a small amount of computation power (one RTX 2080Ti, 10.8GB GPU memory). Excellent performance can also be achieved without retraining(fine-tuning) which is essential in most NAS methods. These advantages can be achieved by using a reinforcement learning-based controller with parameter sharing and focusing on the optimal search space configuration of macro search rather than micro search. Our experiments demonstrate that the proposed NAS method outperforms manually designed networks with state-of-the-art performance in 3D medical image segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00548](http://arxiv.org/abs/1909.00548)

##### PDF
[http://arxiv.org/pdf/1909.00548](http://arxiv.org/pdf/1909.00548)

