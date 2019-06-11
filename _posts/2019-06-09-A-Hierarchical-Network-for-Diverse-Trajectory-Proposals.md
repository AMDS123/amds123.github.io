---
layout: post
title: "A Hierarchical Network for Diverse Trajectory Proposals"
date: 2019-06-09 07:26:50
categories: arXiv_CV
tags: arXiv_CV Drone CNN
author: Sriram N. N., Gourav Kumar, Abhay Singh, M. Siva Karthik, Saket Saurav Brojeshwar Bhowmick, K. Madhava Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous explorative robots frequently encounter scenarios where multiple future trajectories can be pursued. Often these are cases with multiple paths around an obstacle or trajectory options towards various frontiers. Humans in such situations can inherently perceive and reason about the surrounding environment to identify several possibilities of either manoeuvring around the obstacles or moving towards various frontiers. In this work, we propose a 2 stage Convolutional Neural Network architecture which mimics such an ability to map the perceived surroundings to multiple trajectories that a robot can choose to traverse. The first stage is a Trajectory Proposal Network which suggests diverse regions in the environment which can be occupied in the future. The second stage is a Trajectory Sampling network which provides a finegrained trajectory over the regions proposed by Trajectory Proposal Network. We evaluate our framework in diverse and complicated real life settings. For the outdoor case, we use the KITTI dataset and our own outdoor driving dataset. In the indoor setting, we use an autonomous drone to navigate various scenarios and also a ground robot which can explore the environment using the trajectories proposed by our framework. Our experiments suggest that the framework is able to develop a semantic understanding of the obstacles, open regions and identify diverse trajectories that a robot can traverse. Our comparisons portray the performance gain of the proposed architecture over a diverse set of methods against which it is compared.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03584](http://arxiv.org/abs/1906.03584)

##### PDF
[http://arxiv.org/pdf/1906.03584](http://arxiv.org/pdf/1906.03584)

