---
layout: post
title: "Integrated Inference and Learning of Neural Factors in Structural Support Vector Machines"
date: 2016-03-03 22:46:17
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference Prediction Gradient_Descent Relation Recognition
author: Rein Houthooft, Filip De Turck
mathjax: true
---

* content
{:toc}

##### Abstract
Tackling pattern recognition problems in areas such as computer vision, bioinformatics, speech or text recognition is often done best by taking into account task-specific statistical relations between output variables. In structured prediction, this internal structure is used to predict multiple outputs simultaneously, leading to more accurate and coherent predictions. Structural support vector machines (SSVMs) are nonprobabilistic models that optimize a joint input-output function through margin-based learning. Because SSVMs generally disregard the interplay between unary and interaction factors during the training phase, final parameters are suboptimal. Moreover, its factors are often restricted to linear combinations of input features, limiting its generalization power. To improve prediction accuracy, this paper proposes: (i) Joint inference and learning by integration of back-propagation and loss-augmented inference in SSVM subgradient descent; (ii) Extending SSVM factors to neural networks that form highly nonlinear functions of input features. Image segmentation benchmark results demonstrate improvements over conventional SSVM training methods in terms of accuracy, highlighting the feasibility of end-to-end SSVM training with neural factors.

##### Abstract (translated by Google)
在诸如计算机视觉，生物信息学，言语或文本识别等领域解决模式识别问题通常通过考虑输出变量之间的任务特定的统计关系来最好地完成。在结构化预测中，这种内部结构被用来同时预测多个输出，从而导致更准确和一致的预测。结构支持向量机（SSVMs）是非概率模型，通过基于边界的学习来优化联合投入产出函数。由于SSVM通常在训练阶段忽视一元和相互作用因素之间的相互作用，最终的参数是不理想的。而且，它的因素往往局限于输入特征的线性组合，限制了其泛化能力。为了提高预测精度，本文提出：（1）SSVM次梯度下降中的反向传播和丢失增强推理相结合的联合推理和学习; （ii）将SSVM因子扩展到形成输入特征的高度非线性函数的神经网络。图像分割基准测试结果表明，相对于传统的SSVM训练方法在精度方面有所改进，突出了用神经因素进行端到端SSVM训练的可行性。

##### URL
[https://arxiv.org/abs/1508.00451](https://arxiv.org/abs/1508.00451)

##### PDF
[https://arxiv.org/pdf/1508.00451](https://arxiv.org/pdf/1508.00451)

