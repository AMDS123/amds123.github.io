---
layout: post
title: "Towards the first adversarially robust neural network model on MNIST"
date: 2018-08-30 17:18:50
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Lukas Schott, Jonas Rauber, Matthias Bethge, Wieland Brendel
mathjax: true
---

* content
{:toc}

##### Abstract
Despite much effort, deep neural networks remain highly susceptible to tiny input perturbations and even for MNIST, one of the most common toy datasets in computer vision, no neural network model exists for which the adversarial perturbations are large and make semantic sense to humans. We show that the widely recognized and by far most successful defense by Madry et al. (1) overfits on the L-infinity metric (it's highly susceptibility to L2 and L0 perturbations), (2) a simple defense based on binarization performs almost as well and (3) its adversarial perturbations make little sense to humans. These results suggest that MNIST is far from being solved in terms of adversarial robustness. We present a novel approach that performs analysis by synthesis using learned class-conditional data distributions. We go to great length to empirically evaluate our model using maximally effective adversarial attacks by (a) applying decision-based, score-based, gradient-based and transfer-based attacks for several different Lp norms, (b) by designing a new attack that exploits the structure of our defended model and (c) by devising a novel decision-based attack that seeks to minimize the number of perturbed pixels (L0). The results suggest that this approach yields state-of-the-art robustness on MNIST against L0, L2 and L-infinity perturbations and we demonstrate that most adversarial examples are strongly perturbed towards the perceptual boundary between the original and the adversarial class.

##### Abstract (translated by Google)
尽管付出了很多努力，深度神经网络仍然非常容易受到微小输入扰动的影响，甚至对于计算机视觉中最常见的玩具数据集之一MNIST，也没有神经网络模型存在，其对抗性扰动很大并且对人类具有语义意义。我们展示了Madry等人广泛认可和最成功的防御。 （1）对L-infinity度量的过度拟合（它对L2和L0扰动的高度敏感性），（2）基于二值化的简单防御几乎同样如此，并且（3）其对抗性扰动对人类没有多大意义。这些结果表明MNIST在对抗鲁棒性方面远未得到解决。我们提出了一种新方法，使用学习的类条件数据分布通过综合进行分析。我们通过（a）对几种不同的Lp规范应用基于决策，基于分数，基于梯度和基于转移的攻击，（）通过设计新攻击，使用最有效的对抗性攻击来经验性地评估我们的模型。利用我们的防御模型的结构和（c）设计一种新的基于决策的攻击，寻求最小化扰动像素的数量（L0）。结果表明，这种方法在MNIST上对L0，L2和L-无穷大扰动产生了最先进的鲁棒性，并且我们证明了大多数对抗性例子对原始类和对抗类之间的感知边界强烈不安。

##### URL
[http://arxiv.org/abs/1805.09190](http://arxiv.org/abs/1805.09190)

##### PDF
[http://arxiv.org/pdf/1805.09190](http://arxiv.org/pdf/1805.09190)

