---
layout: post
title: "InfiniTAM v3: A Framework for Large-Scale 3D Reconstruction with Loop Closure"
date: 2017-08-02 14:50:02
categories: arXiv_CV
tags: arXiv_CV Tracking SLAM
author: Victor Adrian Prisacariu, Olaf Kähler, Stuart Golodetz, Michael Sapienza, Tommaso Cavallari, Philip H S Torr, David W Murray
mathjax: true
---

* content
{:toc}

##### Abstract
Volumetric models have become a popular representation for 3D scenes in recent years. One breakthrough leading to their popularity was KinectFusion, which focuses on 3D reconstruction using RGB-D sensors. However, monocular SLAM has since also been tackled with very similar approaches. Representing the reconstruction volumetrically as a TSDF leads to most of the simplicity and efficiency that can be achieved with GPU implementations of these systems. However, this representation is memory-intensive and limits applicability to small-scale reconstructions. Several avenues have been explored to overcome this. With the aim of summarizing them and providing for a fast, flexible 3D reconstruction pipeline, we propose a new, unifying framework called InfiniTAM. The idea is that steps like camera tracking, scene representation and integration of new data can easily be replaced and adapted to the user's needs. This report describes the technical implementation details of InfiniTAM v3, the third version of our InfiniTAM system. We have added various new features, as well as making numerous enhancements to the low-level code that significantly improve our camera tracking performance. The new features that we expect to be of most interest are (i) a robust camera tracking module; (ii) an implementation of Glocker et al.'s keyframe-based random ferns camera relocaliser; (iii) a novel approach to globally-consistent TSDF-based reconstruction, based on dividing the scene into rigid submaps and optimising the relative poses between them; and (iv) an implementation of Keller et al.'s surfel-based reconstruction approach.

##### Abstract (translated by Google)
体积模型近年来已成为3D场景的流行代表。 KinectFusion是使用RGB-D传感器进行三维重建的重要突破。然而，单眼SLAM自那以后也采用了非常相似的方法。将体积重建表示为TSDF导致了这些系统的GPU实现可以实现的大部分简单性和效率。然而，这种表示方式是内存密集型的，限制了对小规模重建的适用性。已经探索了几条途径来克服这个问题。为了总结它们并提供一个快速，灵活的3D重建流水线，我们提出了一个称为InfiniTAM的新的统一框架。这个想法是像相机跟踪，场景表示和新数据整合等步骤可以很容易地取代和适应用户的需求。本报告介绍InfiniTAM v3的技术实现细节，InfiniTAM系统的第三个版本。我们增加了各种新功能，并对底层代码进行了大量改进，从而显着改善了我们的相机跟踪性能。我们期望最感兴​​趣的新功能是（i）强大的相机跟踪模块; （ii）Glocker等人的基于关键帧的随机蕨类相机再定标器的实现; （iii）基于全局一致的基于TSDF的重建的新方法，其基于将场景划分为刚性的子图并且优化它们之间的相对姿势;和（iv）实施Keller等人的基于surfel的重建方法。

##### URL
[https://arxiv.org/abs/1708.00783](https://arxiv.org/abs/1708.00783)

##### PDF
[https://arxiv.org/pdf/1708.00783](https://arxiv.org/pdf/1708.00783)

