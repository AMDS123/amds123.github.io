---
layout: post
title: "Weighted Point Cloud Augmentation for Neural Network Training Data Class-Imbalance"
date: 2019-04-09 07:31:37
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: David Griffiths, Jan Boehm
mathjax: true
---

* content
{:toc}

##### Abstract
Recent developments in the field of deep learning for 3D data have demonstrated promising potential for end-to-end learning directly from point clouds. However, many real-world point clouds contain a large class im-balance due to the natural class im-balance observed in nature. For example, a 3D scan of an urban environment will consist mostly of road and facade, whereas other objects such as poles will be under-represented. In this paper we address this issue by employing a weighted augmentation to increase classes that contain fewer points. By mitigating the class im-balance present in the data we demonstrate that a standard PointNet++ deep neural network can achieve higher performance at inference on validation data. This was observed as an increase of F1 score of 19% and 25% on two test benchmark datasets; ScanNet and Semantic3D respectively where no class im-balance pre-processing had been performed. Our networks performed better on both highly-represented and under-represented classes, which indicates that the network is learning more robust and meaningful features when the loss function is not overly exposed to only a few classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04094](http://arxiv.org/abs/1904.04094)

##### PDF
[http://arxiv.org/pdf/1904.04094](http://arxiv.org/pdf/1904.04094)

