---
layout: post
title: "Computational Mapping of the Ground Reflectivity with Laser Scanners"
date: 2017-03-09 17:34:26
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Juan Castorena
mathjax: true
---

* content
{:toc}

##### Abstract
In this investigation we focus on the problem of mapping the ground reflectivity with multiple laser scanners mounted on mobile robots/vehicles. The problem originates because regions of the ground become populated with a varying number of reflectivity measurements whose value depends on the observer and its corresponding perspective. Here, we propose a novel automatic, data-driven computational mapping framework specifically aimed at preserving edge sharpness in the map reconstruction process and that considers the sources of measurement variation. Our new formulation generates map-perspective gradients and applies sub-set selection fusion and de-noising operators to these through iterative algorithms that minimize an $\ell_1$ sparse regularized least squares formulation. Reconstruction of the ground reflectivity is then carried out based on Poisson's formulation posed as an $\ell_2$ term promoting consistency with the fused gradient of map-perspectives and a term that ensures equality constraints with reference measurement data. We demonstrate our new framework outperforms the capabilities of existing ones with experiments realized on Ford's fleet of autonomous vehicles. For example, we show we can achieve map enhancement (i.e., contrast enhancement), artifact removal, de-noising and map-stitching without requiring an additional reflectivity adjustment to calibrate sensors to the specific mounting and robot/vehicle motion.

##### Abstract (translated by Google)
在这项调查中，我们将重点放在用安装在移动机器人/车辆上的多个激光扫描仪来映射地面反射率的问题上。这个问题的根源在于地面上的地区有不同数量的反射率测量值，这些测量值取决于观测者及其相应的观点。在这里，我们提出了一种新颖的自动，数据驱动的计算映射框架，专门用于保存地图重建过程中的边缘清晰度，并考虑测量变化的来源。我们的新公式生成地图透视梯度，并通过迭代算法将子集选择融合和去噪运算符应用于这些算法，这些迭代算法使$ \ ell_1 $稀疏正则化最小二乘公式最小化。地面反射率的重建基于Poisson公式作为$ \ ell_2 $项来进行，以促进与地图视角的融合梯度的一致性，以及确保与参考测量数据的等式约束的术语。我们展示了我们的新架构在福特车队的自主车辆上实现的性能优于现有的架构。例如，我们显示我们可以实现地图增强（即，对比度增强），伪像去除，去噪和地图拼接，而不需要额外的反射率调整来校准传感器到特定的安装和机器人/车辆运动。

##### URL
[https://arxiv.org/abs/1611.09203](https://arxiv.org/abs/1611.09203)

##### PDF
[https://arxiv.org/pdf/1611.09203](https://arxiv.org/pdf/1611.09203)

