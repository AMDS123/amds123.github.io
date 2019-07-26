---
layout: post
title: "MultiDepth: Single-Image Depth Estimation via Multi-Task Regression and Classification"
date: 2019-07-25 14:43:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Optimization Classification Prediction
author: Lukas Liebel, Marco K&#xf6;rner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce MultiDepth, a novel training strategy and convolutional neural network (CNN) architecture that allows approaching single-image depth estimation (SIDE) as a multi-task problem. SIDE is an important part of road scene understanding. It, thus, plays a vital role in advanced driver assistance systems and autonomous vehicles. Best results for the SIDE task so far have been achieved using deep CNNs. However, optimization of regression problems, such as estimating depth, is still a challenging task. For the related tasks of image classification and semantic segmentation, numerous CNN-based methods with robust training behavior have been proposed. Hence, in order to overcome the notorious instability and slow convergence of depth value regression during training, MultiDepth makes use of depth interval classification as an auxiliary task. The auxiliary task can be disabled at test-time to predict continuous depth values using the main regression branch more efficiently. We applied MultiDepth to road scenes and present results on the KITTI depth prediction dataset. In experiments, we were able to show that end-to-end multi-task learning with both, regression and classification, is able to considerably improve training and yield more accurate results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11111](http://arxiv.org/abs/1907.11111)

##### PDF
[http://arxiv.org/pdf/1907.11111](http://arxiv.org/pdf/1907.11111)

