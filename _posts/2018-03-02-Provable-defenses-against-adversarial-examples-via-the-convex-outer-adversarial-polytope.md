---
layout: post
title: "Provable defenses against adversarial examples via the convex outer adversarial polytope"
date: 2018-03-02 00:41:56
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Optimization
author: Eric Wong, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method to learn deep ReLU-based classifiers that are provably robust against norm-bounded adversarial perturbations on the training data. For previously unseen examples, the approach is guaranteed to detect all adversarial examples, though it may flag some non-adversarial examples as well. The basic idea is to consider a convex outer approximation of the set of activations reachable through a norm-bounded perturbation, and we develop a robust optimization procedure that minimizes the worst case loss over this outer region (via a linear program). Crucially, we show that the dual problem to this linear program can be represented itself as a deep network similar to the backpropagation network, leading to very efficient optimization approaches that produce guaranteed bounds on the robust loss. The end result is that by executing a few more forward and backward passes through a slightly modified version of the original network (though possibly with much larger batch sizes), we can learn a classifier that is provably robust to any norm-bounded adversarial attack. We illustrate the approach on a number of tasks to train classifiers with robust adversarial guarantees (e.g. for MNIST, we produce a convolutional classifier that provably has less than 5.8% test error for any adversarial attack with bounded $\ell_\infty$ norm less than $\epsilon = 0.1$). Code for all experiments in the paper is available at https://github.com/locuslab/convex_adversarial.

##### Abstract (translated by Google)
我们提出了一种方法来学习基于深度的基于ReLU的分类器，该分类器对于训练数据上的范数有界对抗干扰是可证明的。对于以前看不见的例子，这种方法可以保证检测到所有敌对的例子，但它也可能标记一些非对抗性的例子。基本思想是考虑通过范数有界扰动可达到的激活集的凸外部近似，并且我们开发一个稳健的优化程序，以最小化该外部区域上的最坏情况损失（通过线性程序）。至关重要的是，我们表明，这个线性规划的对偶问题可以表示为一个类似于反向传播网络的深层网络，从而产生非常有效的优化方法，从而对鲁棒损失产生保证界限。最终的结果是，通过稍微修改版本的原始网络（尽管可能有更大的批量大小）执行更多的前向和后向传递，我们可以学习一个分类器，该分类器对于任何范数有界的对抗攻击都是可靠的。我们举例说明了一些训练具有强大对抗性保证的分类器的任务的方法（例如，对于MNIST，我们产生了一个卷积分类器，对于任何有限的$ \ ell_ \ infty $范数小于5的敌对攻击，测试误差可证明小于5.8％ $ \ epsilon = 0.1 $）。 https://github.com/locuslab/convex_adversarial提供了论文中所有实验的代码。

##### URL
[http://arxiv.org/abs/1711.00851](http://arxiv.org/abs/1711.00851)

##### PDF
[http://arxiv.org/pdf/1711.00851](http://arxiv.org/pdf/1711.00851)

