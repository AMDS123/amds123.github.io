---
layout: post
title: "Metric-Driven Learning of Correspondence Weighting for 2-D/3-D Image Registration"
date: 2018-06-20 16:02:27
categories: arXiv_CV
tags: arXiv_CV
author: Roman Schaffert, Jian Wang, Peter Fischer, Anja Borsdorf, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Registration for pre-operative 3-D images to intra-operative 2-D fluoroscopy images is important in minimally invasive procedures. Registration can be intuitively performed by estimating the global rigidbody motion with constraints of minimizing local misalignments. However, inaccurate local correspondences challenge the registration performance. We use PointNet to estimate the optimal weights of local correspondences. We train the network directly with the criterion to minimize the registration error. For that, we propose an objective function which incorporates point-to-plane motion estimation and projection error computation. Thereby, we enable the learning of a correspondence weighting strategy which optimally fits the underlying formulation of the registration problem in an end-to-end fashion. In the evaluation of single-vertebra registration, we demonstrate an accuracy of 0.74$\pm$0.26 mm of our method and a highly improved robustness, increasing the success rate from 79.3 % to 94.3 % and the capture range from 3 mm to 13 mm.

##### Abstract (translated by Google)
手术前3D图像注册到术中2-D荧光透视图像在微创手术中很重要。通过在最大程度减少局部误差的情况下通过估计全局刚体运动可以直观地进行配准。然而，不准确的地方信函会对注册表现提出质疑。我们使用PointNet来估计本地通信的最佳权重。我们直接用准则来训练网络，以最大限度地减少注册错误。为此，我们提出了一个包含点对平面运动估计和投影误差计算的目标函数。因此，我们能够学习对应性加权策略，以端到端的方式最优地拟合注册问题的基本表述。在评估单椎体配准时，我们证明了我们的方法的准确性为0.74美元/分钟和0.26美元，并且鲁棒性大大提高，成功率从79.3％提高到94.3％，捕获范围从3毫米增加到13毫米。

##### URL
[http://arxiv.org/abs/1806.07812](http://arxiv.org/abs/1806.07812)

##### PDF
[http://arxiv.org/pdf/1806.07812](http://arxiv.org/pdf/1806.07812)

