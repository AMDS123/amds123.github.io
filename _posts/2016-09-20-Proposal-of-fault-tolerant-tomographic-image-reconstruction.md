---
layout: post
title: "Proposal of fault-tolerant tomographic image reconstruction"
date: 2016-09-20 05:09:47
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Hiroyuki Kudo, Keita Takaki, Fukashi Yamazaki, Takuya Nemoto
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with tomographic image reconstruction under the situation where some of projection data bins are contaminated with abnormal data. Such situations occur in various instances of tomography. We propose a new reconstruction algorithm called the Fault-Tolerant reconstruction outlined as follows. The least-squares (L2-norm) error function ||Ax-b||_2^2 used in ordinary iterative reconstructions is sensitive to the existence of abnormal data. The proposed algorithm utilizes the L1-norm error function ||Ax-b||_1^1 instead of the L2-norm, and we develop a row-action-type iterative algorithm using the proximal splitting framework in convex optimization fields. We also propose an improved version of the L1-norm reconstruction called the L1-TV reconstruction, in which a weak Total Variation (TV) penalty is added to the cost function. Simulation results demonstrate that reconstructed images with the L2-norm were severely damaged by the effect of abnormal bins, whereas images with the L1-norm and L1-TV reconstructions were robust to the existence of abnormal bins.

##### Abstract (translated by Google)
本文研究了投影数据箱中某些投影数据箱受到异常数据污染的情况下的断层图像重建问题。这种情况发生在各种断层摄影的情况下。我们提出一种新的重建算法，称为容错重建概述如下。在普通迭代重建中使用的最小二乘（L2范数）误差函数|| Ax-b || _2 ^ 2对异常数据的存在是敏感的。该算法利用L1范数误差函数|| Ax-b || _1 ^ 1代替L2范数，并利用凸优化领域的近似分裂框架，开发了一种行动型迭代算法。我们还提出了一个称为L1-TV重建的L1范数重构的改进版本，其中对成本函数添加了弱总变差（TV）惩罚。仿真结果表明，L2范数的重建图像受到异常箱的影响而严重受损，而L1范数和L1-TV重构的图像对异常箱的存在具有鲁棒性。

##### URL
[https://arxiv.org/abs/1609.06020](https://arxiv.org/abs/1609.06020)

##### PDF
[https://arxiv.org/pdf/1609.06020](https://arxiv.org/pdf/1609.06020)

