---
layout: post
title: "VideoFlow: A Flow-Based Generative Model for Video"
date: 2019-03-04 18:55:45
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization Prediction
author: Manoj Kumar, Mohammad Babaeizadeh, Dumitru Erhan, Chelsea Finn, Sergey Levine, Laurent Dinh, Durk Kingma
mathjax: true
---

* content
{:toc}

##### Abstract
Generative models that can model and predict sequences of future events can, in principle, learn to capture complex real-world phenomena, such as physical interactions. In particular, learning predictive models of videos offers an especially appealing mechanism to enable a rich understanding of the physical world: videos of real-world interactions are plentiful and readily available, and a model that can predict future video frames can not only capture useful representations of the world, but can be useful in its own right, for problems such as model-based robotic control. However, a central challenge in video prediction is that the future is highly uncertain: a sequence of past observations of events can imply many possible futures. Although a number of recent works have studied probabilistic models that can represent uncertain futures, such models are either extremely expensive computationally (as in the case of pixel-level autoregressive models), or do not directly optimize the likelihood of the data. In this work, we propose a model for video prediction based on normalizing flows, which allows for direct optimization of the data likelihood, and produces high-quality stochastic predictions. To our knowledge, our work is the first to propose multi-frame video prediction with normalizing flows. We describe an approach for modeling the latent space dynamics, and demonstrate that flow-based generative models offer a viable and competitive approach to generative modeling of video.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01434](http://arxiv.org/abs/1903.01434)

##### PDF
[http://arxiv.org/pdf/1903.01434](http://arxiv.org/pdf/1903.01434)

