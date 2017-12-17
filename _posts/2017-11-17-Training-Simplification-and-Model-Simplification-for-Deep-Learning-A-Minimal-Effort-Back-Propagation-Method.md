---
layout: post
title: "Training Simplification and Model Simplification for Deep Learning: A Minimal Effort Back Propagation Method"
date: 2017-11-17 13:36:51
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Xu Sun, Xuancheng Ren, Shuming Ma, Bingzhen Wei, Wei Li, Houfeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple yet effective technique to simplify the training and the resulting model of neural networks. In back propagation, only a small subset of the full gradient is computed to update the model parameters. The gradient vectors are sparsified in such a way that only the top-$k$ elements (in terms of magnitude) are kept. As a result, only $k$ rows or columns (depending on the layout) of the weight matrix are modified, leading to a linear reduction in the computational cost. Based on the sparsified gradients, we further simplify the model by eliminating the rows or columns that are seldom updated, which will reduce the computational cost both in the training and decoding, and potentially accelerate decoding in real-world applications. Surprisingly, experimental results demonstrate that most of time we only need to update fewer than 5% of the weights at each back propagation pass. More interestingly, the accuracy of the resulting models is actually improved rather than degraded, and a detailed analysis is given. The model simplification results show that we could adaptively simplify the model which could often be reduced by around 9x, without any loss on accuracy or even with improved accuracy.

##### Abstract (translated by Google)
我们提出一个简单而有效的技术来简化训练和由此产生的神经网络模型。在反向传播中，只计算完整梯度的一小部分来更新模型参数。梯度向量以这种方式稀疏，只保留顶部$ k $元素（以数量级）。结果，权重矩阵只有$ k $行或列（取决于布局）被修改，导致计算成本的线性减少。基于稀疏梯度，我们通过消除很少更新的行或列来进一步简化模型，这将减少训练和解码中的计算成本，并且可能加速实际应用中的解码。令人惊讶的是，实验结果表明，大多数时候我们只需要在每个后向传播过程中更新少于5％的权重。更有意思的是，所得模型的准确性实际上是提高了而不是降低了，并给出了详细的分析。模型简化结果表明，我们可以自适应地简化通常可以减少9倍左右的模型，而不会造成精度损失，甚至提高精度。

##### URL
[https://arxiv.org/abs/1711.06528](https://arxiv.org/abs/1711.06528)

##### PDF
[https://arxiv.org/pdf/1711.06528](https://arxiv.org/pdf/1711.06528)

