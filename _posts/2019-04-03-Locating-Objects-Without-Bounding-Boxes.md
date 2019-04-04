---
layout: post
title: "Locating Objects Without Bounding Boxes"
date: 2019-04-03 05:14:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Detection
author: Javier Ribera, David G&#xfc;era, Yuhao Chen, Edward J. Delp
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in convolutional neural networks (CNN) have achieved remarkable results in locating objects in images. In these networks, the training procedure usually requires providing bounding boxes or the maximum number of expected objects. In this paper, we address the task of estimating object locations without annotated bounding boxes which are typically hand-drawn and time consuming to label. We propose a loss function that can be used in any fully convolutional network (FCN) to estimate object locations. This loss function is a modification of the average Hausdorff distance between two unordered sets of points. The proposed method has no notion of bounding boxes, region proposals, or sliding windows. We evaluate our method with three datasets designed to locate people's heads, pupil centers and plant centers. We outperform state-of-the-art generic object detectors and methods fine-tuned for pupil tracking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.07564](http://arxiv.org/abs/1806.07564)

##### PDF
[http://arxiv.org/pdf/1806.07564](http://arxiv.org/pdf/1806.07564)

