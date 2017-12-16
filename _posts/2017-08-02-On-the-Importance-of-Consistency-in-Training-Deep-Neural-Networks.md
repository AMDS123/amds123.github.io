---
layout: post
title: "On the Importance of Consistency in Training Deep Neural Networks"
date: 2017-08-02 08:05:09
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Chengxi Ye, Yezhou Yang, Cornelia Fermuller, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
We explain that the difficulties of training deep neural networks come from a syndrome of three consistency issues. This paper describes our efforts in their analysis and treatment. The first issue is the training speed inconsistency in different layers. We propose to address it with an intuitive, simple-to-implement, low footprint second-order method. The second issue is the scale inconsistency between the layer inputs and the layer residuals. We explain how second-order information provides favorable convenience in removing this roadblock. The third and most challenging issue is the inconsistency in residual propagation. Based on the fundamental theorem of linear algebra, we provide a mathematical characterization of the famous vanishing gradient problem. Thus, an important design principle for future optimization and neural network design is derived. We conclude this paper with the construction of a novel contractive neural network.

##### Abstract (translated by Google)
我们解释说，训练深度神经网络的困难来自三个一致性问题的综合症。本文介绍了我们在分析和治疗方面的努力。第一个问题是不同层次的训练速度不一致。我们建议用直观，简单实施，低占位面积的二阶方法来解决这个问题。第二个问题是图层输入和图层残差之间的比例不一致。我们解释二阶信息如何为消除这个障碍提供有利的便利。第三个也是最具挑战性的问题是残差传播的不一致性。基于线性代数的基本定理，我们给出了着名的消失梯度问题的数学表征。因此，推导出未来优化和神经网络设计的一个重要设计原则。我们结束本文与建设一个新的收缩神经网络。

##### URL
[https://arxiv.org/abs/1708.00631](https://arxiv.org/abs/1708.00631)

##### PDF
[https://arxiv.org/pdf/1708.00631](https://arxiv.org/pdf/1708.00631)

