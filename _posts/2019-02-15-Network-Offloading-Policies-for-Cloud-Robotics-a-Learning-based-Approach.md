---
layout: post
title: "Network Offloading Policies for Cloud Robotics: a Learning-based Approach"
date: 2019-02-15 06:34:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Drone Detection
author: Sandeep Chinchali, Apoorva Sharma, James Harrison, Amine Elhafsi, Daniel Kang, Evgenya Pergament, Eyal Cidon, Sachin Katti, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
Today's robotic systems are increasingly turning to computationally expensive models such as deep neural networks (DNNs) for tasks like localization, perception, planning, and object detection. However, resource-constrained robots, like low-power drones, often have insufficient on-board compute resources or power reserves to scalably run the most accurate, state-of-the art neural network compute models. Cloud robotics allows mobile robots the benefit of offloading compute to centralized servers if they are uncertain locally or want to run more accurate, compute-intensive models. However, cloud robotics comes with a key, often understated cost: communicating with the cloud over congested wireless networks may result in latency or loss of data. In fact, sending high data-rate video or LIDAR from multiple robots over congested networks can lead to prohibitive delay for real-time applications, which we measure experimentally. In this paper, we formulate a novel Robot Offloading Problem --- how and when should robots offload sensing tasks, especially if they are uncertain, to improve accuracy while minimizing the cost of cloud communication? We formulate offloading as a sequential decision making problem for robots, and propose a solution using deep reinforcement learning. In both simulations and hardware experiments using state-of-the art vision DNNs, our offloading strategy improves vision task performance by between 1.3-2.6x of benchmark offloading strategies, allowing robots the potential to significantly transcend their on-board sensing accuracy but with limited cost of cloud communication.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05703](http://arxiv.org/abs/1902.05703)

##### PDF
[http://arxiv.org/pdf/1902.05703](http://arxiv.org/pdf/1902.05703)

