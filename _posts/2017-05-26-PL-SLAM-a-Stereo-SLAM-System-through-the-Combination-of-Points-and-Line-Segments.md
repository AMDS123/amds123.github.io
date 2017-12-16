---
layout: post
title: "PL-SLAM: a Stereo SLAM System through the Combination of Points and Line Segments"
date: 2017-05-26 08:52:38
categories: arXiv_CV
tags: arXiv_CV SLAM
author: Ruben Gomez-Ojeda, Francisco-Angel Moreno, Davide Scaramuzza, Javier Gonzalez-Jimenez
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional approaches to stereo visual SLAM rely on point features to estimate the camera trajectory and build a map of the environment. In low-textured environments, though, it is often difficult to find a sufficient number of reliable point features and, as a consequence, the performance of such algorithms degrades. This paper proposes PL-SLAM, a stereo visual SLAM system that combines both points and line segments to work robustly in a wider variety of scenarios, particularly in those where point features are scarce or not well-distributed in the image. PL-SLAM leverages both points and segments at all the instances of the process: visual odometry, keyframe selection, bundle adjustment, etc. We contribute also with a loop closure procedure through a novel bag-of-words approach that exploits the combined descriptive power of the two kinds of features. Additionally, the resulting map is richer and more diverse in 3D elements, which can be exploited to infer valuable, high-level scene structures like planes, empty spaces, ground plane, etc. (not addressed in this work). Our proposal has been tested with several popular datasets (such as KITTI and EuRoC), and is compared to state of the art methods like ORB-SLAM, revealing superior performance in most of the experiments, while still running in real-time. An open source version of the PL-SLAM C++ code will be released for the benefit of the community.

##### Abstract (translated by Google)
传统的立体视觉SLAM方法依靠点特征来估计摄像机轨迹并建立环境图。然而，在低纹理的环境中，通常难以找到足够数量的可靠点特征，因此这种算法的性能下降。本文提出了PL-SLAM，一种结合点和线段的立体视觉SLAM系统，可以在各种场景下稳健地工作，特别是在图像中点特征稀缺或分布不均的情况下。 PL-SLAM在过程的所有实例中都利用了点和段：视觉测距法，关键帧选择，束调整等。我们还通过一种新颖的词袋方法来贡献循环闭合过程，该方法利用组合的描述能力的两种特征。此外，由此产生的地图在3D元素中更加丰富和多样化，可以利用这些元素来推断有价值的，高层次的场景结构，如平面，空白空间，地平面等（在本文中未涉及）。我们的建议已经通过几个流行的数据集（如KITTI和EuRoC）进行了测试，并与ORB-SLAM等最先进的方法进行了比较，在大多数实验中仍然表现出优异的性能，同时仍在实时运行。 PL-SLAM C ++代码的开源版本将为社区而发布。

##### URL
[https://arxiv.org/abs/1705.09479](https://arxiv.org/abs/1705.09479)

##### PDF
[https://arxiv.org/pdf/1705.09479](https://arxiv.org/pdf/1705.09479)

