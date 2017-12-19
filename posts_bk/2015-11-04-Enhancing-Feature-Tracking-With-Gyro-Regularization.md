---
layout: post
title: "Enhancing Feature Tracking With Gyro Regularization"
date: 2015-11-04 21:04:07
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking
author: Bryan Poling, Gilad Lerman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deeply integrated method of exploiting low-cost gyroscopes to improve general purpose feature tracking. Most previous methods use gyroscopes to initialize and bound the search for features. In contrast, we use them to regularize the tracking energy function so that they can directly assist in the tracking of ambiguous and poor-quality features. We demonstrate that our simple technique offers significant improvements in performance over conventional template-based tracking methods, and is in fact competitive with more complex and computationally expensive state-of-the-art trackers, but at a fraction of the computational cost. Additionally, we show that the practice of initializing template-based feature trackers like KLT (Kanade-Lucas-Tomasi) using gyro-predicted optical flow offers no advantage over using a careful optical-only initialization method, suggesting that some deeper level of integration, like the method we propose, is needed in order to realize a genuine improvement in tracking performance from these inertial sensors.

##### Abstract (translated by Google)
我们提出了一个开发低成本陀螺仪以改善通用特性跟踪的深度集成方法。大多数以前的方法使用陀螺仪来初始化和限制对特征的搜索。相反，我们使用它们来调整跟踪能量函数，以便它们可以直接帮助跟踪模糊和质​​量差的特征。我们证明，与传统的基于模板的跟踪方法相比，我们的简单技术提供了显着的性能改进，实际上它与更复杂，计算成本更高的最先进的跟踪器相竞争，但计算成本只是其中的一小部分。此外，我们表明，使用陀螺仪预测的光流初始化基于模板的特征跟踪器如KLT（Kanade-Lucas-Tomasi）的做法与使用仔细的仅光学初始化方法相比没有优势，这表明一些更深层次的集成，就像我们提出的方法一样，为了从这些惯性传感器中实现跟踪性能的真正改善，也是需要的。

##### URL
[https://arxiv.org/abs/1511.01508](https://arxiv.org/abs/1511.01508)

##### PDF
[https://arxiv.org/pdf/1511.01508](https://arxiv.org/pdf/1511.01508)

