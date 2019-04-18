---
layout: post
title: "Gaze Training by Modulated Dropout Improves Imitation Learning"
date: 2019-04-17 17:25:37
categories: arXiv_AI
tags: arXiv_AI CNN Prediction
author: Yuying Chen, Congcong Liu, Lei Tai, Ming Liu, Bertram E. Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Imitation learning by behavioral cloning is a prevalent method which has achieved some success in vision-based autonomous driving. The basic idea behind behavioral cloning is to have the neural network learn from observing a human expert's behavior. Typically, a convolutional neural network learns to predict the steering commands from raw driver-view images by mimicking the behaviors of human drivers. However, there are other cues, e.g. gaze behavior, available from human drivers that have yet to be exploited. Previous researches have shown that novice human learners can benefit from observing experts' gaze patterns. We present here that deep neural networks can also profit from this. We propose a method, gaze-modulated dropout, for integrating this gaze information into a deep driving network implicitly rather than as an additional input. Our experimental results demonstrate that gaze-modulated dropout enhances the generalization capability of the network to unseen scenes. Prediction error in steering commands is reduced by 23.5% compared to uniform dropout. Running closed loop in the simulator, the gaze-modulated dropout net increased the average distance travelled between infractions by 58.5%. Consistent with these results, we also found the gaze-modulated dropout net to have lower model uncertainty.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08377](http://arxiv.org/abs/1904.08377)

##### PDF
[http://arxiv.org/pdf/1904.08377](http://arxiv.org/pdf/1904.08377)

