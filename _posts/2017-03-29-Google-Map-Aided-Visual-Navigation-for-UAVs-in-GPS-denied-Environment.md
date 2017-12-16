---
layout: post
title: "Google Map Aided Visual Navigation for UAVs in GPS-denied Environment"
date: 2017-03-29 16:34:25
categories: arXiv_CV
tags: arXiv_CV Tracking Relation
author: Mo Shan, Fei Wang, Feng Lin, Zhi Gao, Ya Z. Tang, Ben M. Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework for Google Map aided UAV navigation in GPS-denied environment. Geo-referenced navigation provides drift-free localization and does not require loop closures. The UAV position is initialized via correlation, which is simple and efficient. We then use optical flow to predict its position in subsequent frames. During pose tracking, we obtain inter-frame translation either by motion field or homography decomposition, and we use HOG features for registration on Google Map. We employ particle filter to conduct a coarse to fine search to localize the UAV. Offline test using aerial images collected by our quadrotor platform shows promising results as our approach eliminates the drift in dead-reckoning, and the small localization error indicates the superiority of our approach as a supplement to GPS.

##### Abstract (translated by Google)
我们提出了一个在GPS拒绝环境下Google Map辅助无人机导航的框架。地理参考导航提供了无漂移的本地化，不需要环路闭合。无人机的位置通过相关进行初始化，简单有效。然后，我们使用光流来预测其在后续帧中的位置。在姿态跟踪过程中，我们通过运动场或单应性分解来获得帧间转换，并且使用HOG特征在Google Map上进行注册。我们采用粒子滤波器进行粗略到精细的搜索来定位无人机。使用由我们的四旋翼平台收集的航拍图像的离线测试显示出有希望的结果，因为我们的方法消除了航位推算中的漂移，并且小的定位误差表明我们的方法作为GPS的补充的优势。

##### URL
[https://arxiv.org/abs/1703.10125](https://arxiv.org/abs/1703.10125)

##### PDF
[https://arxiv.org/pdf/1703.10125](https://arxiv.org/pdf/1703.10125)

