---
layout: post
title: "Reducing Drift in Visual Odometry by Inferring Sun Direction Using a Bayesian Convolutional Neural Network"
date: 2019-08-18 01:13:36
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Detection
author: Valentin Peretroukhin, Lee Clement, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to incorporate global orientation information from the sun into a visual odometry pipeline using only the existing image stream, where the sun is typically not visible. We leverage recent advances in Bayesian Convolutional Neural Networks to train and implement a sun detection model that infers a three-dimensional sun direction vector from a single RGB image. Crucially, our method also computes a principled uncertainty associated with each prediction, using a Monte Carlo dropout scheme. We incorporate this uncertainty into a sliding window stereo visual odometry pipeline where accurate uncertainty estimates are critical for optimal data fusion. Our Bayesian sun detection model achieves a median error of approximately 12 degrees on the KITTI odometry benchmark training set, and yields improvements of up to 42% in translational ARMSE and 32% in rotational ARMSE compared to standard VO. An open source implementation of our Bayesian CNN sun estimator (Sun-BCNN) using Caffe is available at https://github. com/utiasSTARS/sun-bcnn-vo

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1609.05993](http://arxiv.org/abs/1609.05993)

##### PDF
[http://arxiv.org/pdf/1609.05993](http://arxiv.org/pdf/1609.05993)

