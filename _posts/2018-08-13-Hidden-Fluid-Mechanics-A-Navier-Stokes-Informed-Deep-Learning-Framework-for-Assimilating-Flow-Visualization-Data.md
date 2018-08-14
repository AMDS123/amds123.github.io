---
layout: post
title: "Hidden Fluid Mechanics: A Navier-Stokes Informed Deep Learning Framework for Assimilating Flow Visualization Data"
date: 2018-08-13 16:37:56
categories: arXiv_AI
tags: arXiv_AI Deep_Learning Prediction Quantitative
author: Maziar Raissi, Alireza Yazdani, George Em Karniadakis
mathjax: true
---

* content
{:toc}

##### Abstract
We present hidden fluid mechanics (HFM), a physics informed deep learning framework capable of encoding an important class of physical laws governing fluid motions, namely the Navier-Stokes equations. In particular, we seek to leverage the underlying conservation laws (i.e., for mass, momentum, and energy) to infer hidden quantities of interest such as velocity and pressure fields merely from spatio-temporal visualizations of a passive scaler (e.g., dye or smoke), transported in arbitrarily complex domains (e.g., in human arteries or brain aneurysms). Our approach towards solving the aforementioned data assimilation problem is unique as we design an algorithm that is agnostic to the geometry or the initial and boundary conditions. This makes HFM highly flexible in choosing the spatio-temporal domain of interest for data acquisition as well as subsequent training and predictions. Consequently, the predictions made by HFM are among those cases where a pure machine learning strategy or a mere scientific computing approach simply cannot reproduce. The proposed algorithm achieves accurate predictions of the pressure and velocity fields in both two and three dimensional flows for several benchmark problems motivated by real-world applications. Our results demonstrate that this relatively simple methodology can be used in physical and biomedical problems to extract valuable quantitative information (e.g., lift and drag forces or wall shear stresses in arteries) for which direct measurements may not be possible.

##### Abstract (translated by Google)
我们提出了隐藏流体力学（HFM），这是一种物理知识深度学习框架，能够编码控制流体运动的一类重要物理定律，即Navier-Stokes方程。特别是，我们寻求利用潜在的守恒定律（即质量，动量和能量）来推断隐藏的感兴趣量，例如速度和压力场，仅仅来自被动定标器的时空可视化（例如，染料或烟雾） ），在任意复杂的领域（例如，在人类动脉或脑动脉瘤中）运输。我们解决上述数据同化问题的方法是独特的，因为我们设计了一种与几何或初始和边界条件无关的算法。这使得HFM在选择感兴趣的时空域以及随后的训练和预测方面具有高度灵活性。因此，HFM的预测属于纯机器学习策略或仅仅是科学计算方法无法再现的情况。所提出的算法实现了对二维和三维流中的压力和速度场的精确预测，以用于由现实世界应用驱动的若干基准问题。我们的结果表明，这种相对简单的方法可用于物理和生物医学问题，以提取有价值的定量信息（例如，动脉中的升力和阻力或壁剪切应力），对于这些信息，可能无法进行直接测量。

##### URL
[http://arxiv.org/abs/1808.04327](http://arxiv.org/abs/1808.04327)

##### PDF
[http://arxiv.org/pdf/1808.04327](http://arxiv.org/pdf/1808.04327)

