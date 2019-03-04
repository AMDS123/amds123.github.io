---
layout: post
title: "TZC: Efficient Inter-Process Communication for Robotics Middleware with Partial Serialization"
date: 2019-03-01 01:40:40
categories: arXiv_RO
tags: arXiv_RO
author: Yu-Ping Wang, Wende Tan, Xu-Qiang Hu, Dinesh Manocha, Shi-Min Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Inter-process communication (IPC) is one of the core functions of modern robotics middleware. We propose an efficient IPC technique called TZC (Towards Zero-Copy). As a core component of TZC, we design a novel algorithm called partial serialization. Our formulation can generate messages that can be divided into two parts. During message transmission, one part is transmitted through a socket and the other part uses shared memory. The part within shared memory is never copied or serialized during its lifetime. We have integrated TZC with ROS and ROS2 and find that TZC can be easily combined with current open-source platforms. By using TZC, the overhead of IPC remains constant when the message size grows. In particular, when the message size is 4MB (less than the size of a full HD image), TZC can reduce the overhead of ROS IPC from tens of milliseconds to hundreds of microseconds and can reduce the overhead of ROS2 IPC from hundreds of milliseconds to less than 1 millisecond. We also demonstrate the benefits of TZC by integrating with TurtleBot2 that are used in autonomous driving scenarios. We show that by using TZC, the braking distance can be shortened by 16% than ROS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00556](http://arxiv.org/abs/1810.00556)

##### PDF
[http://arxiv.org/pdf/1810.00556](http://arxiv.org/pdf/1810.00556)

