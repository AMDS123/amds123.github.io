---
layout: post
title: "Joint Mapping and Calibration via Differentiable Sensor Fusion"
date: 2018-11-21 06:22:06
categories: arXiv_AI
tags: arXiv_AI Object_Detection Knowledge Optimization Inference Classification Detection
author: Jonathan P. Chen, Fritz Obermeyer, Vladimir Lyapunov, Lionel Gueguen, Noah D. Goodman
mathjax: true
---

* content
{:toc}

##### Abstract
We leverage automatic differentiation (AD) and probabilistic programming languages to develop an end-to-end optimization algorithm for batch triangulation of a large number of unknown objects. Given noisy detections extracted from noisily geo-located street level imagery without depth information, we jointly estimate the number and location of objects of different types, together with parameters for sensor noise characteristics and prior distribution of objects conditioned on side information. The entire algorithm is framed as nested stochastic variational inference. An inner loop solves a soft data association problem via loopy belief propagation; a middle loop performs soft EM clustering using a regularized Newton solver (leveraging an AD framework); an outer loop backpropagates through the inner loops to train global parameters. We place priors over sensor parameters for different traffic object types, and demonstrate improvements with richer priors incorporating knowledge of the environment. 
 We test our algorithm on detections of road signs observed by cars with mounted cameras, though in practice this technique can be used for any geo-tagged images. We assume images do not have depth information (e.g. from lidar or stereo cameras). The detections were extracted by neural image detectors and classifiers, and we independently triangulate each type of sign (e.g. stop, traffic light). We find that our model is more robust to DNN misclassifications than current methods, generalizes across sign types, and can use geometric information to increase precision (e.g. Stop signs seldom occur on highways). Our algorithm outperforms our current production baseline based on k-means clustering. We show that variational inference training allows generalization by learning sign-specific parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00880](http://arxiv.org/abs/1812.00880)

##### PDF
[http://arxiv.org/pdf/1812.00880](http://arxiv.org/pdf/1812.00880)

