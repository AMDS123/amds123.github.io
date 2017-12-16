---
layout: post
title: "Loss-Sensitive Generative Adversarial Networks on Lipschitz Densities"
date: 2017-03-15 06:44:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Guo-Jun Qi
mathjax: true
---

* content
{:toc}

##### Abstract
*New Theory Result* We analyze the generalizability of the LS-GAN, showing that the loss function and generator trained over finite examples can converge to those learned from the real distributions with a moderate number of training examples. In this paper, we present a novel Loss-Sensitive GAN (LS-GAN) that learns a loss function to separate generated samples from their real examples. An important property of the LS-GAN is it allows the generator to focus on improving poor data points that are far apart from real examples rather than wasting efforts on those samples that have already been well generated, and thus can improve the overall quality of generated samples. The theoretical analysis also shows that the LS-GAN can generate samples following the true data density. In particular, we present a regularity condition on the underlying data density, which allows us to use a class of Lipschitz losses and generators to model the LS-GAN. It relaxes the assumption that the classic GAN should have infinite modeling capacity to obtain the similar theoretical guarantee. Furthermore, we show the generalization ability of the LS-GAN by bounding the difference between the model performances over the empirical and real distributions, as well as deriving a tractable sample complexity to train the LS-GAN model in terms of its generalization ability. We also derive a non-parametric solution that characterizes the upper and lower bounds of the losses learned by the LS-GAN, both of which are cone-shaped and have non-vanishing gradient almost everywhere.

##### Abstract (translated by Google)
*新的理论结果*我们分析LS-GAN的概括性，表明经过有限例证训练的损失函数和生成器可以用中等数量的训练例子收敛到从实际分布中学习到的损失函数和生成器。在本文中，我们提出了一种新型的损失敏感型GAN（LS-GAN），它学习了将生成的样本与其实例分离的损失函数。 LS-GAN的一个重要特性是它允许生成器专注于改进与实际示例相距甚远的不良数据点，而不是浪费已经很好生成的样本的努力，从而可以提高生成的总体质量样本。理论分析还表明，LS-GAN可以根据真实的数据密度生成样本。特别是，我们提出了基础数据密度的规律性条件，这使得我们可以使用一类Lipschitz损失和发生器来模拟LS-GAN。它放宽了经典GAN应具有无限建模能力的假设，以获得类似的理论保证。此外，我们通过将模型性能与经验分布和实际分布之间的差异进行界定，从而展示了LS-GAN的泛化能力，并从泛化能力的角度出发导出了一个易处理的样本复杂度来训练LS-GAN模型。我们也推导出一个非参数解，它表征了LS-GAN学习到的损失的上下限，两者都是锥形的，几乎在任何地方都有非零的渐变。

##### URL
[https://arxiv.org/abs/1701.06264](https://arxiv.org/abs/1701.06264)

##### PDF
[https://arxiv.org/pdf/1701.06264](https://arxiv.org/pdf/1701.06264)

