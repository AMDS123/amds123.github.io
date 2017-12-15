---
layout: post
title: "Dynamic Scene Deblurring using a Locally Adaptive Linear Blur Model"
date: 2016-03-14 13:57:19
categories: arXiv_CV
tags: arXiv_CV
author: Tae Hyun Kim, Seungjun Nah, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art video deblurring methods cannot handle blurry videos recorded in dynamic scenes, since they are built under a strong assumption that the captured scenes are static. Contrary to the existing methods, we propose a video deblurring algorithm that can deal with general blurs inherent in dynamic scenes. To handle general and locally varying blurs caused by various sources, such as moving objects, camera shake, depth variation, and defocus, we estimate pixel-wise non-uniform blur kernels. We infer bidirectional optical flows to handle motion blurs, and also estimate Gaussian blur maps to remove optical blur from defocus in our new blur model. Therefore, we propose a single energy model that jointly estimates optical flows, defocus blur maps and latent frames. We also provide a framework and efficient solvers to minimize the proposed energy model. By optimizing the energy model, we achieve significant improvements in removing general blurs, estimating optical flows, and extending depth-of-field in blurry frames. Moreover, in this work, to evaluate the performance of non-uniform deblurring methods objectively, we have constructed a new realistic dataset with ground truths. In addition, extensive experimental on publicly available challenging video data demonstrate that the proposed method produces qualitatively superior performance than the state-of-the-art methods which often fail in either deblurring or optical flow estimation.

##### Abstract (translated by Google)
最先进的视频去模糊方法不能处理在动态场景中记录的模糊视频，因为它们是建立在捕获的场景是静态的强有力假设之下的。与现有方法相反，我们提出了一种视频去模糊算法，可以处理动态场景中固有的一般模糊。为了处理由各种来源引起的一般和局部变化的模糊，例如移动物体，相机抖动，深度变化和散焦，我们估计像素方式非均匀模糊核。我们推断双向光学流动来处理运动模糊，并且还估计高斯模糊图以从我们的新模糊模型中去除离焦的光学模糊。因此，我们提出了联合估计光流，散焦模糊图和潜在帧的单能模型。我们还提供了一个框架和高效的求解器来最小化所提出的能量模型。通过优化能量模型，我们在消除一般模糊，估计光流和在模糊帧中延伸景深方面取得显着进步。此外，为了客观地评价非均匀去模糊方法的性能，我们构建了一个新的具有真实性的现实数据集。另外，对公开可用的具有挑战性的视频数据进行广泛的实验证明，所提出的方法产生比现有技术中定性优越的性能，其经常在去模糊或光流估计中失败。

##### URL
[https://arxiv.org/abs/1603.04265](https://arxiv.org/abs/1603.04265)

##### PDF
[https://arxiv.org/pdf/1603.04265](https://arxiv.org/pdf/1603.04265)

