---
layout: post
title: "Joint shape learning and segmentation for medical images using a minimalistic deep network"
date: 2019-01-25 10:53:57
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Balamurali Murugesan, Kaushik Sarveswaran, Sharath M Shankaranarayana, Keerthi Ram, Mohanasankar Sivaprakasam
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, state-of-the-art results have been achieved in semantic segmentation using fully convolutional networks (FCNs). Most of these networks employ encoder-decoder style architecture similar to U-Net and are trained with images and the corresponding segmentation maps as a pixel-wise classification task. Such frameworks only exploit class information by using the ground truth segmentation maps. In this paper, we propose a multi-task learning framework with the main aim of exploiting structural and spatial information along with the class information. We modify the decoder part of the FCN to exploit class information and the structural information as well. We intend to do this while also keeping the parameters of the network as low as possible. We obtain the structural information using either of the two ways: i) using the contour map and ii) using the distance map, both of which can be obtained from ground truth segmentation maps with no additional annotation costs. We also explore different ways in which distance maps can be computed and study the effects of different distance maps on the segmentation performance. We also experiment extensively on two different medical image segmentation applications: i.e i) using color fundus images for optic disc and cup segmentation and ii) using endoscopic images for polyp segmentation. Through our experiments, we report results comparable to, and in some cases performing better than the current state-of-the-art architectures and with an order of 2x reduction in the number of parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.08824](http://arxiv.org/abs/1901.08824)

##### PDF
[http://arxiv.org/pdf/1901.08824](http://arxiv.org/pdf/1901.08824)

