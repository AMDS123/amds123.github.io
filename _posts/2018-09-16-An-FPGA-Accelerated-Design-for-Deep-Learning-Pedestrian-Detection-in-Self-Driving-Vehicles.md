---
layout: post
title: "An FPGA-Accelerated Design for Deep Learning Pedestrian Detection in Self-Driving Vehicles"
date: 2018-09-16 14:16:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Abdallah Moussawi, Kamal Haddad, Anthony Chahine
mathjax: true
---

* content
{:toc}

##### Abstract
With the rise of self-driving vehicles comes the risk of accidents and the need for higher safety, and protection for pedestrian detection in the following scenarios: imminent crashes, thus the car should crash into an object and avoid the pedestrian, and in the case of road intersections, where it is important for the car to stop when pedestrians are crossing. Currently, a special topology of deep neural networks called Fused Deep Neural Network (F-DNN) is considered to be the state of the art in pedestrian detection, as it has the lowest miss rate, yet it is very slow. Therefore, acceleration is needed to speed up the performance. This project proposes two contributions to address this problem, by using a deep neural network used for object detection, called Single Shot Multi-Box Detector (SSD). The first contribution is training and tuning the hyperparameters of SSD to improve pedestrian detection. The second contribution is a new FPGA design for accelerating the model on the Altera Arria 10 platform. The final system will be used in self-driving vehicles in real-time. Preliminary results of the improved SSD shows 3% higher miss-rate than F-DNN on Caltech pedestrian detection benchmark, but 4x performance improvement. The acceleration design is expected to achieve an additional performance improvement significantly outweighing the minimal difference in accuracy.

##### Abstract (translated by Google)
随着自动驾驶车辆的兴起，发生事故的风险和对更高安全性的需求，以及在以下情况下对行人检测的保护：即将发生的碰撞，因此汽车应撞到物体并避开行人，并且在这种情况下道路交叉口，当行人过马路时，停车很重要。目前，称为融合深度神经网络（F-DNN）的深度神经网络的特殊拓扑被认为是行人检测的最先进技术，因为它具有最低的未命中率，但是它非常慢。因此，需要加速以加速性能。该项目通过使用用于物体检测的深度神经网络（称为单次射击多盒检测器（SSD））提出了解决该问题的两个贡献。第一个贡献是培训和调整SSD的超参数以改善行人检测。第二个贡献是用于加速Altera Arria 10平台模型的新FPGA设计。最终系统将实时用于自动驾驶车辆。改进的SSD的初步结果显示，在加州理工学院行人检测基准测试中，失败率比F-DNN高3％，但性能提高了4倍。加速设计有望实现额外的性能提升，大大超过精度的最小差异。

##### URL
[http://arxiv.org/abs/1809.05879](http://arxiv.org/abs/1809.05879)

##### PDF
[http://arxiv.org/pdf/1809.05879](http://arxiv.org/pdf/1809.05879)

