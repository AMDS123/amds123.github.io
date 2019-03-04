---
layout: post
title: "Speeding up Deep Learning with Transient Servers"
date: 2019-02-28 19:47:59
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Shijian Li, Robert J. Walls, Lijie Xu, Tian Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Distributed training frameworks, like TensorFlow, have been proposed as a means to reduce the training time of deep learning models by using a cluster of GPU servers. While such speedups are often desirable---e.g., for rapidly evaluating new model designs---they often come with significantly higher monetary costs due to sublinear scalability. In this paper, we investigate the feasibility of using training clusters composed of cheaper transient GPU servers to get the benefits of distributed training without the high costs. 
 We conduct the first large-scale empirical analysis, launching more than a thousand GPU servers of various capacities, aimed at understanding the characteristics of transient GPU servers and their impact on distributed training performance. Our study demonstrates the potential of transient servers with a speedup of 7.7X with more than 62.9% monetary savings for some cluster configurations. We also identify a number of important challenges and opportunities for redesigning distributed training frameworks to be transient-aware. For example, the dynamic cost and availability characteristics of transient servers suggest the need for frameworks to dynamically change cluster configurations to best take advantage of current conditions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00045](http://arxiv.org/abs/1903.00045)

##### PDF
[http://arxiv.org/pdf/1903.00045](http://arxiv.org/pdf/1903.00045)

