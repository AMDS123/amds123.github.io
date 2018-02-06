---
layout: post
title: "Road Segmentation in SAR Satellite Images with Deep Fully-Convolutional Neural Networks"
date: 2018-02-05 14:59:39
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Prediction
author: Corentin Henry, Seyed Majid Azimi, Nina Merkle
mathjax: true
---

* content
{:toc}

##### Abstract
Remote sensing is extensively used in cartography. As transportation networks expand, extracting roads automatically from satellite images is crucial to keep maps up-to-date. Synthetic Aperture Radar (SAR) satellites can provide high resolution topographical maps. However roads are difficult to identify in SAR images as they look visually similar to other objects like rivers and railways. Deep convolutional neural networks have been very successful in object segmentation, yet no method was developed to extract entire road networks from SAR images. This letter proposes a method based on a Fully-Convolutional Neural Network (FCNN) adjusted for road segmentation in SAR images. We study two approaches, binary segmentation and regression, intolerant and tolerant to prediction errors, respectively. The segmentation consistency is improved by applying Fully-connected Conditional Random Fields (FCRFs). We also share insights on creating a suitable dataset to facilitate future research. Our FCNN model shows promising results, successfully extracting 57% of the roads in our test dataset. We find out that the erosion effect of the FCRFs can effectively remove incoherent predictions, but is detrimental to road interconnections. The predicted roads have smooth borders yet oscillating shapes, hence regularization would help improving their straightness and connectivity.

##### Abstract (translated by Google)
遥感在制图中被广泛使用。随着交通网络的扩大，自动从卫星图像中提取道路对于保持地图更新至关重要。合成孔径雷达（SAR）卫星可以提供高分辨率的地形图。然而，道路在SAR图像中很难识别，因为它们在视觉上类似于河流和铁路等其他物体。深卷积神经网络在目标分割中是非常成功的，但没有一种方法可以从SAR图像中提取整个道路网络。这封信提出了一种基于完全卷积神经网络（FCNN）的SAR图像道路分割方法。我们分别研究两种方法，二元分割和回归，不容忍和容忍预测错误。通过应用完全连接的条件随机场（FCRF）来改善分割一致性。我们也分享了创建合适的数据集以促进未来研究的见解。我们的FCNN模型显示了有希望的结果，成功地提取了我们测试数据集中57％的道路。我们发现，FCRFs的侵蚀效应可以有效地消除不连贯的预测，但是对公路相互连接是不利的。预测的道路有平滑的边界，但形状是振荡的，因此正则化将有助于改善它们的直线度和连通性。

##### URL
[http://arxiv.org/abs/1802.01445](http://arxiv.org/abs/1802.01445)

##### PDF
[http://arxiv.org/pdf/1802.01445](http://arxiv.org/pdf/1802.01445)

