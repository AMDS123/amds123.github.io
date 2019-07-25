---
layout: post
title: "A neural network based post-filter for speech-driven head motion synthesis"
date: 2019-07-24 17:38:37
categories: arXiv_AI
tags: arXiv_AI
author: JinHong Lu, Hiroshi Shimodaira
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the fact that neural networks are widely used for speech-driven head motion synthesis, it is well-known that the output of neural networks is noisy or discontinuous due to the limited capability of deep neural networks in predicting human motion. Thus, post-processing is required to obtain smooth head motion trajectories for animation. It is common to apply a linear filter or consider keyframes as post-processing. However, neither approach is optimal as there is always a trade-off between smoothness and accuracy. We propose to employ a neural network trained in a way that it is capable of reconstructing the head motions, in order to overcome this limitation. In the objective evaluation, this filter is proved to be good at de-noising data involving types of noise (dropout or Gaussian noise). Objective metrics also demonstrate the improvement of the joined head motion's smoothness after being processed by our proposed filter. A detailed analysis reveals that our proposed filter learns the characteristic of head motions. The subjective evaluation shows that participants were unable to distinguish the synthesised head motions with our proposed filter from ground truth, which was preferred over the Gaussian filter and moving average.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10585](http://arxiv.org/abs/1907.10585)

##### PDF
[http://arxiv.org/pdf/1907.10585](http://arxiv.org/pdf/1907.10585)

