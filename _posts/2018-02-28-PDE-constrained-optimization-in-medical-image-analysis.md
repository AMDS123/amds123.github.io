---
layout: post
title: "PDE-constrained optimization in medical image analysis"
date: 2018-02-28 20:04:23
categories: arXiv_CV
tags: arXiv_CV Regularization Review Optimization
author: Andreas Mang, Amir Gholami, Christos Davatzikos, George Biros
mathjax: true
---

* content
{:toc}

##### Abstract
PDE-constrained optimization problems find many applications in medical image analysis, for example, neuroimaging, cardiovascular imaging, and oncological imaging. We review related literature and give examples on the formulation, discretization, and numerical solution of PDE-constrained optimization problems for medical imaging. We discuss three examples. The first one is image registration. The second one is data assimilation for brain tumor patients, and the third one data assimilation in cardiovascular imaging. The image registration problem is a classical task in medical image analysis and seeks to find pointwise correspondences between two or more images. The data assimilation problems use a PDE-constrained formulation to link a biophysical model to patient-specific data obtained from medical images. The associated optimality systems turn out to be sets of nonlinear, multicomponent PDEs that are challenging to solve in an efficient way. 
 The ultimate goal of our work is the design of inversion methods that integrate complementary data, and rigorously follow mathematical and physical principles, in an attempt to support clinical decision making. This requires reliable, high-fidelity algorithms with a short time-to-solution. This task is complicated by model and data uncertainties, and by the fact that PDE-constrained optimization problems are ill-posed in nature, and in general yield high-dimensional, severely ill-conditioned systems after discretization. These features make regularization, effective preconditioners, and iterative solvers that, in many cases, have to be implemented on distributed-memory architectures to be practical, a prerequisite. We showcase state-of-the-art techniques in scientific computing to tackle these challenges.

##### Abstract (translated by Google)
PDE约束优化问题在医学图像分析中找到了许多应用，例如神经影像学，心血管成像和肿瘤成像。我们回顾了相关文献，并举例说明了用于医学成像的PDE约束优化问题的制定，离散化和数值解。我们讨论三个例子。第一个是图像注册。第二个是脑肿瘤患者的数据同化，第三个数据同化心血管成像。图像配准问题是医学图像分析中的经典任务，并试图找出两个或更多图像之间的点对应关系。数据同化问题使用PDE约束公式将生物物理学模型与从医学图像获得的患者特定数据联系起来。相关的最优性系统变成了非线性的多组分偏微分方程组，这些组合方法很难以有效的方式解决。
 我们工作的最终目标是设计整合互补数据的反演方法，并严格遵循数学和物理原理，试图支持临床决策。这需要可靠的高保真算法和短时间的解决方案。由于模型和数据的不确定性以及PDE约束优化问题本质上是不适当的，并且一般在离散化后产生高维度，严重病态的系统，这个任务变得复杂了。这些功能使正则化，有效的预处理器和迭代求解器成为可能，这在许多情况下必须在分布式存储器体系结构上实现，这是先决条件。我们展示科学计算中的最先进技术来应对这些挑战。

##### URL
[http://arxiv.org/abs/1803.00058](http://arxiv.org/abs/1803.00058)

##### PDF
[http://arxiv.org/pdf/1803.00058](http://arxiv.org/pdf/1803.00058)

