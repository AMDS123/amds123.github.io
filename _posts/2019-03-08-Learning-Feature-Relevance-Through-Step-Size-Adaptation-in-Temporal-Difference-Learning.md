---
layout: post
title: "Learning Feature Relevance Through Step Size Adaptation in Temporal-Difference Learning"
date: 2019-03-08 02:29:22
categories: arXiv_AI
tags: arXiv_AI Represenation_Learning Prediction Gradient_Descent
author: Alex Kearney, Vivek Veeriah, Jaden Travnik, Patrick M. Pilarski, Richard S. Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
There is a long history of using meta learning as representation learning, specifically for determining the relevance of inputs. In this paper, we examine an instance of meta-learning in which feature relevance is learned by adapting step size parameters of stochastic gradient descent---building on a variety of prior work in stochastic approximation, machine learning, and artificial neural networks. In particular, we focus on stochastic meta-descent introduced in the Incremental Delta-Bar-Delta (IDBD) algorithm for setting individual step sizes for each feature of a linear function approximator. Using IDBD, a feature with large or small step sizes will have a large or small impact on generalization from training examples. As a main contribution of this work, we extend IDBD to temporal-difference (TD) learning---a form of learning which is effective in sequential, non i.i.d. problems. We derive a variety of IDBD generalizations for TD learning, demonstrating that they are able to distinguish which features are relevant and which are not. We demonstrate that TD IDBD is effective at learning feature relevance in both an idealized gridworld and a real-world robotic prediction task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03252](http://arxiv.org/abs/1903.03252)

##### PDF
[http://arxiv.org/pdf/1903.03252](http://arxiv.org/pdf/1903.03252)

