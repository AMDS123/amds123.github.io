---
layout: post
title: "Recognition from Hand Cameras"
date: 2016-03-22 09:12:04
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Cheng-Sheng Chan, Shou-Zhong Chen, Pei-Xuan Xie, Chiung-Chih Chang, Min Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We revisit the study of a wrist-mounted camera system (referred to as HandCam) for recognizing activities of hands. HandCam has two unique properties as compared to egocentric systems (referred to as HeadCam): (1) it avoids the need to detect hands; (2) it more consistently observes the activities of hands. By taking advantage of these properties, we propose a deep-learning-based method to recognize hand states (free v.s. active hands, hand gestures, object categories), and discover object categories. Moreover, we propose a novel two-streams deep network to further take advantage of both HandCam and HeadCam. We have collected a new synchronized HandCam and HeadCam dataset with 20 videos captured in three scenes for hand states recognition. Experiments show that our HandCam system consistently outperforms a deep-learning-based HeadCam method (with estimated manipulation regions) and a dense-trajectory-based HeadCam method in all tasks. We also show that HandCam videos captured by different users can be easily aligned to improve free v.s. active recognition accuracy (3.3% improvement) in across-scenes use case. Moreover, we observe that finetuning Convolutional Neural Network consistently improves accuracy. Finally, our novel two-streams deep network combining HandCam and HeadCam features achieves the best performance in four out of five tasks. With more data, we believe a joint HandCam and HeadCam system can robustly log hand states in daily life.

##### Abstract (translated by Google)
我们重新研究了用于识别手部活动的手腕式摄像机系统（简称为HandCam）。与自我中心系统（称为HeadCam）相比，HandCam具有两个独特的特性：（1）避免了检测手的需要; （2）它更一贯地观察手的活动。通过利用这些属性，我们提出了一种基于深度学习的方法来识别手状态（自由诉主动手，手势，对象类别），并发现对象类别。此外，我们提出了一个新的双流深网络，以进一步利用HandCam和HeadCam。我们收集了一个新的同步的HandCam和HeadCam数据集，其中包含20个用于手势识别的场景。实验表明，我们的HandCam系统在所有任务中始终优于基于深度学习的HeadCam方法（具有估计的操作区域）和基于密集轨迹的HeadCam方法。我们还显示，不同用户所拍摄的HandCam视频可以轻松对齐，以改善免费v.s.主动识别的准确性（3.3％的改进）在全景使用案例。此外，我们观察到微调卷积神经网络不断提高准确性。最后，结合HandCam和HeadCam功能的新型双流深度网络在五个任务中的四个中实现了最佳性能。随着更多的数据，我们相信一个联合的HandCam和HeadCam系统可以在日常生活中强大地记录手状态。

##### URL
[https://arxiv.org/abs/1512.01881](https://arxiv.org/abs/1512.01881)

##### PDF
[https://arxiv.org/pdf/1512.01881](https://arxiv.org/pdf/1512.01881)

