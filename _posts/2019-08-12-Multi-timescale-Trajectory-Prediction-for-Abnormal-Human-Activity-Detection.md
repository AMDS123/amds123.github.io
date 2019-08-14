---
layout: post
title: "Multi-timescale Trajectory Prediction for Abnormal Human Activity Detection"
date: 2019-08-12 18:12:20
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Royston Rodrigues, Neha Bhargava, Rajbabu Velmurugan, Subhasis Chaudhuri
mathjax: true
---

* content
{:toc}

##### Abstract
A classical approach to abnormal activity detection is to learn a representation for normal activities from the training data and then use this learned representation to detect abnormal activities while testing. Typically, the methods based on this approach operate at a fixed timescale - either a single time-instant (eg. frame-based) or a constant time duration (eg. video-clip based). But human abnormal activities can take place at different timescales. For example, jumping is a short term anomaly and loitering is a long term anomaly in a surveillance scenario. A single and pre-defined timescale is not enough to capture the wide range of anomalies occurring with different time duration. In this paper, we propose a multi-timescale model to capture the temporal dynamics at different timescales. In particular, the proposed model makes future and past predictions at different timescales for a given input pose trajectory. The model is multi-layered where intermediate layers are responsible to generate predictions corresponding to different timescales. These predictions are combined to detect abnormal activities. In addition, we also introduce an abnormal activity data-set for research use that contains 4,83,566 annotated frames. Data-set will be made available at https://rodrigues-royston.github.io/Multi-timescale_Trajectory_Prediction/ Our experiments show that the proposed model can capture the anomalies of different time duration and outperforms existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04321](http://arxiv.org/abs/1908.04321)

##### PDF
[http://arxiv.org/pdf/1908.04321](http://arxiv.org/pdf/1908.04321)

