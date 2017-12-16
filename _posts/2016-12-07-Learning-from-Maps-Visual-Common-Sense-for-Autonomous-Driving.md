---
layout: post
title: "Learning from Maps: Visual Common Sense for Autonomous Driving"
date: 2016-12-07 22:24:52
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Ari Seff, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
Today's autonomous vehicles rely extensively on high-definition 3D maps to navigate the environment. While this approach works well when these maps are completely up-to-date, safe autonomous vehicles must be able to corroborate the map's information via a real time sensor-based system. Our goal in this work is to develop a model for road layout inference given imagery from on-board cameras, without any reliance on high-definition maps. However, no sufficient dataset for training such a model exists. Here, we leverage the availability of standard navigation maps and corresponding street view images to construct an automatically labeled, large-scale dataset for this complex scene understanding problem. By matching road vectors and metadata from navigation maps with Google Street View images, we can assign ground truth road layout attributes (e.g., distance to an intersection, one-way vs. two-way street) to the images. We then train deep convolutional networks to predict these road layout attributes given a single monocular RGB image. Experimental evaluation demonstrates that our model learns to correctly infer the road attributes using only panoramas captured by car-mounted cameras as input. Additionally, our results indicate that this method may be suitable to the novel application of recommending safety improvements to infrastructure (e.g., suggesting an alternative speed limit for a street).

##### Abstract (translated by Google)
今天的自主车辆广泛依靠高清3D地图来导航环境。虽然这种方法在这些地图是完全最新的时候效果很好，但是安全自主车辆必须能够通过基于实时传感器的系统来证实地图的信息。我们在这项工作中的目标是开发一个模型的道路布局推断给出的相机上的图像，而不依赖于高清晰度地图。但是，没有足够的数据集来训练这样的模型。在这里，我们利用标准导航地图和相应的街景视图图像的可用性，为这个复杂的场景理解问题构建一个自动标记的大规模数据集。通过将导航地图中的道路矢量和元数据与Google街景视图图像进行匹配，我们可以为图像分配地面道路布局属性（例如，到路口的距离，单向路径或双向街道）。然后，我们训练深卷积网络来预测这些道路布局属性给定一个单一的单目RGB图像。实验评估表明，我们的模型学习只使用车载摄像头拍摄的全景作为输入正确推断道路属性。此外，我们的研究结果表明，这种方法可能适用于向基础设施推荐安全改进的新颖应用（例如，建议替代的街道速度限制）。

##### URL
[https://arxiv.org/abs/1611.08583](https://arxiv.org/abs/1611.08583)

##### PDF
[https://arxiv.org/pdf/1611.08583](https://arxiv.org/pdf/1611.08583)

