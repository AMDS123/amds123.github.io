---
layout: post
title: "Finding Appropriate Traffic Regulations via Graph Convolutional Networks"
date: 2018-10-23 08:19:33
categories: arXiv_AI
tags: arXiv_AI CNN
author: Tomoharu Iwata, Takuma Otsuka, Hitoshi Shimizu, Hiroshi Sawada, Futoshi Naya, Naonori Ueda
mathjax: true
---

* content
{:toc}

##### Abstract
Appropriate traffic regulations, e.g. planned road closure, are important in congested events. Crowd simulators have been used to find appropriate regulations by simulating multiple scenarios with different regulations. However, this approach requires multiple simulation runs, which are time-consuming. In this paper, we propose a method to learn a function that outputs regulation effects given the current traffic situation as inputs. If the function is learned using the training data of many simulation runs in advance, we can obtain an appropriate regulation efficiently by bypassing simulations for the current situation. We use the graph convolutional networks for modeling the function, which enable us to find regulations even for unseen areas. With the proposed method, we construct a graph for each area, where a node represents a road, and an edge represents the road connection. By running crowd simulations with various regulations on various areas, we generate traffic situations and regulation effects. The graph convolutional networks are trained to output the regulation effects given the graph with the traffic situation information as inputs. With experiments using real-world road networks and a crowd simulator, we demonstrate that the proposed method can find a road to close that reduces the average time needed to reach the destination.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09712](http://arxiv.org/abs/1810.09712)

##### PDF
[http://arxiv.org/pdf/1810.09712](http://arxiv.org/pdf/1810.09712)

