---
layout: post
title: "Robust Cardiac Motion Estimation using Ultrafast Ultrasound Data: A Low-Rank-Topology-Preserving Approach"
date: 2017-04-25 13:24:48
categories: arXiv_CV
tags: arXiv_CV GAN
author: Angelica I. Aviles, Thomas Widlak, Alicia Casals, Maartje M. Nillesen, Habib Ammari
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac motion estimation is an important diagnostic tool to detect heart diseases and it has been explored with modalities such as MRI and conventional ultrasound (US) sequences. US cardiac motion estimation still presents challenges because of the complex motion patterns and the presence of noise. In this work, we propose a novel approach to estimate the cardiac motion using ultrafast ultrasound data. -- Our solution is based on a variational formulation characterized by the L2-regularized class. The displacement is represented by a lattice of b-splines and we ensure robustness by applying a maximum likelihood type estimator. While this is an important part of our solution, the main highlight of this paper is to combine a low-rank data representation with topology preservation. Low-rank data representation (achieved by finding the k-dominant singular values of a Casorati Matrix arranged from the data sequence) speeds up the global solution and achieves noise reduction. On the other hand, topology preservation (achieved by monitoring the Jacobian determinant) allows to radically rule out distortions while carefully controlling the size of allowed expansions and contractions. Our variational approach is carried out on a realistic dataset as well as on a simulated one. We demonstrate how our proposed variational solution deals with complex deformations through careful numerical experiments. While maintaining the accuracy of the solution, the low-rank preprocessing is shown to speed up the convergence of the variational problem. Beyond cardiac motion estimation, our approach is promising for the analysis of other organs that experience motion.

##### Abstract (translated by Google)
心脏运动估计是检测心脏疾病的重要诊断工具，并且已经利用诸如MRI和常规超声（US）序列的模式进行了探索。由于复杂的运动模式和噪声的存在，美国心脏运动估计仍然面临挑战。在这项工作中，我们提出了一种新的方法来估计使用超快超声数据的心脏运动。 - 我们的解决方案是基于L2正则化类的变分公式。位移由b样条点阵表示，我们通过应用最大似然估计量来确保鲁棒性。虽然这是我们解决方案的重要组成部分，但本文的主要亮点是将低级数据表示与拓扑保存相结合。低秩数据表示（通过查找从数据序列排列的Casorati矩阵的k-主导奇异值来实现）加速了全局解，并实现了降噪。另一方面，拓扑保持（通过监视雅可比行列式实现）允许从根本上排除失真，同时仔细控制允许的扩展和收缩的大小。我们的变分方法是在一个真实的数据集上以及在一个模拟的数据集上进行的。我们展示了我们提出的变分解决方案如何通过仔细的数值实验处理复杂的变形。在保持解的准确性的同时，显示了低阶预处理加速了变分问题的收敛。除了心脏运动估计之外，我们的方法对于分析经历运动的其他器官是有希望的。

##### URL
[https://arxiv.org/abs/1611.02730](https://arxiv.org/abs/1611.02730)

##### PDF
[https://arxiv.org/pdf/1611.02730](https://arxiv.org/pdf/1611.02730)

