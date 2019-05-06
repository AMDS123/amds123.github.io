---
layout: post
title: "Neural Stethoscopes: Unifying Analytic, Auxiliary and Adversarial Network Probing"
date: 2019-05-02 19:31:50
categories: arXiv_AI
tags: arXiv_AI Adversarial Deep_Learning Prediction
author: Fabian B. Fuchs, Oliver Groth, Adam R. Kosiorek, Alex Bewley, Markus Wulfmeier, Andrea Vedaldi, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
Model interpretability and systematic, targeted model adaptation present central challenges in deep learning. In the domain of intuitive physics, we study the task of visually predicting stability of block towers with the goal of understanding and influencing the model's reasoning. Our contributions are two-fold. Firstly, we introduce neural stethoscopes as a framework for quantifying the degree of importance of specific factors of influence in deep networks as well as for actively promoting and suppressing information as appropriate. In doing so, we unify concepts from multitask learning as well as training with auxiliary and adversarial losses. Secondly, we deploy the stethoscope framework to provide an in-depth analysis of a state-of-the-art deep neural network for stability prediction, specifically examining its physical reasoning. We show that the baseline model is susceptible to being misled by incorrect visual cues. This leads to a performance breakdown to the level of random guessing when training on scenarios where visual cues are inversely correlated with stability. Using stethoscopes to promote meaningful feature extraction increases performance from 51% to 90% prediction accuracy. Conversely, training on an easy dataset where visual cues are positively correlated with stability, the baseline model learns a bias leading to poor performance on a harder dataset. Using an adversarial stethoscope, the network is successfully de-biased, leading to a performance increase from 66% to 88%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.05502](http://arxiv.org/abs/1806.05502)

##### PDF
[http://arxiv.org/pdf/1806.05502](http://arxiv.org/pdf/1806.05502)

