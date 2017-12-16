---
layout: post
title: "RegNet: Multimodal Sensor Registration Using Deep Neural Networks"
date: 2017-07-11 08:21:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Nick Schneider, Florian Piewak, Christoph Stiller, Uwe Franke
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present RegNet, the first deep convolutional neural network (CNN) to infer a 6 degrees of freedom (DOF) extrinsic calibration between multimodal sensors, exemplified using a scanning LiDAR and a monocular camera. Compared to existing approaches, RegNet casts all three conventional calibration steps (feature extraction, feature matching and global regression) into a single real-time capable CNN. Our method does not require any human interaction and bridges the gap between classical offline and target-less online calibration approaches as it provides both a stable initial estimation as well as a continuous online correction of the extrinsic parameters. During training we randomly decalibrate our system in order to train RegNet to infer the correspondence between projected depth measurements and RGB image and finally regress the extrinsic calibration. Additionally, with an iterative execution of multiple CNNs, that are trained on different magnitudes of decalibration, our approach compares favorably to state-of-the-art methods in terms of a mean calibration error of 0.28 degrees for the rotational and 6 cm for the translation components even for large decalibrations up to 1.5 m and 20 degrees.

##### Abstract (translated by Google)
在本文中，我们提出RegNet，第一个深度卷积神经网络（CNN）来推断多模式传感器之间的6自由度（DOF）外部校准，例如使用扫描LiDAR和单目照相机。与现有方法相比，RegNet将所有三个传统的校准步骤（特征提取，特征匹配和全局回归）转换为单个实时有效的CNN。我们的方法不需要任何人为的交互作用，弥补了经典离线和无目标在线校准方法之间的差距，因为它提供了稳定的初始估计以及对外部参数的连续在线校正。在训练期间，我们随机地对我们的系统进行去校准，以便训练RegNet来推断投影的深度测量结果与RGB图像之间的对应关系，并最终回归外部校准。此外，通过迭代执行多个CNN（经过不同程度的去校准），我们的方法在平均校准误差为0.28度（旋转角度）和6厘米翻译组件，即使对于高达1.5米和20度的大幅度降级。

##### URL
[https://arxiv.org/abs/1707.03167](https://arxiv.org/abs/1707.03167)

##### PDF
[https://arxiv.org/pdf/1707.03167](https://arxiv.org/pdf/1707.03167)

