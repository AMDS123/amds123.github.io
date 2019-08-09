---
layout: post
title: "Learning Vision-based Flight in Drone Swarms by Imitation"
date: 2019-08-08 10:19:48
categories: arXiv_CV
tags: arXiv_CV Drone CNN
author: Fabian Schilling, Julien Lecoeur, Fabrizio Schiano, Dario Floreano
mathjax: true
---

* content
{:toc}

##### Abstract
Decentralized drone swarms deployed today either rely on sharing of positions among agents or detecting swarm members with the help of visual markers. This work proposes an entirely visual approach to coordinate markerless drone swarms based on imitation learning. Each agent is controlled by a small and efficient convolutional neural network that takes raw omnidirectional images as inputs and predicts 3D velocity commands that match those computed by a flocking algorithm. We start training in simulation and propose a simple yet effective unsupervised domain adaptation approach to transfer the learned controller to the real world. We further train the controller with data collected in our motion capture hall. We show that the convolutional neural network trained on the visual inputs of the drone can learn not only robust inter-agent collision avoidance but also cohesion of the swarm in a sample-efficient manner. The neural controller effectively learns to localize other agents in the visual input, which we show by visualizing the regions with the most influence on the motion of an agent. We remove the dependence on sharing positions among swarm members by taking only local visual information into account for control. Our work can therefore be seen as the first step towards a fully decentralized, vision-based swarm without the need for communication or visual markers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02999](http://arxiv.org/abs/1908.02999)

##### PDF
[http://arxiv.org/pdf/1908.02999](http://arxiv.org/pdf/1908.02999)

