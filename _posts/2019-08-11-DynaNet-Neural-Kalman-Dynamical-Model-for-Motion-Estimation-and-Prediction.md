---
layout: post
title: "DynaNet: Neural Kalman Dynamical Model for Motion Estimation and Prediction"
date: 2019-08-11 15:03:24
categories: arXiv_RO
tags: arXiv_RO Knowledge RNN Deep_Learning Prediction
author: Changhao Chen, Chris Xiaoxuan Lu, Bing Wang, Niki Trigoni, Andrew Markham
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamical models estimate and predict the temporal evolution of physical systems. State Space Models (SSMs) in particular represent the system dynamics with many desirable properties, such as being able to model uncertainty in both the model and measurements, and optimal (in the Bayesian sense) recursive formulations e.g. the Kalman Filter. However, they require significant domain knowledge to derive the parametric form and considerable hand-tuning to correctly set all the parameters. Data driven techniques e.g. Recurrent Neural Networks have emerged as compelling alternatives to SSMs with wide success across a number of challenging tasks, in part due to their ability to extract relevant features from rich inputs. They however lack interpretability and robustness to unseen conditions. In this work, we present DynaNet, a hybrid deep learning and time-varying state-space model which can be trained end-to-end. Our neural Kalman dynamical model allows us to exploit the relative merits of each approach. We demonstrate state-of-the-art estimation and prediction on a number of physically challenging tasks, including visual odometry, sensor fusion for visual-inertial navigation and pendulum control. In addition we show how DynaNet can indicate failures through investigation of properties such as the rate of innovation (Kalman Gain).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.03918](http://arxiv.org/abs/1908.03918)

##### PDF
[http://arxiv.org/pdf/1908.03918](http://arxiv.org/pdf/1908.03918)

