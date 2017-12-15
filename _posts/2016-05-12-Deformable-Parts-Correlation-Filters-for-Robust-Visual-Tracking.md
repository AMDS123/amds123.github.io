---
layout: post
title: "Deformable Parts Correlation Filters for Robust Visual Tracking"
date: 2016-05-12 08:22:46
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Inference Relation
author: Alan Lukežič, Luka Čehovin, Matej Kristan
mathjax: true
---

* content
{:toc}

##### Abstract
Deformable parts models show a great potential in tracking by principally addressing non-rigid object deformations and self occlusions, but according to recent benchmarks, they often lag behind the holistic approaches. The reason is that potentially large number of degrees of freedom have to be estimated for object localization and simplifications of the constellation topology are often assumed to make the inference tractable. We present a new formulation of the constellation model with correlation filters that treats the geometric and visual constraints within a single convex cost function and derive a highly efficient optimization for MAP inference of a fully-connected constellation. We propose a tracker that models the object at two levels of detail. The coarse level corresponds a root correlation filter and a novel color model for approximate object localization, while the mid-level representation is composed of the new deformable constellation of correlation filters that refine the object location. The resulting tracker is rigorously analyzed on a highly challenging OTB, VOT2014 and VOT2015 benchmarks, exhibits a state-of-the-art performance and runs in real-time.

##### Abstract (translated by Google)
可变形零件模型通过主要解决非刚性物体变形和自闭现象显示了追踪的巨大潜力，但根据最近的基准，它们通常落后于整体方法。原因在于对于物体定位可能需要估计大量的自由度，并且通常假设星座拓扑的简化使得推理易于处理。我们提出了一种带有相关滤波器的星座模型的新公式，该公式在单个凸成本函数内处理几何和视觉约束，并且为全连接星座的MAP推导导出高效率的优化。我们提出一个跟踪器，在两个细节层次上对对象进行建模。粗级对应于根相关滤波器和用于近似物体定位的新颖颜色模型，而中级表示由用于细化物体位置的新的可变形星座相关滤波器组成。所得到的跟踪器在极具挑战性的OTB，VOT2014和VOT2015基准上进行了严格的分析，展现了最先进的性能并实时运行。

##### URL
[https://arxiv.org/abs/1605.03720](https://arxiv.org/abs/1605.03720)

##### PDF
[https://arxiv.org/pdf/1605.03720](https://arxiv.org/pdf/1605.03720)

