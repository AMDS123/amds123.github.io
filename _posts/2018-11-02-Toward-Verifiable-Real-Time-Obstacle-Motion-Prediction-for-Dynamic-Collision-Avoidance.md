---
layout: post
title: "Toward Verifiable Real-Time Obstacle Motion Prediction for Dynamic Collision Avoidance"
date: 2018-11-02 20:14:51
categories: arXiv_RO
tags: arXiv_RO RNN Prediction
author: Vincent Kurtz, Hai Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Next generation Unmanned Aerial Vehicles (UAVs) must reliably avoid moving obstacles. Existing dynamic collision avoidance methods are effective where obstacle trajectories are linear or known, but such restrictions are not accurate to many real-world UAV applications. We propose an efficient method of predicting an obstacle's motion based only on recent observations, via online training of an LSTM neural network. Given such predictions, we define a Nonlinear Probabilistic Velocity Obstacle (NPVO), which can be used select a velocity that is collision free with a given probability. We take a step towards formal verification of our approach, using statistical model checking to approximate the probability that our system will mispredict an obstacle's motion. Given such a probability, we prove upper bounds on the probability of collision in multi-agent and reciprocal collision avoidance scenarios. Furthermore, we demonstrate in simulation that our method avoids collisions where state-of-the-art methods fail.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01075](http://arxiv.org/abs/1811.01075)

##### PDF
[http://arxiv.org/pdf/1811.01075](http://arxiv.org/pdf/1811.01075)

