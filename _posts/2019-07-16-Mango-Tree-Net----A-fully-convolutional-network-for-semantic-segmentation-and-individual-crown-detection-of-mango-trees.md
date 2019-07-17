---
layout: post
title: "Mango Tree Net -- A fully convolutional network for semantic segmentation and individual crown detection of mango trees"
date: 2019-07-16 09:41:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Detection
author: Vikas Agaradahalli Gurumurthy, Ramesh Kestur, Omkar Narasipura
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a method for semantic segmentation of mango trees in high resolution aerial imagery, and, a novel method for individual crown detection of mango trees using segmentation output. Mango Tree Net, a fully convolutional neural network (FCN), is trained using supervised learning to perform semantic segmentation of mango trees in imagery acquired using an unmanned aerial vehicle (UAV). The proposed network is retrained to separate touching/overlapping tree crowns in segmentation output. Contour based connected object detection is performed on the segmentation output from retrained network. Bounding boxes are drawn on the original images using coordinates of connected objects to achieve individual crown detection. The training dataset consists of 8,824 image patches of size 240 x 240. The approach is tested for performance on segmentation and individual crown detection tasks using test datasets containing 36 and 4 images respectively. The performance is analyzed using standard metrics precision, recall, f1-score and accuracy. Results obtained demonstrate the robustness of the proposed methods despite variations in factors such as scale, occlusion, lighting conditions and surrounding vegetation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06915](http://arxiv.org/abs/1907.06915)

##### PDF
[http://arxiv.org/pdf/1907.06915](http://arxiv.org/pdf/1907.06915)

