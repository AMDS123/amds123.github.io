---
layout: post
title: "Effects of Blur and Deblurring to Visual Object Tracking"
date: 2019-08-21 15:02:14
categories: arXiv_CV
tags: arXiv_CV GAN Tracking Object_Tracking Quantitative
author: Qing Guo, Wei Feng, Zhihao Chen, Ruijun Gao, Liang Wan, Song Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Intuitively, motion blur may hurt the performance of visual object tracking. However, we lack quantitative evaluation of tracker robustness to different levels of motion blur. Meanwhile, while image deblurring methods can produce visually clearer videos for pleasing human eyes, it is unknown whether visual object tracking can benefit from image deblurring or not. In this paper, we address these two problems by constructing a Blurred Video Tracking benchmark, which contains a variety of videos with different levels of motion blurs, as well as ground truth tracking results for evaluating trackers. We extensively evaluate 23 trackers on this benchmark and observe several new interesting results. Specifically, we find that light blur may improve the performance of many trackers, but heavy blur always hurts the tracking performance. We also find that image deblurring may help to improve tracking performance on heavily blurred videos but hurt the performance on lightly blurred videos. According to these observations, we propose a new GAN based scheme to improve the tracker robustness to motion blurs. In this scheme, a finetuned discriminator is used as an adaptive assessor to selectively deblur frames during the tracking process. We use this scheme to successfully improve the accuracy and robustness of 6 trackers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07904](http://arxiv.org/abs/1908.07904)

##### PDF
[http://arxiv.org/pdf/1908.07904](http://arxiv.org/pdf/1908.07904)

