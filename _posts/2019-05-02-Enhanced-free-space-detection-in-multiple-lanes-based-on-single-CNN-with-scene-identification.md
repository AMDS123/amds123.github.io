---
layout: post
title: "Enhanced free space detection in multiple lanes based on single CNN with scene identification"
date: 2019-05-02 19:26:07
categories: arXiv_CV
tags: arXiv_CV Detection
author: Fabio Pizzati, Fernando Garc&#xed;a
mathjax: true
---

* content
{:toc}

##### Abstract
Many systems for autonomous vehicles' navigation rely on lane detection. Traditional algorithms usually estimate only the position of the lanes on the road, but an autonomous control system may also need to know if a lane marking can be crossed or not, and what portion of space inside the lane is free from obstacles, to make safer control decisions. On the other hand, free space detection algorithms only detect navigable areas, without information about lanes. State-of-the-art algorithms use CNNs for both tasks, with significant consumption of computing resources. We propose a novel approach that estimates the free space inside each lane, with a single CNN. Additionally, adding only a small requirement concerning GPU RAM, we infer the road type, that will be useful for path planning. To achieve this result, we train a multi-task CNN. Then, we further elaborate the output of the network, to extract polygons that can be effectively used in navigation control. Finally, we provide a computationally efficient implementation, based on ROS, that can be executed in real time. Our code and trained models are available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00941](http://arxiv.org/abs/1905.00941)

##### PDF
[http://arxiv.org/pdf/1905.00941](http://arxiv.org/pdf/1905.00941)

