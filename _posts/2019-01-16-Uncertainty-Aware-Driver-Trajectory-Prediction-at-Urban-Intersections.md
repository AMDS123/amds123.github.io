---
layout: post
title: "Uncertainty-Aware Driver Trajectory Prediction at Urban Intersections"
date: 2019-01-16 01:46:57
categories: arXiv_AI
tags: arXiv_AI Prediction Detection
author: Xin Huang, Stephen McGill, Brian C. Williams, Luke Fletcher, Guy Rosman
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting the motion of a driver's vehicle is crucial for advanced driving systems, enabling detection of potential risks towards shared control between the driver and automation systems. In this paper, we propose a variational neural network approach that predicts future driver trajectory distributions for the vehicle based on multiple sensors. Our predictor generates both a conditional variational distribution of future trajectories, as well as a confidence estimate for different time horizons. Our approach allows us to handle inherently uncertain situations, and reason about information gain from each input, as well as combine our model with additional predictors, creating a mixture of experts. We show how to augment the variational predictor with a physics-based predictor, and based on their confidence estimators, improve overall system performance. The resulting combined model is aware of the uncertainty associated with its predictions, which can help the vehicle autonomy to make decisions with more confidence. The model is validated on real-world urban driving data collected in multiple locations. This validation demonstrates that our approach improves the prediction error of a physics-based model by 25% while successfully identifying the uncertain cases with 66% accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.05105](http://arxiv.org/abs/1901.05105)

##### PDF
[http://arxiv.org/pdf/1901.05105](http://arxiv.org/pdf/1901.05105)

