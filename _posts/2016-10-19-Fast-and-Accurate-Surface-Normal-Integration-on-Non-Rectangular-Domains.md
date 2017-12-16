---
layout: post
title: "Fast and Accurate Surface Normal Integration on Non-Rectangular Domains"
date: 2016-10-19 15:01:09
categories: arXiv_CV
tags: arXiv_CV Face
author: Martin Bähr, Michael Breuß, Yvain Quéau, Ali Sharifi Boroujerdi, Jean-Denis Durou
mathjax: true
---

* content
{:toc}

##### Abstract
The integration of surface normals for the purpose of computing the shape of a surface in 3D space is a classic problem in computer vision. However, even nowadays it is still a challenging task to devise a method that combines the flexibility to work on non-trivial computational domains with high accuracy, robustness and computational efficiency. By uniting a classic approach for surface normal integration with modern computational techniques we construct a solver that fulfils these requirements. Building upon the Poisson integration model we propose to use an iterative Krylov subspace solver as a core step in tackling the task. While such a method can be very efficient, it may only show its full potential when combined with a suitable numerical preconditioning and a problem-specific initialisation. We perform a thorough numerical study in order to identify an appropriate preconditioner for our purpose. To address the issue of a suitable initialisation we propose to compute this initial state via a recently developed fast marching integrator. Detailed numerical experiments illuminate the benefits of this novel combination. In addition, we show on real-world photometric stereo datasets that the developed numerical framework is flexible enough to tackle modern computer vision applications.

##### Abstract (translated by Google)
为了计算三维空间中曲面的形状，表面法线的整合是计算机视觉中的一个经典问题。然而，即使是在今天，设计一种结合灵活性来处理非平凡计算域的方法，即使在当今，仍然是一个具有高精度，鲁棒性和计算效率的具有挑战性的任务。通过将表面法线积分的经典方法与现代计算技术相结合，我们构建了满足这些要求的求解器。基于泊松积分模型，我们建议使用迭代Krylov子空间求解器作为解决任务的核心步骤。虽然这样的方法可以非常有效，但只有结合适当的数值预处理和特定问题的初始化才能显示出其全部潜力。我们进行彻底的数值研究，以便为我们的目的确定一个适当的预处理器。为了解决合适的初始化问题，我们建议通过最近开发的快速前进集成器来计算这个初始状态。详细的数值实验阐明了这种新型组合的好处。另外，我们在真实世界的光度立体数据集上展示了已开发的数字框架足够灵活以应对现代计算机视觉应用。

##### URL
[https://arxiv.org/abs/1610.06049](https://arxiv.org/abs/1610.06049)

##### PDF
[https://arxiv.org/pdf/1610.06049](https://arxiv.org/pdf/1610.06049)

