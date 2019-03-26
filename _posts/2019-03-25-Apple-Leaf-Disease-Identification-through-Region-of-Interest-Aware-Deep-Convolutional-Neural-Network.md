---
layout: post
title: "Apple Leaf Disease Identification through Region-of-Interest-Aware Deep Convolutional Neural Network"
date: 2019-03-25 14:15:40
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification Recognition
author: Hee-Jin Yu, Chang-Hwan Son
mathjax: true
---

* content
{:toc}

##### Abstract
A new method of recognizing apple leaf diseases through region-of-interest-aware deep convolutional neural network is proposed in this paper. The primary idea is that leaf disease symptoms appear in the leaf area whereas the background region contains no useful information regarding leaf diseases. To realize this idea, two subnetworks are first designed. One is for the division of the input image into three areas: background, leaf area, and spot area indicating the leaf diseases, which is the region of interest, and the other is for the classification of leaf diseases. The two subnetworks exhibit the architecture types of an encoder-decoder network and VGG network, respectively; subsequently, they are trained separately through transfer learning with a new training set containing class information, according to the types of leaf diseases and the ground truth images where the background, leaf area, and spot area are separated. Next, to connect these subnetworks and subsequently train the connected whole network in an end-to-end manner, the predicted ROI feature map is stacked on the top of the input image through a fusion layer, and subsequently fed into the subnetwork used for the leaf disease identification. The experimental results indicate that correct recognition accuracy can be increased using the predicted ROI feature map. It is also shown that the proposed method obtains better performance than the conventional state-of-the-art methods: transfer-learning-based methods, bilinear model, and multiscale-based deep feature extraction, and pooling approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10356](http://arxiv.org/abs/1903.10356)

##### PDF
[http://arxiv.org/pdf/1903.10356](http://arxiv.org/pdf/1903.10356)

