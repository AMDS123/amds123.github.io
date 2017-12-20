---
layout: post
title: "Improving End-to-End Speech Recognition with Policy Learning"
date: 2017-12-19 18:39:50
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Classification Recognition
author: Yingbo Zhou, Caiming Xiong, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Connectionist temporal classification (CTC) is widely used for maximum likelihood learning in end-to-end speech recognition models. However, there is usually a disparity between the negative maximum likelihood and the performance metric used in speech recognition, e.g., word error rate (WER). This results in a mismatch between the objective function and metric during training. We show that the above problem can be mitigated by jointly training with maximum likelihood and policy gradient. In particular, with policy learning we are able to directly optimize on the (otherwise non-differentiable) performance metric. We show that joint training improves relative performance by 4% to 13% for our end-to-end model as compared to the same model learned through maximum likelihood. The model achieves 5.53% WER on Wall Street Journal dataset, and 5.42% and 14.70% on Librispeech test-clean and test-other set, respectively.

##### Abstract (translated by Google)
Connectionist时间分类（CTC）被广泛用于端对端语音识别模型中的最大似然学习。然而，在语音识别中所使用的负极大似然性和性能度量之间通常存在差异，例如字错误率（WER）。这导致训练期间目标函数和度量之间的不匹配。我们表明，上述问题可以通过最大可能性和政策梯度的联合训练来缓解。特别是通过政策学习，我们可以直接对（否则不可区分的）绩效指标进行优化。我们显示，与通过最大可能性学习的相同模型相比，联合训练将端到端模型的相对性能提高了4％到13％。该模型在“华尔街日报”数据集中获得了5.53％的WER，在Librispeech测试清理和测试集中分别达到了5.42％和14.70％。

##### URL
[http://arxiv.org/abs/1712.07101](http://arxiv.org/abs/1712.07101)

##### PDF
[http://arxiv.org/pdf/1712.07101](http://arxiv.org/pdf/1712.07101)

