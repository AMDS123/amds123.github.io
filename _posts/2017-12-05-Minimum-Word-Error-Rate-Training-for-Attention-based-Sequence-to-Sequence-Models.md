---
layout: post
title: "Minimum Word Error Rate Training for Attention-based Sequence-to-Sequence Models"
date: 2017-12-05 18:52:18
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Rohit Prabhavalkar, Tara N. Sainath, Yonghui Wu, Patrick Nguyen, Zhifeng Chen, Chung-Cheng Chiu, Anjuli Kannan
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models, such as attention-based models in automatic speech recognition (ASR), are typically trained to optimize the cross-entropy criterion which corresponds to improving the log-likelihood of the data. However, system performance is usually measured in terms of word error rate (WER), not log-likelihood. Traditional ASR systems benefit from discriminative sequence training which optimizes criteria such as the state-level minimum Bayes risk (sMBR) which are more closely related to WER. In the present work, we explore techniques to train attention-based models to directly minimize expected word error rate. We consider two loss functions which approximate the expected number of word errors: either by sampling from the model, or by using N-best lists of decoded hypotheses, which we find to be more effective than the sampling-based method. In experimental evaluations, we find that the proposed training procedure improves performance by up to 8.2% relative to the baseline system. This allows us to train grapheme-based, uni-directional attention-based models which match the performance of a traditional, state-of-the-art, discriminative sequence-trained system on a mobile voice-search task.

##### Abstract (translated by Google)
通常训练序列 - 序列模型（例如自动语音识别（ASR）中的基于注意力的模型）以优化对应于改善数据的对数似然性的交叉熵标准。但是，系统性能通常以字错误率（WER）而不是对数似然来衡量。传统的ASR系统受益于区分序列训练，该训练优化了与WER更密切相关的状态最小贝叶斯风险（sMBR）等标准。在目前的工作中，我们探索技术来训练基于注意力的模型，以直接最小化预期的错误率。我们考虑两个损失函数，这些函数接近预期的单词错误的数量：或者从模型中抽样，或者使用解码假设的N个最佳列表，我们发现它比基于抽样的方法更有效。在实验评估中，我们发现，相对于基准系统，所提出的训练过程将性能提高了8.2％。这使我们能够在移动语音搜索任务上训练基于字形的，单向的基于注意的模型，该模型与传统的，最先进的，区分性序列训练系统的性能相匹配。

##### URL
[http://arxiv.org/abs/1712.01818](http://arxiv.org/abs/1712.01818)

##### PDF
[http://arxiv.org/pdf/1712.01818](http://arxiv.org/pdf/1712.01818)

