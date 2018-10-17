---
layout: post
title: "Robust Learning of Tactile Force Estimation through Robot Interaction"
date: 2018-10-15 05:31:24
categories: arXiv_RO
tags: arXiv_RO Face Inference
author: Balakumar Sundaralingam, Alexander (Sasha)Lambert, Ankur Handa, Byron Boots, Tucker Hermans, Stan Birchfield, Nathan Ratliff, Dieter Fox
mathjax: true
---

* content
{:toc}

##### Abstract
Current methods for estimating force from tactile sensor signals are either inaccurate analytic models or task-specific learned models. In this paper, we explore learning a robust model that maps tactile sensor signals to force. We specifically explore learning a mapping for the SynTouch BioTac sensor via neural networks. We propose a voxelized input feature layer for spatial signals and leverage information about the sensor surface to regularize the loss function. To learn a robust tactile force model that transfers across tasks, we generate ground truth data from three different sources: (1) the BioTac rigidly mounted to a force torque sensor, (2) a robot interacting with a ball rigidly attached to a force sensor to collect a wide range of force readings, and (3) through force inference on a planar pushing task by formalizing the mechanics as a system of particles and optimizing over the object motion. A total of 140k samples were collected from the three sources. To study generalization, we evaluate using the learned model to estimate force inside a feedback controller performing grasp stabilization and object placement. We achieve a median angular accuracy of 0.06 radians in predicting force direction~(66% improvement over the current state of the art) and a median magnitude accuracy of 0.06 N (93% improvement) on a test dataset. Our results can be found on this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.06187](https://arxiv.org/abs/1810.06187)

##### PDF
[https://arxiv.org/pdf/1810.06187](https://arxiv.org/pdf/1810.06187)

