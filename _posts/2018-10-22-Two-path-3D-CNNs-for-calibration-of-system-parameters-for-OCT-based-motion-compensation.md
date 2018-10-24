---
layout: post
title: "Two-path 3D CNNs for calibration of system parameters for OCT-based motion compensation"
date: 2018-10-22 22:14:38
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Deep_Learning Relation
author: Nils Gessert, Martin Gromniak, Matthias Schl&#xfc;ter, Alexander Schlaefer
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic motion compensation and adjustment of an intraoperative imaging modality's field of view is a common problem during interventions. Optical coherence tomography (OCT) is an imaging modality which is used in interventions due to its high spatial resolution of few micrometers and its temporal resolution of potentially several hundred volumes per second. However, performing motion compensation with OCT is problematic due to its small field of view which might lead to tracked objects being lost quickly. We propose a novel deep learning-based approach that directly learns input parameters of motors that move the scan area for motion compensation from optical coherence tomography volumes. We design a two-path 3D convolutional neural network (CNN) architecture that takes two volumes with an object to be tracked as its input and predicts the necessary motor input parameters to compensate the object's movement. In this way, we learn the calibration between object movement and system parameters for motion compensation with arbitrary objects. Thus, we avoid error-prone hand-eye calibration and handcrafted feature tracking from classical approaches. We achieve an average correlation coefficient of 0.998 between predicted and ground-truth motor parameters which leads to sub-voxel accuracy. Furthermore, we show that our deep learning model is real-time capable for use with the system's high volume acquisition frequency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09582](http://arxiv.org/abs/1810.09582)

##### PDF
[http://arxiv.org/pdf/1810.09582](http://arxiv.org/pdf/1810.09582)

