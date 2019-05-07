---
layout: post
title: "Autonomous Air Traffic Controller: A Deep Multi-Agent Reinforcement Learning Approach"
date: 2019-05-02 21:03:27
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Drone Optimization
author: Marc Brittain, Peng Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Air traffic control is a real-time safety-critical decision making process in highly dynamic and stochastic environments. In today's aviation practice, a human air traffic controller monitors and directs many aircraft flying through its designated airspace sector. With the fast growing air traffic complexity in traditional (commercial airliners) and low-altitude (drones and eVTOL aircraft) airspace, an autonomous air traffic control system is needed to accommodate high density air traffic and ensure safe separation between aircraft. We propose a deep multi-agent reinforcement learning framework that is able to identify and resolve conflicts between aircraft in a high-density, stochastic, and dynamic en-route sector with multiple intersections and merging points. The proposed framework utilizes an actor-critic model, A2C that incorporates the loss function from Proximal Policy Optimization (PPO) to help stabilize the learning process. In addition we use a centralized learning, decentralized execution scheme where one neural network is learned and shared by all agents in the environment. We show that our framework is both scalable and efficient for large number of incoming aircraft to achieve extremely high traffic throughput with safety guarantee. We evaluate our model via extensive simulations in the BlueSky environment. Results show that our framework is able to resolve 99.97% and 100% of all conflicts both at intersections and merging points, respectively, in extreme high-density air traffic scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01303](http://arxiv.org/abs/1905.01303)

##### PDF
[http://arxiv.org/pdf/1905.01303](http://arxiv.org/pdf/1905.01303)

