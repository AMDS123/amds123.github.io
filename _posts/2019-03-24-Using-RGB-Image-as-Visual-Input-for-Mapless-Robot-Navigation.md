---
layout: post
title: "Using RGB Image as Visual Input for Mapless Robot Navigation"
date: 2019-03-24 05:44:20
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Liulong Ma, Jiao Chen, Yanjie Liu *
mathjax: true
---

* content
{:toc}

##### Abstract
Robot navigation in mapless environment is one of the essential problems and challenges in mobile robots. Deep reinforcement learning is a promising direction to tackle the task of mapless navigation. Since reinforcement learning requires a lot of exploration, it is usually necessary to train the agent in the simulator and then migrate to the real environment.The big reality gap makes RGB image, the most common visual sensor, rarely used. In this paper we present a learning-based mapless motion planner by taking RGB images as visual inputs. Many parameters in end-to-end navigation network taking RGB images as visual input are used to extract visual features. Therefore, we decouple visual features extracted module from the reinforcement learning network to reduce the need of interactions between agent and environment. We use Variational Autoencoder (VAE) to encode the image, and input the obtained latent vector as low-dimensional visual features into the network together with the target and motion information, so that the sampling efficiency of the agent is greatly improved. We built simulation environment as robot navigation environment for algorithm comparison. In the test environment, the proposed method was compared with the end-to-end network, which proved its effectiveness and efficiency. What's more, the proposed motion planner helps to find the optimal path. Finally, experiments were carried out in our built environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09927](http://arxiv.org/abs/1903.09927)

##### PDF
[http://arxiv.org/pdf/1903.09927](http://arxiv.org/pdf/1903.09927)

