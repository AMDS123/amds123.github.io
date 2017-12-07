---
layout: post
title: "Learning Sampling Distributions for Efficient Object Detection"
date: 2015-11-02 12:52:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face_Detection Detection
author: Yanwei Pang, Jiale Cao, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is an important task in computer vision and learning systems. Multistage particle windows (MPW), proposed by Gualdi et al., is an algorithm of fast and accurate object detection. By sampling particle windows from a proposal distribution (PD), MPW avoids exhaustively scanning the image. Despite its success, it is unknown how to determine the number of stages and the number of particle windows in each stage. Moreover, it has to generate too many particle windows in the initialization step and it redraws unnecessary too many particle windows around object-like regions. In this paper, we attempt to solve the problems of MPW. An important fact we used is that there is large probability for a randomly generated particle window not to contain the object because the object is a sparse event relevant to the huge number of candidate windows. Therefore, we design the proposal distribution so as to efficiently reject the huge number of non-object windows. Specifically, we propose the concepts of rejection, acceptance, and ambiguity windows and regions. This contrasts to MPW which utilizes only on region of support. The PD of MPW is acceptance-oriented whereas the PD of our method (called iPW) is rejection-oriented. Experimental results on human and face detection demonstrate the efficiency and effectiveness of the iPW algorithm. The source code is publicly accessible.

##### Abstract (translated by Google)
目标检测是计算机视觉和学习系统中的一项重要任务。 Gualdi等人提出的多级粒子窗（MPW）是快速和准确的目标检测算法。通过从提议分布（PD）中抽样粒子窗口，MPW避免彻底地扫描图像。尽管成功，但如何确定阶段的数量和每个阶段的粒子窗口的数量是未知的。而且，它在初始化步骤中必须产生太多的粒子窗口，并且在类似物体的区域周围重绘不必要的太多粒子窗口。本文试图解决MPW的问题。我们使用的一个重要事实是，随机生成的粒子窗口不大可能包含对象，因为对象是与大量候选窗口相关的稀疏事件。因此，我们设计提案分配，以有效地拒绝大量的非对象窗口。具体而言，我们提出拒绝，接受和歧义窗口和地区的概念。这与仅在支持区域使用的MPW形成对比。 MPW的PD是接受导向的，而我们的方法PD（称为iPW）是拒绝导向的。人脸检测的实验结果证明了iPW算法的有效性和有效性。源代码是可公开访问的。

##### URL
[https://arxiv.org/abs/1508.05581](https://arxiv.org/abs/1508.05581)

##### PDF
[https://arxiv.org/pdf/1508.05581](https://arxiv.org/pdf/1508.05581)

