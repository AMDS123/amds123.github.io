---
layout: post
title: "Gradients explode - Deep Networks are shallow - ResNet explained"
date: 2017-12-15 08:25:51
categories: arXiv_CV
tags: arXiv_CV
author: George Philipp, Dawn Song, Jaime G. Carbonell
mathjax: true
---

* content
{:toc}

##### Abstract
Whereas it is believed that techniques such as Adam, batch normalization and, more recently, SeLU nonlinearities "solve" the exploding gradient problem, we show that this is not the case in general and that in a range of popular MLP architectures, exploding gradients exist and that they limit the depth to which networks can be effectively trained, both in theory and in practice. We explain why exploding gradients occur and highlight the *collapsing domain problem*, which can arise in architectures that avoid exploding gradients. 
 ResNets have significantly lower gradients and thus can circumvent the exploding gradient problem, enabling the effective training of much deeper networks, which we show is a consequence of a surprising mathematical property. By noticing that *any neural network is a residual network*, we devise the *residual trick*, which reveals that introducing skip connections simplifies the network mathematically, and that this simplicity may be the major cause for their success.

##### Abstract (translated by Google)
尽管相信诸如亚当，批量归一化和最近的SeLU非线性技术“解决”爆炸梯度问题的技术，但是我们证明这不是一般情况，并且在一系列流行的MLP体系结构中存在爆炸梯度而且它们限制了网络在理论和实践上都可以得到有效训练的深度。我们解释为什么会出现爆炸渐变，并突出显示*崩溃域问题*，这可能会出现在避免爆炸梯度的体系结构中。
 ResNets具有明显较低的梯度，因此可以规避爆炸的梯度问题，从而能够对更深层的网络进行有效的训练，我们展示的是一个令人惊讶的数学属性的结果。通过注意到*任何神经网络是残余网络*，我们设计*残留技巧*，这表明引入跳过连接简化了网络的数学运算，而这种简单性可能是他们成功的主要原因。

##### URL
[http://arxiv.org/abs/1712.05577](http://arxiv.org/abs/1712.05577)

##### PDF
[http://arxiv.org/pdf/1712.05577](http://arxiv.org/pdf/1712.05577)

