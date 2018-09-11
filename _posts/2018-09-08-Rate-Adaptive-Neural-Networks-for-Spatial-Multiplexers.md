---
layout: post
title: "Rate-Adaptive Neural Networks for Spatial Multiplexers"
date: 2018-09-08 18:21:31
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Inference Recognition
author: Suhas Lohit, Rajhans Singh, Kuldeep Kulkarni, Pavan Turaga
mathjax: true
---

* content
{:toc}

##### Abstract
In resource-constrained environments, one can employ spatial multiplexing cameras to acquire a small number of measurements of a scene, and perform effective reconstruction or high-level inference using purely data-driven neural networks. However, once trained, the measurement matrix and the network are valid only for a single measurement rate (MR) chosen at training time. To overcome this drawback, we answer the following question: How can we jointly design the measurement operator and the reconstruction/inference network so that the system can operate over a \textit{range} of MRs? To this end, we present a novel training algorithm, for learning \textbf{\textit{rate-adaptive}} networks. Using standard datasets, we demonstrate that, when tested over a range of MRs, a rate-adaptive network can provide high quality reconstruction over a the entire range, resulting in up to about 15 dB improvement over previous methods, where the network is valid for only one MR. We demonstrate the effectiveness of our approach for sample-efficient object tracking where video frames are acquired at dynamically varying MRs. We also extend this algorithm to learn the measurement operator in conjunction with image recognition networks. Experiments on MNIST and CIFAR-10 confirm the applicability of our algorithm to different tasks.

##### Abstract (translated by Google)
在资源受限的环境中，可以使用空间复用相机来获取场景的少量测量，并使用纯数据驱动的神经网络执行有效的重建或高级推断。但是，一旦经过训练，测量矩阵和网络仅对训练时选择的单个测量速率（MR）有效。为了克服这个缺点，我们回答了以下问题：我们如何联合设计测量算子和重建/推理网络，以便系统可以在MR的\ textit {范围}上运行？为此，我们提出了一种新颖的训练算法，用于学习\ textbf {\ textit {rate-adaptive}网络。使用标准数据集，我们证明，当在一系列MR上进行测试时，速率自适应网络可以在整个范围内提供高质量的重建，与之前的网络有效的方法相比，最多可提高约15 dB。只有一个MR。我们证明了我们的方法对样本有效物体跟踪的有效性，其中视频帧是在动态变化的MR下获得的。我们还扩展了该算法，以结合图像识别网络学习测量算子。在MNIST和CIFAR-10上的实验证实了我们的算法在不同任务中的适用性。

##### URL
[http://arxiv.org/abs/1809.02850](http://arxiv.org/abs/1809.02850)

##### PDF
[http://arxiv.org/pdf/1809.02850](http://arxiv.org/pdf/1809.02850)

