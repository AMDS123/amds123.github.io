---
layout: post
title: "Less Is More: Picking Informative Frames for Video Captioning"
date: 2018-03-05 01:57:49
categories: arXiv_CV
tags: arXiv_CV Salient Video_Caption Attention Caption
author: Yangyu Chen, Shuhui Wang, Weigang Zhang, Qingming Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In video captioning task, the best practice has been achieved by attention-based models which associate salient visual components with sentences in the video. However, existing study follows a common procedure which includes a frame-level appearance modeling and motion modeling on equal interval frame sampling, which may bring about redundant visual information, sensitivity to content noise and unnecessary computation cost. We propose a plug-and-play PickNet to perform informative frame picking in video captioning. Based on a standard Encoder-Decoder framework, we develop a reinforcement-learning-based procedure to train the network sequentially, where the reward of each frame picking action is designed by maximizing visual diversity and minimizing textual discrepancy. If the candidate is rewarded, it will be selected and the corresponding latent representation of Encoder-Decoder will be updated for future trials. This procedure goes on until the end of the video sequence. Consequently, a compact frame subset can be selected to represent the visual information and perform video captioning without performance degradation. Experiment results shows that our model can use 6-8 frames to achieve competitive performance across popular benchmarks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.01457](https://arxiv.org/abs/1803.01457)

##### PDF
[https://arxiv.org/pdf/1803.01457](https://arxiv.org/pdf/1803.01457)

