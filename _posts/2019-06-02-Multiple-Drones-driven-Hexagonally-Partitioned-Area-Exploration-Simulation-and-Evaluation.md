---
layout: post
title: "Multiple Drones driven Hexagonally Partitioned Area Exploration: Simulation and Evaluation"
date: 2019-06-02 13:30:18
categories: arXiv_RO
tags: arXiv_RO Drone RNN
author: Ayush Datta, Rahul Tallamraju, Kamalakar Karlapalem
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we simulated a distributed, cooperative path planning technique for multiple drones ($\sim$200) to explore an unknown region ($\sim$10,000 connected units) in the presence of obstacles. The map of an unknown region is dynamically created based on the information obtained from sensors and other drones. The unknown area is considered as connected region made up of hexagonal unit cells. These cells are grouped to form larger cells called sub-areas. We use two types of communication, one long range and another more frequently used short range communication. The short range communication within drones in smaller proximity helps avoid obstacles and re-exploration of cells already explored by companion drones located in same subarea. The long range communication helps drones identify next sub area to be targeted by individual drones based on weighted RNN (Reverse nearest neighbour).\par Simulation results show that using weighted RNN with two types of communication in a hexagonal representation of subareas makes exploration more efficient, scalable and resilient to communication failures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00401](http://arxiv.org/abs/1906.00401)

##### PDF
[http://arxiv.org/pdf/1906.00401](http://arxiv.org/pdf/1906.00401)

