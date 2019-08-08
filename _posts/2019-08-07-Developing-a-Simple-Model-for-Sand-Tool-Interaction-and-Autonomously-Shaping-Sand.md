---
layout: post
title: "Developing a Simple Model for Sand-Tool Interaction and Autonomously Shaping Sand"
date: 2019-08-07 17:54:09
categories: arXiv_RO
tags: arXiv_RO Face Reinforcement_Learning
author: Wooshik Kim, Catherine Pavlov, Aaron M. Johnson
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomy for robots interacting with sand will enable a wide range of beneficial behaviors, from earth moving for construction and farming vehicles to navigating rough terrain for Mars rovers. The goal of this work is to shape sand into desired forms. Unlike other common autonomous tasks of achieving desired state of a robot, achieving a desired shape of a continuously deformable environment like sand is a much more challenging task. The state of robot can be described with a couple of states-x, y, z, roll, pitch, yaw-but the desired shape of sand can not be described with just a few values. Sand is an aggregation of billions of small particles. After simplifying the model of sand and tool interaction by looking only at the surface of the heightmap, we can formulate the problems into something that is still high dimensional (hundreds to thousands of state dimensions) but much more solvable. We show how this problem can be formulated into a graph search problem and solve it with the A-star algorithm and report preliminary results on using deep reinforcement learning methods like Deep Q-Network and Deep Deterministic Policy Gradient.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02745](http://arxiv.org/abs/1908.02745)

##### PDF
[http://arxiv.org/pdf/1908.02745](http://arxiv.org/pdf/1908.02745)

