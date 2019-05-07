---
layout: post
title: "Spatio-Temporal Action Localization in a Weakly Supervised Setting"
date: 2019-05-06 17:39:09
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Weakly_Supervised CNN Optimization Detection
author: Kurt Degiorgio, Fabio Cuzzolin
mathjax: true
---

* content
{:toc}

##### Abstract
Enabling computational systems with the ability to localize actions in video-based content has manifold applications. Traditionally, such a problem is approached in a fully-supervised setting where video-clips with complete frame-by-frame annotations around the actions of interest are provided for training. However, the data requirements needed to achieve adequate generalization in this setting is prohibitive. In this work, we circumvent this issue by casting the problem in a weakly supervised setting, i.e., by considering videos as labelled `sets' of unlabelled video segments. Firstly, we apply unsupervised segmentation to take advantage of the elementary structure of each video. Subsequently, a convolutional neural network is used to extract RGB features from the resulting video segments. Finally, Multiple Instance Learning (MIL) is employed to predict labels at the video segment level, thus inherently performing spatio-temporal action detection. In contrast to previous work, we make use of a different MIL formulation in which the label of each video segment is continuous rather then discrete, making the resulting optimization function tractable. Additionally, we utilize a set splitting technique for regularization. Experimental results considering multiple performance indicators on the UCF-Sports data-set support the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02171](http://arxiv.org/abs/1905.02171)

##### PDF
[http://arxiv.org/pdf/1905.02171](http://arxiv.org/pdf/1905.02171)

