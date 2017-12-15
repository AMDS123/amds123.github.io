---
layout: post
title: "Similarity Registration Problems for 2D/3D Ultrasound Calibration"
date: 2016-07-31 18:04:54
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Francisco Vasconcelos, Donald Peebles, Sebastien Ourselin, Danail Stoyanov
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a minimal solution for the similarity registration (rigid pose and scale) between two sets of 3D lines, and also between a set of co-planar points and a set of 3D lines. The first problem is solved up to 8 discrete solutions with a minimum of 2 line-line correspondences, while the second is solved up to 4 discrete solutions using 4 point-line correspondences. We use these algorithms to perform the extrinsic calibration between a pose tracking sensor and a 2D/3D ultrasound (US) curvilinear probe using a tracked needle as calibration target. The needle is tracked as a 3D line, and is scanned by the ultrasound as either a 3D line (3D US) or as a 2D point (2D US). Since the scale factor that converts US scan units to metric coordinates is unknown, the calibration is formulated as a similarity registration problem. We present results with both synthetic and real data and show that the minimum solutions outperform the correspondent non-minimal linear formulations.

##### Abstract (translated by Google)
我们为两组三维线之间的相似性配准（刚性姿态和比例）以及一组共面点和一组三维线之间的相似性配准提出了最小的解决方案。第一个问题可以解决多达8个离散解决方案，至少有2个线路对应关系，而第二个解决方案使用4个点对应点解决多达4个离散解决方案。我们使用这些算法来执行姿态跟踪传感器和2D / 3D超声波（US）曲线探头之间的外部校准，使用跟踪针作为校准目标。针被追踪为3D线，并且通过超声作为3D线（3D US）或作为2D点（2D US）被扫描。由于将美国扫描单位转换为度量坐标的比例因子是未知的，所以校准被表述为相似性配准问题。我们用合成的和真实的数据给出结果，并且显示最小解决方案胜过相应的非最小线性公式。

##### URL
[https://arxiv.org/abs/1608.00247](https://arxiv.org/abs/1608.00247)

##### PDF
[https://arxiv.org/pdf/1608.00247](https://arxiv.org/pdf/1608.00247)

