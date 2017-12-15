---
layout: post
title: "Richardson-Lucy Deblurring for Moving Light Field Cameras"
date: 2017-05-19 08:20:54
categories: arXiv_CV
tags: arXiv_CV Regularization Quantitative
author: Donald G. Dansereau, Anders Eriksson, Jürgen Leitner
mathjax: true
---

* content
{:toc}

##### Abstract
We generalize Richardson-Lucy (RL) deblurring to 4-D light fields by replacing the convolution steps with light field rendering of motion blur. The method deals correctly with blur caused by 6-degree-of-freedom camera motion in complex 3-D scenes, without performing depth estimation. We introduce a novel regularization term that maintains parallax information in the light field while reducing noise and ringing. We demonstrate the method operating effectively on rendered scenes and scenes captured using an off-the-shelf light field camera. An industrial robot arm provides repeatable and known trajectories, allowing us to establish quantitative performance in complex 3-D scenes. Qualitative and quantitative results confirm the effectiveness of the method, including commonly occurring cases for which previously published methods fail. We include mathematical proof that the algorithm converges to the maximum-likelihood estimate of the unblurred scene under Poisson noise. We expect extension to blind methods to be possible following the generalization of 2-D Richardson-Lucy to blind deconvolution.

##### Abstract (translated by Google)
我们通过用运动模糊的光场渲染来替代卷积步骤，将Richardson-Lucy（RL）去模糊概括为4-D光场。该方法正确地处理在复杂的三维场景中由6自由度相机运动引起的模糊，而不执行深度估计。我们引入了一个新颖的正则化术语，它可以在减少噪声和振铃的同时保持光场中的视差信息。我们演示了在使用现成的光场相机拍摄的渲染场景和场景上有效运行的方法。工业机器人手臂提供可重复和已知的轨迹，使我们能够在复杂的三维场景中建立定量性能。定性和定量结果证实了该方法的有效性，包括以前发表的方法失败的常见情况。我们包括数学证明，该算法收敛于泊松噪声下的非模糊场景的最大似然估计。随着二维Richardson-Lucy推广到盲解卷积，我们期望盲目方法的扩展是可能的。

##### URL
[https://arxiv.org/abs/1606.04308](https://arxiv.org/abs/1606.04308)

##### PDF
[https://arxiv.org/pdf/1606.04308](https://arxiv.org/pdf/1606.04308)

