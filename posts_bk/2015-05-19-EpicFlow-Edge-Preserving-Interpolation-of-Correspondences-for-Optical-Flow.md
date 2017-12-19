---
layout: post
title: "EpicFlow: Edge-Preserving Interpolation of Correspondences for Optical Flow"
date: 2015-05-19 14:46:16
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jerome Revaud (INRIA Grenoble Rhône-Alpes / LJK Laboratoire Jean Kuntzmann), Philippe Weinzaepfel (INRIA Grenoble Rhône-Alpes / LJK Laboratoire Jean Kuntzmann), Zaid Harchaoui (INRIA Grenoble Rhône-Alpes / LJK Laboratoire Jean Kuntzmann), Cordelia Schmid (INRIA Grenoble Rhône-Alpes / LJK Laboratoire Jean Kuntzmann)
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel approach for optical flow estimation , targeted at large displacements with significant oc-clusions. It consists of two steps: i) dense matching by edge-preserving interpolation from a sparse set of matches; ii) variational energy minimization initialized with the dense matches. The sparse-to-dense interpolation relies on an appropriate choice of the distance, namely an edge-aware geodesic distance. This distance is tailored to handle occlusions and motion boundaries -- two common and difficult issues for optical flow computation. We also propose an approximation scheme for the geodesic distance to allow fast computation without loss of performance. Subsequent to the dense interpolation step, standard one-level variational energy minimization is carried out on the dense matches to obtain the final flow estimation. The proposed approach, called Edge-Preserving Interpolation of Correspondences (EpicFlow) is fast and robust to large displacements. It significantly outperforms the state of the art on MPI-Sintel and performs on par on Kitti and Middlebury.

##### Abstract (translated by Google)
我们提出了一种新的光学流量估计方法，针对具有明显的偶团的大位移。它由两个步骤组成：i）通过一个稀疏匹配集进行边保留插值的稠密匹配; ii）利用密集匹配初始化的变分能量最小化。稀疏到高密度插值依赖于距离的适当选择，即边缘感知测地距离。这个距离是为了处理遮挡和运动边界而设计的 - 这是光流计算的两个常见和困难的问题。我们还提出了测地距离的近似方案，以允许快速计算而不损失性能。在密集插值步骤之后，对密集匹配执行标准的一级变分能量最小化以获得最终的流量估计。所提出的方法称为对应的边缘保持插值（EpicFlow），对于大位移快速和稳健。它明显优于MPI-Sintel的最新技术，并在Kitti和Middlebury上表现优异。

##### URL
[https://arxiv.org/abs/1501.02565](https://arxiv.org/abs/1501.02565)

##### PDF
[https://arxiv.org/pdf/1501.02565](https://arxiv.org/pdf/1501.02565)

