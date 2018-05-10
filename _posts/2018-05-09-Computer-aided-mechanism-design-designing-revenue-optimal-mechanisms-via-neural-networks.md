---
layout: post
title: "Computer-aided mechanism design: designing revenue-optimal mechanisms via neural networks"
date: 2018-05-09 05:57:29
categories: arXiv_AI
tags: arXiv_AI Face
author: Weiran Shen, Pingzhong Tang, Song Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Using AI approaches to automatically design mechanisms has been a central research mission at the interface of AI and economics [Conitzer and Sandholm, 2002]. Previous approaches that a empt to design revenue optimal auctions for the multi-dimensional settings fall short in at least one of the three aspects: 1) representation --- search in a space that probably does not even contain the optimal mechanism; 2) exactness --- finding a mechanism that is either not truthful or far from optimal; 3) domain dependence --- need a different design for different environment settings. To resolve the three difficulties, in this paper, we put forward a uni ed neural network based framework that automatically learns to design revenue optimal mechanisms. Our framework consists of a mechanism network that takes an input distribution for training and outputs a mechanism, as well as a buyer network that takes a mechanism as input and output an action. Such a separation in design mitigates the difficulty to impose incentive compatibility constraints on the mechanism, by making it a rational choice of the buyer. As a result, our framework easily overcomes the previously mentioned difficulty in incorporating IC constraints and always returns exactly incentive compatible mechanisms. We then applied our framework to a number of multi-item revenue optimal design settings, for a few of which the theoretically optimal mechanisms are unknown. We then go on to theoretically prove that the mechanisms found by our framework are indeed optimal.

##### Abstract (translated by Google)
使用AI方法自动设计机制一直是人工智能和经济学界面的核心研究任务[Conitzer and Sandholm，2002]。以前的方法至少在三个方面中的一个方面不足以实现多维设置的设计收益最优拍卖：1）表示法 - 在可能甚至不包含最佳机制的空间中进行搜索; 2）正确性---找到一种不真实或远离最佳的机制; 3）域依赖性---针对不同的环境设置需要不同的设计。为了解决这三个难题，本文提出了一种基于统一神经网络的框架，自动学习设计收益最优机制。我们的框架由一个机制网络组成，这个网络需要一个输入分配用于训练并输出一个机制，以及一个采用机制作为输入和输出动作的买方网络。这种设计分离减轻了对机制施加激励相容性限制的困难，使其成为买方的理性选择。因此，我们的框架很容易克服前面提到的融合IC约束的困难，并始终返回完全激励兼容的机制。然后，我们将我们的框架应用于许多多项目收入优化设计设置，其中一些理论上最佳的机制是未知的。然后，我们继续理论上证明，我们的框架发现的机制确实是最佳的。

##### URL
[http://arxiv.org/abs/1805.03382](http://arxiv.org/abs/1805.03382)

##### PDF
[http://arxiv.org/pdf/1805.03382](http://arxiv.org/pdf/1805.03382)

