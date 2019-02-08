---
layout: post
title: "Augmenting Learning Components for Safety in Resource Constrained Autonomous Robots"
date: 2019-02-06 23:39:22
categories: arXiv_AI
tags: arXiv_AI
author: Shreyas Ramakrishna, Abhishek Dubey, Matthew P Burruss, Charles Hartsell, Nagabhushan Mahadevan, Saideep Nannapaneni, Aron Laszka, Gabor Karsai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with resource constrained autonomous robots commonly found in factories, hospitals, and education laboratories, which popularly use learning enabled components (LEC) to make control actions. However, these LECs do not provide any safety guarantees, and testing them is challenging. To overcome these challenges, we introduce a framework that performs confidence estimation, resource management, and supervised safety control of autonomous systems with LECs. Using this framework, we make the following contributions: (1) allow for seamless integration of safety controllers and different simplex strategies to aid the LEC, (2) introduce RL-Simplex and illustrate the use of Q-learning to learn the optimal weights for the arbitration logic of the Simplex Architecture, (3) design a system level monitor that uses the current state information and a discrete Bayesian network model learned from past data to estimate a metric, which indicates if the car will remain in the safe region, and (4) a Resource Manager which performs dynamic task offloading depending on the resource temperature and CPU utilization while continually adjusting vehicle speed to compensate for the latency overhead. We compare the speed, steering and safety performance of the different controllers and simplex strategies, and we find RL-Simplex to have 60\% fewer safety violations and higher optimized speed during indoor driving ($\sim\,0.40\,m/s$) than the original system (using only LEC).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02432](http://arxiv.org/abs/1902.02432)

##### PDF
[http://arxiv.org/pdf/1902.02432](http://arxiv.org/pdf/1902.02432)

