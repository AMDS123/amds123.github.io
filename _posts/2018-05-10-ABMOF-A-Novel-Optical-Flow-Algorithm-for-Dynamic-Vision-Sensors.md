---
layout: post
title: "ABMOF: A Novel Optical Flow Algorithm for Dynamic Vision Sensors"
date: 2018-05-10 14:07:31
categories: arXiv_CV
tags: arXiv_CV Sparse Drone
author: Min Liu, Tobi Delbruck
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic Vision Sensors (DVS), which output asynchronous log intensity change events, have potential applications in high-speed robotics, autonomous cars and drones. The precise event timing, sparse output, and wide dynamic range of the events are well suited for optical flow, but conventional optical flow (OF) algorithms are not well matched to the event stream data. This paper proposes an event-driven OF algorithm called adaptive block-matching optical flow (ABMOF). ABMOF uses time slices of accumulated DVS events. The time slices are adaptively rotated based on the input events and OF results. Compared with other methods such as gradient-based OF, ABMOF can efficiently be implemented in compact logic circuits. Results show that ABMOF achieves comparable accuracy to conventional standards such as Lucas-Kanade (LK). The main contributions of our paper are new adaptive time-slice rotation methods that ensure the generated slices have sufficient features for matching,including a feedback mechanism that controls the generated slices to have average slice displacement within the block search range. An LK method using our adapted slices is also implemented. The ABMOF accuracy is compared with this LK method on natural scene data including sparse and dense texture, high dynamic range, and fast motion exceeding 30,000 pixels per second.The paper dataset and source code are available from <a href="http://sensors.ini.uzh.ch/databases.html.">this http URL</a>

##### Abstract (translated by Google)
输出异步对数强度变化事件的动态视觉传感器（DVS）在高速机器人，自动驾驶汽车和无人机中具有潜在应用。事件的精确事件定时，稀疏输出和宽动态范围非常适合光流，但传统的光流（OF）算法与事件流数据不匹配。本文提出了一种事件驱动的OF算法，称为自适应块匹配光流（ABMOF）。 ABMOF使用累积DVS事件的时间片。时间片根据输入事件和OF结果自适应旋转。与诸如基于梯度的OF等其他方法相比，ABMOF可以在紧凑的逻辑电路中有效地实现。结果表明，ABMOF达到了与传统标准（如Lucas-Kanade（LK））相当的准确度。我们的论文的主要贡献是新的自适应时间切片旋转方法，确保生成的切片具有足够的匹配特征，包括控制生成的切片在块搜索范围内具有平均切片位移的反馈机制。使用我们改进的切片的LK方法也被实现。将ABMOF精度与这种LK方法在自然场景数据上进行比较，包括稀疏和密集纹理，高动态范围和每秒超过30,000像素的快速运动。纸质数据集和源代码可从<a href =“http：// sensors.ini.uzh.ch/databases.html.">这个http URL </a>

##### URL
[http://arxiv.org/abs/1805.03988](http://arxiv.org/abs/1805.03988)

##### PDF
[http://arxiv.org/pdf/1805.03988](http://arxiv.org/pdf/1805.03988)

