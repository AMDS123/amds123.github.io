---
layout: post
title: "Evaluating Robustness of Neural Networks with Mixed Integer Programming"
date: 2018-06-11 17:41:34
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Vincent Tjeng, Kai Xiao, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks have demonstrated considerable success on a wide variety of real-world problems. However, networks trained only to optimize for training accuracy can often be fooled by adversarial examples - slightly perturbed inputs that are misclassified with high confidence. Verification of networks enables us to gauge their vulnerability to such adversarial examples. We formulate verification of piecewise-linear neural networks as a mixed integer program. On a representative task of finding minimum adversarial distortions, our verifier is two to three orders of magnitude quicker than the state-of-the-art. We achieve this computational speedup via tight formulations for non-linearities, as well as a novel presolve algorithm that makes full use of all information available. The computational speedup allows us to verify properties on convolutional networks with an order of magnitude more ReLUs than networks previously verified by any complete verifier. In particular, we determine for the first time the exact adversarial accuracy of an MNIST classifier to perturbations with bounded $l_\infty$ norm $\epsilon=0.1$: for this classifier, we find an adversarial example for 4.38% of samples, and a certificate of robustness (to perturbations with bounded norm) for the remainder. Across all robust training procedures and network architectures considered, we are able to certify more samples than the state-of-the-art and find more adversarial examples than a strong first-order attack.

##### Abstract (translated by Google)
神经网络在各种现实世界的问题上已经取得了相当大的成功。然而，训练仅训练精度优化的网络往往可能被敌对的例子迷惑 - 微扰的输入被高度置信地错误分类。网络的验证使我们能够评估它们对这种对抗性例子的脆弱性。我们将验证分段线性神经网络作为混合整数程序。在寻找最小对抗性失真的代表性任务中，我们的验证器比现有技术快2-3个数量级。我们通过用于非线性的紧配方实现了这种计算加速，以及充分利用所有可用信息的新型预求解算法。计算加速允许我们验证卷积网络上的属性，其数量级比先前由任何完整验证者验证的网络多得多。特别是，我们首次确定了MNIST分类器对有界$ l_ \ infty $ norm $ \ epsilon = 0.1 $的干扰的精确对抗精度：对于这个分类器，我们找到了4.38％样本的对抗示例，并且其余部分的鲁棒性证书（对有界标准的扰动）。在考虑所有强大的培训程序和网络体系结构时，我们能够证明比最先进的技术更多的样本，并找到比强烈的一阶攻击更多的对抗性例子。

##### URL
[http://arxiv.org/abs/1711.07356](http://arxiv.org/abs/1711.07356)

##### PDF
[http://arxiv.org/pdf/1711.07356](http://arxiv.org/pdf/1711.07356)

