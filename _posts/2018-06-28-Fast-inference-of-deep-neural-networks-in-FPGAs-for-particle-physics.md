---
layout: post
title: "Fast inference of deep neural networks in FPGAs for particle physics"
date: 2018-06-28 21:43:10
categories: arXiv_CV
tags: arXiv_CV Inference
author: Javier Duarte, Song Han, Philip Harris, Sergo Jindariani, Edward Kreinar, Benjamin Kreis, Jennifer Ngadiuba, Maurizio Pierini, Ryan Rivera, Nhan Tran, Zhenbin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Recent results at the Large Hadron Collider (LHC) have pointed to enhanced physics capabilities through the improvement of the real-time event processing techniques. Machine learning methods are ubiquitous and have proven to be very powerful in LHC physics, and particle physics as a whole. However, exploration of the use of such techniques in low-latency, low-power FPGA hardware has only just begun. FPGA-based trigger and data acquisition (DAQ) systems have extremely low, sub-microsecond latency requirements that are unique to particle physics. We present a case study for neural network inference in FPGAs focusing on a classifier for jet substructure which would enable, among many other physics scenarios, searches for new dark sector particles and novel measurements of the Higgs boson. While we focus on a specific example, the lessons are far-reaching. We develop a package based on High-Level Synthesis (HLS) called hls4ml to build machine learning models in FPGAs. The use of HLS increases accessibility across a broad user community and allows for a drastic decrease in firmware development time. We map out FPGA resource usage and latency versus neural network hyperparameters to identify the problems in particle physics that would benefit from performing neural network inference with FPGAs. For our example jet substructure model, we fit well within the available resources of modern FPGAs with a latency on the scale of 100 ns.

##### Abstract (translated by Google)
最近在大型强子对撞机（LHC）的研究结果表明，通过改进实时事件处理技术可以提高物理性能。机器学习方法无处不在，已被证明在LHC物理学和粒子物理学中是非常强大的。然而，探索在低延迟，低功耗FPGA硬件中使用这些技术才刚刚开始。基于FPGA的触发和数据采集（DAQ）系统具有极低的亚微秒级延迟要求，这是粒子物理学所特有的。我们提出了一个关于FPGA中神经网络推理的案例研究，重点关注喷射子结构的分类器，它可以在许多其他物理场景中搜索新的黑色扇形粒子和希格斯玻色子的新颖测量。虽然我们着重于一个具体的例子，但是这些经验教训是深远的。我们开发了一种基于高级综合（HLS）的软件包，名为hls4ml，用于在FPGA中构建机器学习模型。 HLS的使用提高了广大用户社区的可访问性，并可大幅缩短固件开发时间。我们绘制出FPGA资源使用情况和等待时间与神经网络超参数的关系，以确定在利用FPGA执行神经网络推理中受益的粒子物理问题。对于我们的喷射子结构模型示例，我们很适合现代FPGA的可用资源，并具有100纳秒的延迟。

##### URL
[http://arxiv.org/abs/1804.06913](http://arxiv.org/abs/1804.06913)

##### PDF
[http://arxiv.org/pdf/1804.06913](http://arxiv.org/pdf/1804.06913)

