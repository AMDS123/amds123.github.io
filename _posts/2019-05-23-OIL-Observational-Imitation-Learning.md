---
layout: post
title: "OIL: Observational Imitation Learning"
date: 2019-05-23 11:24:12
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Guohao Li, Matthias M&#xfc;ller, Vincent Casser, Neil Smith, Dominik L. Michels, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has explored the problem of autonomous navigation by imitating a teacher and learning an end-to-end policy, which directly predicts controls from raw images. However, these approaches tend to be sensitive to mistakes by the teacher and do not scale well to other environments or vehicles. To this end, we propose Observational Imitation Learning (OIL), a novel imitation learning variant that supports online training and automatic selection of optimal behavior by observing multiple imperfect teachers. We apply our proposed methodology to the challenging problems of autonomous driving and UAV racing. For both tasks, we utilize the Sim4CV simulator that enables the generation of large amounts of synthetic training data and also allows for online learning and evaluation. We train a perception network to predict waypoints from raw image data and use OIL to train another network to predict controls from these waypoints. Extensive experiments demonstrate that our trained network outperforms its teachers, conventional imitation learning (IL) and reinforcement learning (RL) baselines and even humans in simulation. The project website is available at https://sites.google.com/kaust.edu.sa/oil/ and a video at https://youtu.be/_rhq8a0qgeg

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.01129](http://arxiv.org/abs/1803.01129)

##### PDF
[http://arxiv.org/pdf/1803.01129](http://arxiv.org/pdf/1803.01129)

