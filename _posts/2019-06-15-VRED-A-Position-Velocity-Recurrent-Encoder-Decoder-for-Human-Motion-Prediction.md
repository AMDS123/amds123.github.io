---
layout: post
title: "VRED: A Position-Velocity Recurrent Encoder-Decoder for Human Motion Prediction"
date: 2019-06-15 09:59:30
categories: arXiv_CV
tags: arXiv_CV Embedding RNN Prediction Relation
author: Hongsong Wang, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Human motion prediction, which aims to predict future human poses given past poses, has recently seen increased interest. Many recent approaches are based on Recurrent Neural Networks (RNN) which model human poses with exponential maps. These approaches neglect the pose velocity as well as temporal relation of different poses, and tend to converge to the mean pose or fail to generate natural-looking poses. We therefore propose a novel Position-Velocity Recurrent Encoder-Decoder (PVRED) for human motion prediction, which makes full use of pose velocities and temporal positional information. A temporal position embedding method is presented and a Position-Velocity RNN (PVRNN) is proposed. We also emphasize the benefits of quaternion parameterization of poses and design a novel trainable Quaternion Transformation (QT) layer, which is combined with a robust loss function during training. Experiments on two human motion prediction benchmarks show that our approach considerably outperforms the state-of-the-art methods for both short-term prediction and long-term prediction. In particular, our proposed approach can predict future human-like and meaningful poses in 4000 milliseconds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06514](http://arxiv.org/abs/1906.06514)

##### PDF
[http://arxiv.org/pdf/1906.06514](http://arxiv.org/pdf/1906.06514)

