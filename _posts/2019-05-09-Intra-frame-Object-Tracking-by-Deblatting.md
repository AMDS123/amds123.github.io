---
layout: post
title: "Intra-frame Object Tracking by Deblatting"
date: 2019-05-09 13:48:01
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking
author: Jan Kotera, Denys Rozumnyi, Filip &#x160;roubek, Ji&#x159;&#xed; Matas
mathjax: true
---

* content
{:toc}

##### Abstract
Objects moving at high speed along complex trajectories often appear in videos, especially videos of sports. Such objects elapse non-negligible distance during exposure time of a single frame and therefore their position in the frame is not well defined. They appear as semi-transparent streaks due to the motion blur and cannot be reliably tracked by standard trackers. We propose a novel approach called Tracking by Deblatting based on the observation that motion blur is directly related to the intra-frame trajectory of an object. Blur is estimated by solving two intertwined inverse problems, blind deblurring and image matting, which we call deblatting. The trajectory is then estimated by fitting a piecewise quadratic curve, which models physically justifiable trajectories. As a result, tracked objects are precisely localized with higher temporal resolution than by conventional trackers. The proposed TbD tracker was evaluated on a newly created dataset of videos with ground truth obtained by a high-speed camera using a novel Trajectory-IoU metric that generalizes the traditional Intersection over Union and measures the accuracy of the intra-frame trajectory. The proposed method outperforms baseline both in recall and trajectory accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03633](http://arxiv.org/abs/1905.03633)

##### PDF
[http://arxiv.org/pdf/1905.03633](http://arxiv.org/pdf/1905.03633)

