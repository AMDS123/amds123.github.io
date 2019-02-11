---
layout: post
title: "Skeleton-Based Online Action Prediction Using Scale Selection Network"
date: 2019-02-08 14:04:25
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Jun Liu, Amir Shahroudy, Gang Wang, Ling-Yu Duan, Alex C. Kot
mathjax: true
---

* content
{:toc}

##### Abstract
Action prediction is to recognize the class label of an ongoing activity when only a part of it is observed. In this paper, we focus on online action prediction in streaming 3D skeleton sequences. A dilated convolutional network is introduced to model the motion dynamics in temporal dimension via a sliding window over the temporal axis. Since there are significant temporal scale variations in the observed part of the ongoing action at different time steps, a novel window scale selection method is proposed to make our network focus on the performed part of the ongoing action and try to suppress the possible incoming interference from the previous actions at each step. An activation sharing scheme is also proposed to handle the overlapping computations among the adjacent time steps, which enables our framework to run more efficiently. Moreover, to enhance the performance of our framework for action prediction with the skeletal input data, a hierarchy of dilated tree convolutions are also designed to learn the multi-level structured semantic representations over the skeleton joints at each frame. Our proposed approach is evaluated on four challenging datasets. The extensive experiments demonstrate the effectiveness of our method for skeleton-based online action prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03084](http://arxiv.org/abs/1902.03084)

##### PDF
[http://arxiv.org/pdf/1902.03084](http://arxiv.org/pdf/1902.03084)

