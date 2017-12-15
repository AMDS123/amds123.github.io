---
layout: post
title: "meProp: Sparsified Back Propagation for Accelerated Deep Learning with Reduced Overfitting"
date: 2017-10-31 02:04:52
categories: arXiv_CL
tags: arXiv_CL Deep_Learning
author: Xu Sun, Xuancheng Ren, Shuming Ma, Houfeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple yet effective technique for neural network learning. The forward propagation is computed as usual. In back propagation, only a small subset of the full gradient is computed to update the model parameters. The gradient vectors are sparsified in such a way that only the top-$k$ elements (in terms of magnitude) are kept. As a result, only $k$ rows or columns (depending on the layout) of the weight matrix are modified, leading to a linear reduction ($k$ divided by the vector dimension) in the computational cost. Surprisingly, experimental results demonstrate that we can update only 1--4\% of the weights at each back propagation pass. This does not result in a larger number of training iterations. More interestingly, the accuracy of the resulting models is actually improved rather than degraded, and a detailed analysis is given. The code is available at this https URL

##### Abstract (translated by Google)
我们提出了一个简单而有效的神经网络学习技术。正向传播如常计算。在反向传播中，只计算完整梯度的一小部分来更新模型参数。梯度向量以这种方式稀疏，只保留顶部$ k $元素（以数量级）。结果，只有权重矩阵的$ k $行或列（取决于布局）被修改，导致计算成本中的线性减少（$ k $除以矢量维）。令人惊讶的是，实验结果表明，我们只能更新每个后向传播路径权重的1--4％。这不会导致大量的训练迭代。更有意思的是，所得模型的准确性实际上是提高了而不是降低了，并给出了详细的分析。该代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1706.06197](https://arxiv.org/abs/1706.06197)

##### PDF
[https://arxiv.org/pdf/1706.06197](https://arxiv.org/pdf/1706.06197)

