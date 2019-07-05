---
layout: post
title: "Sim2real transfer learning for 3D pose estimation: motion to the rescue"
date: 2019-07-04 17:27:18
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Transfer_Learning
author: Carl Doersch, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
Simulation is an anonymous, low-bias source of data where annotation can often be done automatically; however, for some tasks, current models trained on synthetic data generalize poorly to real data. The task of 3D human pose estimation is a particularly interesting example of this sim2real problem, because learning-based approaches perform reasonably well given real training data, yet labeled 3D poses are extremely difficult to obtain in the wild, limiting scalability. In this paper, we show that standard neural-network approaches, which perform poorly when trained on synthetic RGB images, can perform well when the data is pre-processed to extract cues about the person's motion, notably as optical flow and the motion of 2D keypoints. Therefore, our results suggest that motion can be a simple way to bridge a sim2real gap when video is available. We evaluate on the 3D Poses in the Wild dataset, the most challenging modern standard of 3D pose estimation, where we show full 3D mesh recovery that is on par with state-of-the-art methods trained on real 3D sequences, despite training only on synthetic humans from the SURREAL dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02499](http://arxiv.org/abs/1907.02499)

##### PDF
[http://arxiv.org/pdf/1907.02499](http://arxiv.org/pdf/1907.02499)

