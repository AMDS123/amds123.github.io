---
layout: post
title: "NISP: Pruning Networks using Neuron Importance Score Propagation"
date: 2017-11-17 14:47:14
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Ruichi Yu, Ang Li, Chun-Fu Chen, Jui-Hsin Lai, Vlad I. Morariu, Xintong Han, Mingfei Gao, Ching-Yung Lin, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
To reduce the significant redundancy in deep Convolutional Neural Networks (CNNs), most existing methods prune neurons by only considering statistics of an individual layer or two consecutive layers (e.g., prune one layer to minimize the reconstruction error of the next layer), ignoring the effect of error propagation in deep networks. In contrast, we argue that it is essential to prune neurons in the entire neuron network jointly based on a unified goal: minimizing the reconstruction error of important responses in the "final response layer" (FRL), which is the second-to-last layer before classification, for a pruned network to retrain its predictive power. Specifically, we apply feature ranking techniques to measure the importance of each neuron in the FRL, and formulate network pruning as a binary integer optimization problem and derive a closed-form solution to it for pruning neurons in earlier layers. Based on our theoretical analysis, we propose the Neuron Importance Score Propagation (NISP) algorithm to propagate the importance scores of final responses to every neuron in the network. The CNN is pruned by removing neurons with least importance, and then fine-tuned to retain its predictive power. NISP is evaluated on several datasets with multiple CNN models and demonstrated to achieve significant acceleration and compression with negligible accuracy loss.

##### Abstract (translated by Google)
为了减少深度卷积神经网络（CNN）中的显着冗余，大多数现有方法仅通过考虑单个层或两个连续层的统计（例如，修剪一层以最小化下一层的重构误差）来修剪神经元，忽略误差传播在深度网络中的作用。相反，我们认为，根据一个统一的目标，在整个神经元网络中共同修剪神经元至关重要：最小化“最终响应层”（FRL）中重要响应的重构误差，这是倒数第二个分层之前，为了修剪网络重新训练其预测能力。具体来说，我们应用特征排序技术来测量每个神经元在FRL中的重要性，并将网络修剪形成为二进制整数优化问题，并推导出闭合形式的解决方案，以修剪早期的神经元层。在理论分析的基础上，提出神经元重要性评分传播（NISP）算法，将网络中每个神经元的最终响应重要性分数传播。 CNN通过去除最不重要的神经元来修剪，然后进行微调以保持其预测能力。 NISP在具有多个CNN模型的多个数据集上进行评估，并且被证明能够实现显着的加速度和压缩，精度损失可以忽略不计。

##### URL
[https://arxiv.org/abs/1711.05908](https://arxiv.org/abs/1711.05908)

##### PDF
[https://arxiv.org/pdf/1711.05908](https://arxiv.org/pdf/1711.05908)

