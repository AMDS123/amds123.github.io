---
layout: post
title: "YellowFin and the Art of Momentum Tuning"
date: 2018-02-14 20:46:23
categories: arXiv_AI
tags: arXiv_AI RNN Deep_Learning Language_Model Recognition
author: Jian Zhang, Ioannis Mitliagkas
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperparameter tuning is one of the most time-consuming workloads in deep learning. State-of-the-art optimizers, such as AdaGrad, RMSProp and Adam, reduce this labor by adaptively tuning an individual learning rate for each variable. Recently researchers have shown renewed interest in simpler methods like momentum SGD as they may yield better test metrics. Motivated by this trend, we ask: can simple adaptive methods based on SGD perform as well or better? We revisit the momentum SGD algorithm and show that hand-tuning a single learning rate and momentum makes it competitive with Adam. We then analyze its robustness to learning rate misspecification and objective curvature variation. Based on these insights, we design YellowFin, an automatic tuner for momentum and learning rate in SGD. YellowFin optionally uses a negative-feedback loop to compensate for the momentum dynamics in asynchronous settings on the fly. We empirically show that YellowFin can converge in fewer iterations than Adam on ResNets and LSTMs for image recognition, language modeling and constituency parsing, with a speedup of up to 3.28x in synchronous and up to 2.69x in asynchronous settings.

##### Abstract (translated by Google)
超参数调整是深度学习中最耗时的工作量之一。 AdaGrad，RMSProp和Adam等最先进的优化器通过自适应地调整每个变量的单独学习速率来减少这种工作量。最近，研究人员重新关注更简单的方法，如动量SGD，因为它们可能产生更好的测试指标。受这种趋势的驱动，我们问：基于SGD的简单自适应方法可以表现得好还是更好？我们重温动量SGD算法，并显示手动调整单个学习速率和动量使其与Adam竞争。然后我们分析它对学习速率错误指定和目标曲率变化的鲁棒性。基于这些见解，我们设计了YellowFin，一种自动调谐器，用于动量和SGD的学习率。 YellowFin可选择使用负反馈回路来动态补偿异步设置中的动量动态。我们凭经验证明，YellowFin可以在迭代次数上比ResNets和LSTM在迭代次数更少，用于图像识别，语言建模和选区分析，同步时加速比率高达3.28倍，异步设置时高达2.69倍。

##### URL
[http://arxiv.org/abs/1706.03471](http://arxiv.org/abs/1706.03471)

##### PDF
[http://arxiv.org/pdf/1706.03471](http://arxiv.org/pdf/1706.03471)

