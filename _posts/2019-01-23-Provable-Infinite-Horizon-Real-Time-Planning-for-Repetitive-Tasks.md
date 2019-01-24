---
layout: post
title: "Provable Infinite-Horizon Real-Time Planning for Repetitive Tasks"
date: 2019-01-23 02:36:07
categories: arXiv_RO
tags: arXiv_RO
author: Fahad Islam, Oren Salzman, Maxim Likhachev
mathjax: true
---

* content
{:toc}

##### Abstract
In manufacturing and automation settings, robots often have to perform highly-repetitive manipulation tasks in structured environments. In this work we are interested in settings where tasks are similar, yet not identical (e.g., due to uncertain orientation of objects) and motion planning needs to be extremely fast. Preprocessing-based approaches prove to be very beneficial in these settings; they analyze the configuration-space offline to generate some auxiliary information which can then be used in the query phase to speedup planning times. Typically, the tighter the requirement is on query times the larger the memory footprint will be. In particular, for high-dimensional spaces, providing real-time planning capabilities is extremely challenging. While there are planners that guarantee real-time performance by limiting the planning horizon, we are not aware of general-purpose planners capable of doing it for infinite horizon (i.e., planning to the goal). To this end, we propose a preprocessing-based method that provides provable bounds on the query time while incurring only a small amount of memory overhead in the query phase. We evaluate our method on a 7-DOF robot arm and show a speedup of over tenfold in query time when compared to the PRM algorithm, while provably guaranteeing a maximum query time of less than 3 milliseconds.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07698](http://arxiv.org/abs/1901.07698)

##### PDF
[http://arxiv.org/pdf/1901.07698](http://arxiv.org/pdf/1901.07698)

