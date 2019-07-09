---
layout: post
title: "TrackNet: A Deep Learning Network for Tracking High-speed and Tiny Objects in Sports Applications"
date: 2019-07-08 16:08:43
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Deep_Learning Detection
author: Yu-Chuan Huang, I-No Liao, Ching-Hsuan Chen, Ts&#xec;-U&#xed; &#x130;k, Wen-Chih Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Ball trajectory data are one of the most fundamental and useful information in the evaluation of players' performance and analysis of game strategies. Although vision-based object tracking techniques have been developed to analyze sport competition videos, it is still challenging to recognize and position a high-speed and tiny ball accurately. In this paper, we develop a deep learning network, called TrackNet, to track the tennis ball from broadcast videos in which the ball images are small, blurry, and sometimes with afterimage tracks or even invisible. The proposed heatmap-based deep learning network is trained to not only recognize the ball image from a single frame but also learn flying patterns from consecutive frames. TrackNet takes images with a size of $640\times360$ to generate a detection heatmap from either a single frame or several consecutive frames to position the ball and can achieve high precision even on public domain videos. The network is evaluated on the video of the men's singles final at the 2017 Summer Universiade, which is available on YouTube. The precision, recall, and F1-measure of TrackNet reach $99.7\%$, $97.3\%$, and $98.5\%$, respectively. To prevent overfitting, 9 additional videos are partially labeled together with a subset from the previous dataset to implement 10-fold cross-validation, and the precision, recall, and F1-measure are $95.3\%$, $75.7\%$, and $84.3\%$, respectively. A conventional image processing algorithm is also implemented to compare with TrackNet. Our experiments indicate that TrackNet outperforms conventional method by a big margin and achieves exceptional ball tracking performance. The dataset and demo video are available at https://nol.cs.nctu.edu.tw/ndo3je6av9/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03698](http://arxiv.org/abs/1907.03698)

##### PDF
[http://arxiv.org/pdf/1907.03698](http://arxiv.org/pdf/1907.03698)

