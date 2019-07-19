---
layout: post
title: "A Strong Feature Representation for Siamese Network Tracker"
date: 2019-07-18 05:26:08
categories: arXiv_CV
tags: arXiv_CV Attention Tracking CNN Object_Tracking
author: Zhipeng Zhou, Rui Zhang, Dong Yin
mathjax: true
---

* content
{:toc}

##### Abstract
Object tracking has important application in assistive technologies for personalized monitoring. Recent trackers choosing AlexNet as their backbone to extract features have gained great success. However, AlexNet is too shallow to form a strong feature representation, the tracker based on the Siamese network have an accuracy gap compared with state-of-the-art algorithms. To solve this problem, this paper proposes a tracker called SiamPF. Firstly, the modified pre-trained VGG16 network is fine-tuned as the backbone. Secondly, an AlexNet-like branch is added after the third convolutional layer and merged with the response map of the backbone network to form a preliminary strong feature representation. And then, a channel attention block is designed to adaptively select the contribution features. Finally, the APCE is modified to process the response map to reduce interference and focus the tracker on the target. Our SiamPF only used ILSVRC2015-VID for training, but it achieved excellent performance on OTB-2013 / OTB-2015 / VOT2015 / VOT2017, while maintaining the real-time performance of 41FPS on the GTX 1080Ti.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07880](http://arxiv.org/abs/1907.07880)

##### PDF
[http://arxiv.org/pdf/1907.07880](http://arxiv.org/pdf/1907.07880)

