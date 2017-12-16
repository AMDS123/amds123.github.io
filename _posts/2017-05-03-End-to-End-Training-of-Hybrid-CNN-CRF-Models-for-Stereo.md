---
layout: post
title: "End-to-End Training of Hybrid CNN-CRF Models for Stereo"
date: 2017-05-03 09:33:20
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Patrick Knöbelreiter, Christian Reinbacher, Alexander Shekhovtsov, Thomas Pock
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel and principled hybrid CNN+CRF model for stereo estimation. Our model allows to exploit the advantages of both, convolutional neural networks (CNNs) and conditional random fields (CRFs) in an unified approach. The CNNs compute expressive features for matching and distinctive color edges, which in turn are used to compute the unary and binary costs of the CRF. For inference, we apply a recently proposed highly parallel dual block descent algorithm which only needs a small fixed number of iterations to compute a high-quality approximate minimizer. As the main contribution of the paper, we propose a theoretically sound method based on the structured output support vector machine (SSVM) to train the hybrid CNN+CRF model on large-scale data end-to-end. Our trained models perform very well despite the fact that we are using shallow CNNs and do not apply any kind of post-processing to the final output of the CRF. We evaluate our combined models on challenging stereo benchmarks such as Middlebury 2014 and Kitti 2015 and also investigate the performance of each individual component.

##### Abstract (translated by Google)
我们提出了一种新颖有效的混合CNN + CRF模型用于立体声估计。我们的模型允许以统一的方式利用卷积神经网络（CNN）和条件随机场（CRF）两者的优点。 CNN计算用于匹配和独特色彩边缘的表现特征，其反过来用于计算CRF的一元和二元成本。为了推断，我们应用了最近提出的高度并行的双块下降算法，它只需要一个小的固定迭代次数来计算一个高质量的近似最小值。作为本文的主要贡献，本文提出了一种基于结构化输出支持向量机（SSVM）的理论上合理的方法来对大规模数据端到端的混合CNN + CRF模型进行训练。尽管我们正在使用浅CNN，并且不对CRF的最终产出进行任何形式的后处理，但我们训练有素的模型表现得非常好。我们在具有挑战性的立体声基准（如Middlebury 2014和Kitti 2015）上评估我们的组合模型，并调查每个组件的性能。

##### URL
[https://arxiv.org/abs/1611.10229](https://arxiv.org/abs/1611.10229)

##### PDF
[https://arxiv.org/pdf/1611.10229](https://arxiv.org/pdf/1611.10229)

