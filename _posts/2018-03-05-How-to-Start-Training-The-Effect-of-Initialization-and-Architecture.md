---
layout: post
title: "How to Start Training: The Effect of Initialization and Architecture"
date: 2018-03-05 15:17:50
categories: arXiv_AI
tags: arXiv_AI
author: Boris Hanin, David Rolnick
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the effects of initialization and architecture on the start of training in deep ReLU nets. We identify two common failure modes for early training in which the mean and variance of activations are poorly behaved. For each failure mode, we give a rigorous proof of when it occurs at initialization and how to avoid it. The first failure mode, exploding/vanishing mean activation length, can be avoided by initializing weights from a symmetric distribution with variance 2/fan-in. The second failure mode, exponentially large variance of activation length, can be avoided by keeping constant the sum of the reciprocals of layer widths. We demonstrate empirically the effectiveness of our theoretical results in predicting when networks are able to start training. In particular, we note that many popular initializations fail our criteria, whereas correct initialization and architecture allows much deeper networks to be trained.

##### Abstract (translated by Google)
我们调查初始化和体系结构对深度ReLU网络训练开始的影响。我们确定了早期训练的两种常见失效模式，其中激活的均值和方差表现不佳。对于每种故障模式，我们都会给出一个严格的证明，说明它在初始化时何时发生以及如何避免它。通过初始化方差为2 / fan-in的对称分布的权重，可以避免第一种失效模式，爆炸/消失平均激活长度。通过保持层宽倒数之和不变，可以避免第二失效模式，即激活长度的指数大变化。我们凭经验证明了我们的理论结果在预测网络何时能够开始训练方面的有效性。特别是，我们注意到很多流行的初始化不符合我们的标准，而正确的初始化和体系结构允许深度网络被训练。

##### URL
[http://arxiv.org/abs/1803.01719](http://arxiv.org/abs/1803.01719)

##### PDF
[http://arxiv.org/pdf/1803.01719](http://arxiv.org/pdf/1803.01719)

