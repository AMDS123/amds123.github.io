---
layout: post
title: 'Multiframe Motion Coupling for Video Super Resolution'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: [arXiv_CV,Super Resolution]
author: Jonas Geiping, Hendrik Dirks, Daniel Cremers, Michael Moeller
---

* content
{:toc}

##### Abstract
The idea of video super resolution is to use different view points of a single scene to enhance the overall resolution and quality. Classical energy minimization approaches first establish a correspondence of the current frame to all its neighbors in some radius and then use this temporal information for enhancement. In this paper, we propose the first variational super resolution approach that computes several super resolved frames in one batch optimization procedure by incorporating motion information between the high-resolution image frames themselves. As a consequence, the number of motion estimation problems grows linearly in the number of frames, opposed to a quadratic growth of classical methods and temporal consistency is enforced naturally. We use infimal convolution regularization as well as an automatic parameter balancing scheme to automatically determine the reliability of the motion information and reweight the regularization locally. We demonstrate that our approach yields state-of-the-art results and even is competitive with machine learning approaches.

##### Abstract (translated by Google)
视频超分辨率的想法是使用单个场景的不同视点来提高总体分辨率和质量。经典能量最小化方法首先建立当前帧与其所有邻居在某个半径的对应关系，然后使用这个时间信息进行增强。在本文中，我们提出了第一种变分超分辨率方法，通过在高分辨率图像帧本身之间结合运动信息来计算一批批优化过程中的几个超分辨率帧。结果，运动估计问题的数量在帧数上呈线性增长，与经典方法的二次增长相反，并且时间一致性自然得到强化。我们使用最小卷积正则化以及自动参数平衡方案来自动确定运动信息的可靠性，并且在本地重新调整正则化。我们证明，我们的方法可以得到最先进的结果，甚至可以和机器学习方法竞争。

##### URL
[http://arxiv.org/abs/1611.07767](http://arxiv.org/abs/1611.07767)

