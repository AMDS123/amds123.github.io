---
layout: post
title: "SAAGs: Biased Stochastic Variance Reduction Methods for Large-scale Learning"
date: 2018-12-24 10:04:22
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Vinod Kumar Chauhan, Anuj Sharma, Kalpana Dahiya
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic approximation is one of the effective approach to deal with the large-scale machine learning problems and the recent research has focused on reduction of variance, caused by the noisy approximations of the gradients. In this paper, we have proposed novel variants of SAAG-I and II (Stochastic Average Adjusted Gradient) Chauhan et el. (2017), called SAAG-III and IV, respectively. Unlike SAAG-I, starting point is set to average of previous epoch in SAAG-III, and unlike SAAG-II, the snap point and starting point are set to average and last iterate of previous epoch in SAAG-IV, respectively. To determine the step size, we use Stochastic Backtracking-Armijo line Search (SBAS) which performs line search only on selected mini-batch of data points. Since backtracking line search is not suitable for large-scale problems and the constants used to find the step size, like Lipschitz constant, are not always available so SBAS could be very effective in such cases. We extend SAAGs (I, II, III, IV), to solve non-smooth problems and design two update rules for smooth and non-smooth problems. Moreover, our theoretical results prove linear convergence of SAAG-IV for all the four combinations of smoothness and strong-convexity, in expectation. Finally, our experimental studies prove the efficacy of proposed methods against the state-of-art techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08934](http://arxiv.org/abs/1807.08934)

##### PDF
[http://arxiv.org/pdf/1807.08934](http://arxiv.org/pdf/1807.08934)

