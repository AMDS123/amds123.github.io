---
layout: post
title: "Validation loss for landmark detection"
date: 2019-01-29 07:19:44
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection Relation
author: Wolfgang Fuhl, Thomas K&#xfc;bler, Rene Alexander Lotz, Gjergji Kasneci, Wolfgang Rosenstiel, Enkelejda Kasneci
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new loss function for the validation of image landmarks detected via Convolutional Neural Networks (CNNs). The network learns to estimate how accurate its landmark estimation is. This loss function is applicable to all regression-based location estimations and allows exclusion of unreliable landmarks from further processing. In addition, we formulate a novel batch balancing approach which weights the importance of samples based on their produced loss. This is done by computing a probability distribution mapping on an interval from which samples can be selected using a uniform random selection scheme. 
 We conducted several experiments on the 300W facial landmark data. In the first experiment, the influence of our batch balancing approach is evaluated by comparing it against uniform sampling. Afterwards, we compare two networks with the state of the art and demonstrate the usage and practical importance of our landmark validation signal. The effectiveness of our validation signal is further confirmed by a correlation analysis over all landmarks. Finally, we show a study on head pose estimation of truck drivers on German highways and compare our network to a commercial multi-camera system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10143](http://arxiv.org/abs/1901.10143)

##### PDF
[http://arxiv.org/pdf/1901.10143](http://arxiv.org/pdf/1901.10143)

