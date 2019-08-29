---
layout: post
title: "Unsupervised Scale-consistent Depth and Ego-motion Learning from Monocular Video"
date: 2019-08-28 05:25:46
categories: arXiv_CV
tags: arXiv_CV Knowledge Prediction
author: Jia-Wang Bian, Zhichao Li, Naiyan Wang, Huangying Zhan, Chunhua Shen, Ming-Ming Cheng, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that CNN-based depth and ego-motion estimators can be learned using unlabelled monocular videos. However, the performance is limited by unidentified moving objects that violate the underlying static scene assumption in geometric image reconstruction. More significantly, due to lack of proper constraints, networks output scale-inconsistent results over different samples, i.e., the ego-motion network cannot provide full camera trajectories over a long video sequence because of the per-frame scale ambiguity. This paper tackles these challenges by proposing a geometry consistency loss for scale-consistent predictions, and an induced self-discovered mask for handling moving objects and occlusions. Since we do not leverage multi-task learning like recent works, our framework is much simpler and more efficient. Extensive evaluation results demonstrate that our depth estimator achieves the state-of-the-art performance on the standard KITTI and Make3D datasets. Moreover, we show that our ego-motion network is able to predict a globally scale-consistent camera trajectory for long video sequences, and the resulting visual odometry accuracy is competitive with the state-of-the-art model that is trained using stereo videos. To the best of our knowledge, this is the first work to show that deep networks trained using monocular video snippets can predict globally scale-consistent camera trajectories over a long video sequence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10553](http://arxiv.org/abs/1908.10553)

##### PDF
[http://arxiv.org/pdf/1908.10553](http://arxiv.org/pdf/1908.10553)

