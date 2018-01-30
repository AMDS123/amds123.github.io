---
layout: post
title: "Meshed Up: Learnt Error Correction in 3D Reconstructions"
date: 2018-01-27 19:38:21
categories: arXiv_CV
tags: arXiv_CV
author: Michael Tanner, Stefan Saftescu, Alex Bewley, Paul Newman (Oxford Robotics Institute)
mathjax: true
---

* content
{:toc}

##### Abstract
Dense reconstructions often contain errors that prior work has so far minimised using high quality sensors and regularising the output. Nevertheless, errors still persist. This paper proposes a machine learning technique to identify errors in three dimensional (3D) meshes. Beyond simply identifying errors, our method quantifies both the magnitude and the direction of depth estimate errors when viewing the scene. This enables us to improve the reconstruction accuracy. 
 We train a suitably deep network architecture with two 3D meshes: a high-quality laser reconstruction, and a lower quality stereo image reconstruction. The network predicts the amount of error in the lower quality reconstruction with respect to the high-quality one, having only view the former through its input. We evaluate our approach by correcting two-dimensional (2D) inverse-depth images extracted from the 3D model, and show that our method improves the quality of these depth reconstructions by up to a relative 10% RMSE.

##### Abstract (translated by Google)
密集重建往往包含错误，以前的工作到目前为止使用高质量的传感器和正规化的输出最小化。尽管如此，错误仍然存​​在。本文提出了一种机器学习技术来识别三维（3D）网格中的错误。除了简单地识别错误之外，我们的方法量化观看场景时的深度估计误差的大小和方向。这使我们能够提高重建的准确性。
 我们用两个三维网格来训练适当深度的网络结构：高质量的激光重建和低质量的立体图像重建。网络预测低质量重构中的高质量重构的误差量，仅通过其输入来查看前者。我们通过校正从3D模型提取的二维（2D）逆深度图像来评估我们的方法，并且显示我们的方法通过高达相对10％的RMSE提高了这些深度重建的质量。

##### URL
[http://arxiv.org/abs/1801.09128](http://arxiv.org/abs/1801.09128)

##### PDF
[http://arxiv.org/pdf/1801.09128](http://arxiv.org/pdf/1801.09128)

