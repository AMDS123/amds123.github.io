---
layout: post
title: "Joint Multi-view Face Alignment in the Wild"
date: 2017-08-20 21:20:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge GAN Face Tracking CNN Detection Face_Detection
author: Jiankang Deng, George Trigeorgis, Yuxiang Zhou, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
The de facto algorithm for facial landmark estimation involves running a face detector with a subsequent deformable model fitting on the bounding box. This encompasses two basic problems: i) the detection and deformable fitting steps are performed independently, while the detector might not provide best-suited initialisation for the fitting step, ii) the face appearance varies hugely across different poses, which makes the deformable face fitting very challenging and thus distinct models have to be used (\eg, one for profile and one for frontal faces). In this work, we propose the first, to the best of our knowledge, joint multi-view convolutional network to handle large pose variations across faces in-the-wild, and elegantly bridge face detection and facial landmark localisation tasks. Existing joint face detection and landmark localisation methods focus only on a very small set of landmarks. By contrast, our method can detect and align a large number of landmarks for semi-frontal (68 landmarks) and profile (39 landmarks) faces. We evaluate our model on a plethora of datasets including standard static image datasets such as IBUG, 300W, COFW, and the latest Menpo Benchmark for both semi-frontal and profile faces. Significant improvement over state-of-the-art methods on deformable face tracking is witnessed on 300VW benchmark. We also demonstrate state-of-the-art results for face detection on FDDB and MALF datasets.

##### Abstract (translated by Google)
用于面部标志估计的事实上的算法涉及运行具有在边界框上拟合的随后的可变形模型的面部检测器。这包括两个基本问题：（1）检测和变形的拟合步骤是独立进行的，而检测器可能不提供适合于拟合步骤的最佳拟合;（2）不同姿态的面貌变化很大，这使得可变形的面部拟合非常具有挑战性，因此必须使用不同的模型（例如，一个用于轮廓，一个用于正面）。在这项工作中，我们首先提出了联合多视角卷积网络来处理人脸中的大幅度姿态变化，并优雅地桥接人脸检测和面部标志定位任务。现有的联合人脸检测和地标定位方法只集中在一小部分地标上。相比之下，我们的方法可以检测和对齐大量的半正面（68个地标）和轮廓（39个地标）面的地标。我们在众多的数据集上评估我们的模型，包括标准的静态图像数据集，如IBUG，300W，COFW和最新的Menpo基准，用于半正面和侧面。基于300VW基准测试，可变形脸部跟踪的最先进方法得到了显着改善。我们还在FDDB和MALF数据集上展示了最新的人脸检测结果。

##### URL
[https://arxiv.org/abs/1708.06023](https://arxiv.org/abs/1708.06023)

##### PDF
[https://arxiv.org/pdf/1708.06023](https://arxiv.org/pdf/1708.06023)

