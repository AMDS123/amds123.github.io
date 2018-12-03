---
layout: post
title: "CubemapSLAM: A Piecewise-Pinhole Monocular Fisheye SLAM System"
date: 2018-11-30 06:25:23
categories: arXiv_RO
tags: arXiv_RO Face Optimization SLAM
author: Yahui Wang, Shaojun Cai, Shi-Jie Li, Yun Liu, Yangyan Guo, Tao Li, Ming-Ming Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
We present a real-time feature-based SLAM (Simultaneous Localization and Mapping) system for fisheye cameras featured by a large field-of-view (FoV). Large FoV cameras are beneficial for large-scale outdoor SLAM applications, because they increase visual overlap between consecutive frames and capture more pixels belonging to the static parts of the environment. However, current feature-based SLAM systems such as PTAM and ORB-SLAM limit their camera model to pinhole only. To compensate for the vacancy, we propose a novel SLAM system with the cubemap model that utilizes the full FoV without introducing distortion from the fisheye lens, which greatly benefits the feature matching pipeline. In the initialization and point triangulation stages, we adopt a unified vector-based representation to efficiently handle matches across multiple faces, and based on this representation we propose and analyze a novel inlier checking metric. In the optimization stage, we design and test a novel multi-pinhole reprojection error metric that outperforms other metrics by a large margin. We evaluate our system comprehensively on a public dataset as well as a self-collected dataset that contains real-world challenging sequences. The results suggest that our system is more robust and accurate than other feature-based fisheye SLAM approaches. The CubemapSLAM system has been released into the public domain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12633](http://arxiv.org/abs/1811.12633)

##### PDF
[http://arxiv.org/pdf/1811.12633](http://arxiv.org/pdf/1811.12633)

