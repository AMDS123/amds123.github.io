---
layout: post
title: "The exploding gradient problem demystified - definition, prevalence, impact, origin, tradeoffs, and solutions"
date: 2018-03-21 17:12:48
categories: arXiv_CV
tags: arXiv_CV
author: George Philipp, Dawn Song, Jaime G. Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Whereas it is believed that techniques such as Adam, batch normalization and, more recently, SeLU nonlinearities "solve" the exploding gradient problem, we show that this is not the case in general and that in a range of popular MLP architectures, exploding gradients exist and that they limit the depth to which networks can be effectively trained, both in theory and in practice. We explain why exploding gradients occur and highlight the *collapsing domain problem*, which can arise in architectures that avoid exploding gradients. 
 ResNets have significantly lower gradients and thus can circumvent the exploding gradient problem, enabling the effective training of much deeper networks. We show this is a direct consequence of the Pythagorean equation. By noticing that *any neural network is a residual network*, we devise the *residual trick*, which reveals that introducing skip connections simplifies the network mathematically, and that this simplicity may be the major cause for their success.

##### Abstract (translated by Google)
尽管相信诸如亚当，批量归一化和最近的SeLU非线性技术“解决”爆炸梯度问题的技术，但是我们表明这不是一般情况，并且在一系列流行的MLP体系结构中存在爆炸梯度而且它们限制了网络在理论和实践中都可以得到有效训练的深度。我们解释了为什么会出现爆炸渐变并突出显示*崩溃域问题*，这可能会导致在避免爆炸梯度的体系结构中出现。
 ResNets具有显着较低的梯度，因此可以规避爆炸梯度问题，从而可以对更深层次的网络进行有效的培训。我们证明这是毕达哥拉斯方程的直接后果。通过注意到*任何神经网络都是一个残余网络*，我们设计*残留技巧*，这表明引入跳过连接从数学上简化了网络，并且这种简单性可能是他们成功的主要原因。

##### URL
[http://arxiv.org/abs/1712.05577](http://arxiv.org/abs/1712.05577)

##### PDF
[http://arxiv.org/pdf/1712.05577](http://arxiv.org/pdf/1712.05577)

