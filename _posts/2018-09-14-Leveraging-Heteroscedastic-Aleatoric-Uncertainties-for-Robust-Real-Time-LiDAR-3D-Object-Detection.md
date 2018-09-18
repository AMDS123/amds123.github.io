---
layout: post
title: "Leveraging Heteroscedastic Aleatoric Uncertainties for Robust Real-Time LiDAR 3D Object Detection"
date: 2018-09-14 21:10:42
categories: arXiv_RO
tags: arXiv_RO Object_Detection Inference Detection
author: Di Feng, Lars Rosenbaum, Fabian Timm, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a robust real-time LiDAR 3D object detector that leverages heteroscedastic aleatoric uncertainties to significantly improve its detection performance. A multi-loss function is designed to incorporate uncertainty estimations predicted by auxiliary output layers. Using our proposed method, the network ignores to train from noisy samples, and focuses more on informative ones. We validate our method on the KITTI object detection benchmark. Our method surpasses the baseline method which does not explicitly estimate uncertainties by up to nearly 9% in terms of Average Precision (AP). It also produces state-of-the-art results compared to other methods while running with an inference time of only 72 ms. In addition, we conduct extensive experiments to understand how aleatoric uncertainties behave. Extracting aleatoric uncertainties brings almost no additional computation cost during the deployment, making our method highly desirable for autonomous driving applications.

##### Abstract (translated by Google)
我们提出了一个强大的实时LiDAR 3D物体探测器，利用异方差任意不确定性来显着提高其探测性能。设计多损失函数以结合由辅助输出层预测的不确定性估计。使用我们提出的方法，网络忽略了从嘈杂的样本训练，并更多地关注信息性的样本。我们在KITTI对象检测基准测试中验证了我们的方法。我们的方法超过了基线方法，在平均精度（AP）方面没有明确估计不确定性高达近9％。与其他方法相比，它还可以在推理时间仅为72 ms的情况下运行，从而产生最先进的结果。此外，我们进行了大量实验，以了解任意不确定性的行为。提取任意不确定性在部署期间几乎不会产生额外的计算成本，使得我们的方法非常适合自动驾驶应用。

##### URL
[http://arxiv.org/abs/1809.05590](http://arxiv.org/abs/1809.05590)

##### PDF
[http://arxiv.org/pdf/1809.05590](http://arxiv.org/pdf/1809.05590)

