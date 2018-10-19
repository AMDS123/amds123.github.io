---
layout: post
title: "Probably Unknown: Deep Inverse Sensor Modelling In Radar"
date: 2018-10-18 16:42:27
categories: arXiv_RO
tags: arXiv_RO Segmentation
author: Rob Weston, Sarah Cen, Paul Newman, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
Radar presents a promising alternative to lidar and vision in autonomous vehicle applications, being able to detect objects at long range under a variety of weather conditions. However, distinguishing between occupied and free space from a raw radar scan is notoriously difficult. We consider the challenge of learning an Inverse Sensor Model (ISM) mapping a raw radar observation to occupancy probabilities in a discretised space. We frame this problem as a segmentation task, utilising a deep neural network that is able to learn an inherently probabilistic ISM from raw sensor data considers scene context. In doing so our approach explicitly accounts for the heteroscedastic aleatoric uncertainty for radar that arises due to complex interactions between occlusion and sensor noise. Our network is trained using only partial occupancy labels generated from lidar and able to successfully distinguish between occupied and free space. We evaluate our approach on five hours of data recorded in a dynamic urban environment and show that it significantly outperforms classical constant false-alarm rate (CFAR) filtering approaches in light of challenging noise artefacts whilst identifying space that is inherently uncertain because of occlusion.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08151](http://arxiv.org/abs/1810.08151)

##### PDF
[http://arxiv.org/pdf/1810.08151](http://arxiv.org/pdf/1810.08151)

