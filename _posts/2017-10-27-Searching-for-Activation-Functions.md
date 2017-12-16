---
layout: post
title: "Searching for Activation Functions"
date: 2017-10-27 17:45:21
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Classification
author: Prajit Ramachandran, Barret Zoph, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
The choice of activation functions in deep networks has a significant effect on the training dynamics and task performance. Currently, the most successful and widely-used activation function is the Rectified Linear Unit (ReLU). Although various hand-designed alternatives to ReLU have been proposed, none have managed to replace it due to inconsistent gains. In this work, we propose to leverage automatic search techniques to discover new activation functions. Using a combination of exhaustive and reinforcement learning-based search, we discover multiple novel activation functions. We verify the effectiveness of the searches by conducting an empirical evaluation with the best discovered activation function. Our experiments show that the best discovered activation function, $f(x) = x \cdot \text{sigmoid}(\beta x)$, which we name Swish, tends to work better than ReLU on deeper models across a number of challenging datasets. For example, simply replacing ReLUs with Swish units improves top-1 classification accuracy on ImageNet by 0.9\% for Mobile NASNet-A and 0.6\% for Inception-ResNet-v2. The simplicity of Swish and its similarity to ReLU make it easy for practitioners to replace ReLUs with Swish units in any neural network.

##### Abstract (translated by Google)
深度网络中激活函数的选择对训练动态和任务性能有显着的影响。目前，最成功和广泛使用的激活功能是整流线性单元（ReLU）。尽管已经提出了各种手工设计的ReLU替代方案，但由于收益不一致，没有人设法取代它。在这项工作中，我们建议利用自动搜索技术来发现新的激活功能。结合使用穷举和强化学习的搜索，我们发现了多种新颖的激活函数。我们通过最佳发现的激活函数进行实证评估来验证搜索的有效性。我们的实验显示，我们命名为Swish的最好发现的激活函数往往比ReLU在更深入的模型上工作得更好，数据集。例如，简单地用Swish单元代替ReLUs，对于移动NASNet-A来说，ImageNet的分类精度提高了1分之1，对于Inception-ResNet-v2，分类精度提高了0.6％。 Swish的简单性及其与ReLU的相似性使得从业者可以很容易地用任何神经网络中的Swish单元代替ReLUs。

##### URL
[https://arxiv.org/abs/1710.05941](https://arxiv.org/abs/1710.05941)

##### PDF
[https://arxiv.org/pdf/1710.05941](https://arxiv.org/pdf/1710.05941)

