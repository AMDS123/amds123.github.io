---
layout: post
title: "Benefits of Depth for Long-Term Memory of Recurrent Networks"
date: 2017-10-25 19:34:33
categories: arXiv_CV
tags: arXiv_CV CNN RNN Relation
author: Yoav Levine, Or Sharir, Amnon Shashua
mathjax: true
---

* content
{:toc}

##### Abstract
The key attribute that drives the unprecedented success of modern Recurrent Neural Networks (RNNs) on learning tasks which involve sequential data, is their ever-improving ability to model intricate long-term temporal dependencies. However, an adequate measure of RNNs long-term memory capacity is lacking, and thus formal understanding of their ability to correlate data throughout time is limited. Though depth efficiency in convolutional networks is well established, it does not suffice in order to account for the success of deep RNNs on data of varying lengths, and the need to address their `time-series expressive power' arises. In this paper, we analyze the effect of depth on the ability of recurrent networks to express correlations ranging over long time-scales. To meet the above need, we introduce a measure of the information flow across time supported by the network, referred to as the Start-End separation rank. This measure essentially reflects the distance of the function realized by the recurrent network from a function that models no interaction whatsoever between the beginning and end of the input sequence. We prove that deep recurrent networks support Start-End separation ranks which are exponentially higher than those supported by their shallow counterparts. Thus, we establish that depth brings forth an overwhelming advantage in the ability of recurrent networks to model long-term dependencies. Such analyses may be readily extended to other RNN architectures of interest, e.g. variants of LSTM networks. We obtain our results by considering a class of recurrent networks referred to as Recurrent Arithmetic Circuits (RACs), which merge the hidden state with the input via the Multiplicative Integration operation. Finally, we make use of the tool of quantum Tensor Networks to gain additional graphic insight regarding the complexity brought forth by depth in recurrent networks.

##### Abstract (translated by Google)
推动现代递归神经网络（RNN）在涉及顺序数据的学习任务方面取得前所未有的成功的关键因素是它们不断提高的模拟复杂的长期时间依赖性的能力。然而，RNN的长期记忆能力缺乏足够的衡量标准，因此正式理解它们在整个时间内关联数据的能力是有限的。尽管卷积网络中的深度效率已经确立，但是为了说明深度RNN对不同长度的数据的成功是不够的，并且需要解决它们的“时间序列表达能力”。在本文中，我们分析深度对经常性网络在长时间尺度上表达相关性的能力的影响。为了满足上述需求，我们引入了网络支持的跨时间信息流度量，称为起始 - 终止分离度。这个度量基本上反映了由循环网络实现的函数与一个函数的距离，该函数在输入序列的开始和结束之间不产生任何交互。我们证明，深度经常性网络支持起始和终止的分离等级，其指数级高于其浅层支持者。因此，我们确定这个深度在循环网络模拟长期依赖的能力方面带来了压倒性的优势。这样的分析可以容易地扩展到感兴趣的其他RNN体系结构， LSTM网络的变种。我们通过考虑一类被称为经常性算术电路（RAC）的循环网络来获得我们的结果，所述经常性算术电路（RAC）通过乘法积分操作将隐藏状态与输入合并。最后，我们利用量子张量网络的工具来获得关于复杂网络深度复杂性的更多图形洞察。

##### URL
[https://arxiv.org/abs/1710.09431](https://arxiv.org/abs/1710.09431)

##### PDF
[https://arxiv.org/pdf/1710.09431](https://arxiv.org/pdf/1710.09431)

