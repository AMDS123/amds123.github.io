---
layout: post
title: "Classifying a specific image region using convolutional nets with an ROI mask as input"
date: 2018-12-01 23:52:37
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Image_Classification Classification
author: Sagi Eppel
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural nets (CNN) are the leading computer vision method for classifying images. In some cases, it is desirable to classify only a specific region of the image that corresponds to a certain object. Hence, assuming that the region of the object in the image is known in advance and is given as a binary region of interest (ROI) mask, the goal is to classify the object in this region using a convolutional neural net. This goal is achieved using a standard image classification net with the addition of a side branch, which converts the ROI mask into an attention map. This map is then combined with the image classification net. This allows the net to focus the attention on the object region while still extracting contextual cues from the background. This approach was evaluated using the COCO object dataset and the OpenSurfaces materials dataset. In both cases, it gave superior results to methods that completely ignore the background region. In addition, it was found that combining the attention map at the first layer of the net gave better results than combining it at higher layers or multiple layers of the net. The advantages of this method are most apparent in the classification of small regions which demands a great deal of contextual information from the background.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00291](http://arxiv.org/abs/1812.00291)

##### PDF
[http://arxiv.org/pdf/1812.00291](http://arxiv.org/pdf/1812.00291)

