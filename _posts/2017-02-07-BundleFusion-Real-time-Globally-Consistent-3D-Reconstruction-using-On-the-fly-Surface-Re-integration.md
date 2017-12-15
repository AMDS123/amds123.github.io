---
layout: post
title: "BundleFusion: Real-time Globally Consistent 3D Reconstruction using On-the-fly Surface Re-integration"
date: 2017-02-07 19:00:46
categories: arXiv_CV
tags: arXiv_CV Sparse Face Pose_Estimation Tracking Optimization
author: Angela Dai, Matthias Nießner, Michael Zollhöfer, Shahram Izadi, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time, high-quality, 3D scanning of large-scale scenes is key to mixed reality and robotic applications. However, scalability brings challenges of drift in pose estimation, introducing significant errors in the accumulated model. Approaches often require hours of offline processing to globally correct model errors. Recent online methods demonstrate compelling results, but suffer from: (1) needing minutes to perform online correction preventing true real-time use; (2) brittle frame-to-frame (or frame-to-model) pose estimation resulting in many tracking failures; or (3) supporting only unstructured point-based representations, which limit scan quality and applicability. We systematically address these issues with a novel, real-time, end-to-end reconstruction framework. At its core is a robust pose estimation strategy, optimizing per frame for a global set of camera poses by considering the complete history of RGB-D input with an efficient hierarchical approach. We remove the heavy reliance on temporal tracking, and continually localize to the globally optimized frames instead. We contribute a parallelizable optimization framework, which employs correspondences based on sparse features and dense geometric and photometric matching. Our approach estimates globally optimized (i.e., bundle adjusted) poses in real-time, supports robust tracking with recovery from gross tracking failures (i.e., relocalization), and re-estimates the 3D model in real-time to ensure global consistency; all within a single framework. Our approach outperforms state-of-the-art online systems with quality on par to offline methods, but with unprecedented speed and scan completeness. Our framework leads to a comprehensive online scanning solution for large indoor environments, enabling ease of use and high-quality results.

##### Abstract (translated by Google)
大规模场景的实时高质量3D扫描是混合现实和机器人应用的关键。然而，可扩展性带来了姿态估计漂移的挑战，在累积模型中引入了显着的误差。方法通常需要数小时的离线处理来全局修正模型错误。最近的在线方法显示出令人信服的结果，但遭受：（1）需要数分钟来执行在线校正，以防止真正的实时使用; （2）脆弱的帧到帧（或帧到模型）姿态估计导致许多跟踪失败;或（3）仅支持非结构化的基于点的表示，这限制了扫描质量和适用性。我们用一种新颖的，实时的，端到端的重建框架来系统地解决这些问题。其核心是一个强大的姿态估计策略，通过考虑RGB-D输入的完整历史，以一种有效的分层方法来优化每帧全局相机姿态。我们消除了对时间跟踪的严重依赖，而是不断将其定位到全局优化框架。我们提供了一个可并行化的优化框架，它采用基于稀疏特征和密集的几何和光度匹配的对应关系。我们的方法估计全局优化（即，束调整）实时姿态，支持强劲的跟踪与从总体跟踪失败（即重新定位）恢复，并实时重新估计三维模型，以确保全球一致性;全部在一个框架内。我们的方法在性能上优于最新的在线系统，其质量与离线方法相当，但具有前所未有的速度和扫描完整性。我们的框架为大型室内环境提供了一个全面的在线扫描解决方案，使得易用性和高质量的结果成为可能。

##### URL
[https://arxiv.org/abs/1604.01093](https://arxiv.org/abs/1604.01093)

##### PDF
[https://arxiv.org/pdf/1604.01093](https://arxiv.org/pdf/1604.01093)

