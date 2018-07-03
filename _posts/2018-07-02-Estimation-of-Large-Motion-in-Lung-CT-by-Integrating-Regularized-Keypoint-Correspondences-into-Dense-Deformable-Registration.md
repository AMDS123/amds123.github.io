---
layout: post
title: "Estimation of Large Motion in Lung CT by Integrating Regularized Keypoint Correspondences into Dense Deformable Registration"
date: 2018-07-02 05:27:27
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Optimization Detection
author: Jan R&#xfc;haak, Thomas Polzin, Stefan Heldmann, Ivor J. A. Simpson, Heinz Handels, Jan Modersitzki, Mattias P. Heinrich
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel algorithm for the registration of pulmonary CT scans. Our method is designed for large respiratory motion by integrating sparse keypoint correspondences into a dense continuous optimization framework. The detection of keypoint correspondences enables robustness against large deformations by jointly optimizing over a large number of potential discrete displacements, whereas the dense continuous registration achieves subvoxel alignment with smooth transformations. Both steps are driven by the same normalized gradient fields data term. We employ curvature regularization and a volume change control mechanism to prevent foldings of the deformation grid and restrict the determinant of the Jacobian to physiologically meaningful values. Keypoint correspondences are integrated into the dense registration by a quadratic penalty with adaptively determined weight. Using a parallel matrix-free derivative calculation scheme, a runtime of about 5 min was realized on a standard PC. The proposed algorithm ranks first in the EMPIRE10 challenge on pulmonary image registration. Moreover, it achieves an average landmark distance of 0.82 mm on the DIR-Lab COPD database, thereby improving upon the state of the art in accuracy by 15%. Our algorithm is the first to reach the inter-observer variability in landmark annotation on this dataset.

##### Abstract (translated by Google)
我们提出了一种新的肺部CT扫描登记算法。我们的方法是通过将稀疏关键点对应关系集成到密集的连续优化框架中来设计用于大呼吸运动。关键点对应的检测通过联合优化大量潜在的离散位移来实现对抗大变形的鲁棒性，而密集连续配准通过平滑变换实现子体素对准。两个步骤均由相同的标准化梯度场数据项驱动。我们采用曲率正则化和体积变化控制机制来防止变形网格的折叠，并将雅可比行列式的行列式限制为生理上有意义的值。通过具有自适应确定权重的二次惩罚将关键点对应关系整合到密集登记中。使用无并行无矩阵导数计算方案，在标准PC上实现了大约5分钟的运行时间。所提出的算法在肺部图像配准的EMPIRE10挑战中排名第一。此外，它在DIR-Lab COPD数据库上实现了0.82mm的平均界标距离，从而将现有技术的精度提高了15％。我们的算法是第一个在该数据集上达到地标注释的观察者间变异性的算法。

##### URL
[http://arxiv.org/abs/1807.00467](http://arxiv.org/abs/1807.00467)

##### PDF
[http://arxiv.org/pdf/1807.00467](http://arxiv.org/pdf/1807.00467)

