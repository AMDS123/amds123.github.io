---
layout: post
title: "Progressive LiDAR Adaptation for Road Detection"
date: 2019-04-02 04:22:23
categories: arXiv_CV
tags: arXiv_CV Detection
author: Zhe Chen, Jing Zhang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Despite rapid developments in visual image-based road detection, robustly identifying road areas in visual images remains challenging due to issues like illumination changes and blurry images. To this end, LiDAR sensor data can be incorporated to improve the visual image-based road detection, because LiDAR data is less susceptible to visual noises. However, the main difficulty in introducing LiDAR information into visual image-based road detection is that LiDAR data and its extracted features do not share the same space with the visual data and visual features. Such gaps in spaces may limit the benefits of LiDAR information for road detection. To overcome this issue, we introduce a novel Progressive LiDAR Adaptation-aided Road Detection (PLARD) approach to adapt LiDAR information into visual image-based road detection and improve detection performance. In PLARD, progressive LiDAR adaptation consists of two subsequent modules: 1) data space adaptation, which transforms the LiDAR data to the visual data space to align with the perspective view by applying altitude difference-based transformation; and 2) feature space adaptation, which adapts LiDAR features to visual features through a cascaded fusion structure. Comprehensive empirical studies on the well-known KITTI road detection benchmark demonstrate that PLARD takes advantage of both the visual and LiDAR information, achieving much more robust road detection even in challenging urban scenes. In particular, PLARD outperforms other state-of-the-art road detection models and is currently top of the publicly accessible benchmark leader-board.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01206](http://arxiv.org/abs/1904.01206)

##### PDF
[http://arxiv.org/pdf/1904.01206](http://arxiv.org/pdf/1904.01206)

