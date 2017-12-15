---
layout: post
title: "Learning to Track at 100 FPS with Deep Regression Networks"
date: 2016-08-16 02:34:48
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Relation
author: David Held, Sebastian Thrun, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning techniques are often used in computer vision due to their ability to leverage large amounts of training data to improve performance. Unfortunately, most generic object trackers are still trained from scratch online and do not benefit from the large number of videos that are readily available for offline training. We propose a method for offline training of neural networks that can track novel objects at test-time at 100 fps. Our tracker is significantly faster than previous methods that use neural networks for tracking, which are typically very slow to run and not practical for real-time applications. Our tracker uses a simple feed-forward network with no online training required. The tracker learns a generic relationship between object motion and appearance and can be used to track novel objects that do not appear in the training set. We test our network on a standard tracking benchmark to demonstrate our tracker's state-of-the-art performance. Further, our performance improves as we add more videos to our offline training set. To the best of our knowledge, our tracker is the first neural-network tracker that learns to track generic objects at 100 fps.

##### Abstract (translated by Google)
机器学习技术通常用于计算机视觉，因为它们能够利用大量的训练数据来提高性能。不幸的是，大多数通用的对象跟踪器仍然是从头开始在线训练，不能从大量可用于离线训练的视频中受益。我们提出了一种离线训练神经网络的方法，可以在100 fps的测试时间跟踪新的对象。我们的跟踪器比以前使用神经网络进行跟踪的方法快得多，通常运行速度非常慢并且不适用于实时应用。我们的跟踪器使用简单的前馈网络，不需要在线培训。跟踪器学习对象运动和外观之间的一般关系，可用于跟踪未出现在训练集中的新对象。我们在标准的跟踪基准上测试我们的网络，以展示我们的跟踪器的最新性能。此外，随着我​​们向离线训练集添加更多视频，我们的表现也会提高。据我们所知，我们的跟踪器是第一个学习跟踪100 fps通用对象的神经网络跟踪器。

##### URL
[https://arxiv.org/abs/1604.01802](https://arxiv.org/abs/1604.01802)

##### PDF
[https://arxiv.org/pdf/1604.01802](https://arxiv.org/pdf/1604.01802)

