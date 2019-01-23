---
layout: post
title: "An Integrated Approach to Autonomous Environment Modeling"
date: 2019-01-22 15:38:38
categories: arXiv_RO
tags: arXiv_RO SLAM
author: Miroslav Kulich, Viktor Koz&#xe1;k, Libor P&#x159;eu&#x10d;il
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an integrated solution to memory-efficient environment modeling by an autonomous mobile robot equipped with a laser range-finder. 
 Majority of nowadays approaches to autonomous environment modeling, called exploration, employs occupancy grids as environment representation where the working space is divided into small cells each storing information about the corresponding piece of the environment in the form of a probabilistic estimate of its state. In contrast, the presented approach uses a polygonal representation of the explored environment which consumes much less memory, enables fast planning and decision-making algorithms and it is thus reliable for large-scale environments. 
 Simultaneous localization and mapping (SLAM) has been integrated into the presented framework to correct odometry errors and to provide accurate position estimates. This involves also a refinement of the already generated environment model in case of loop closure, i.e. when the robot detects that it revisited an already explored place. 
 The framework has been implemented in Robot Operating System (ROS) and tested with a real robot in various environments. The experiments show that the polygonal representation with SLAM integrated can be used in the real world as it is fast, memory efficient and accurate. Moreover, the refinement can be executed in real-time during the exploration process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07423](http://arxiv.org/abs/1901.07423)

##### PDF
[http://arxiv.org/pdf/1901.07423](http://arxiv.org/pdf/1901.07423)

