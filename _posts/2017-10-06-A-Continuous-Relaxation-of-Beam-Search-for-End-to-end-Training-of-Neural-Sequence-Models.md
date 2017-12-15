---
layout: post
title: "A Continuous Relaxation of Beam Search for End-to-end Training of Neural Sequence Models"
date: 2017-10-06 19:29:30
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Kartik Goyal, Graham Neubig, Chris Dyer, Taylor Berg-Kirkpatrick
mathjax: true
---

* content
{:toc}

##### Abstract
Beam search is a desirable choice of test-time decoding algorithm for neural sequence models because it potentially avoids search errors made by simpler greedy methods. However, typical cross entropy training procedures for these models do not directly consider the behaviour of the final decoding method. As a result, for cross-entropy trained models, beam decoding can sometimes yield reduced test performance when compared with greedy decoding. In order to train models that can more effectively make use of beam search, we propose a new training procedure that focuses on the final loss metric (e.g. Hamming loss) evaluated on the output of beam search. While well-defined, this "direct loss" objective is itself discontinuous and thus difficult to optimize. Hence, in our approach, we form a sub-differentiable surrogate objective by introducing a novel continuous approximation of the beam search decoding procedure. In experiments, we show that optimizing this new training objective yields substantially better results on two sequence tasks (Named Entity Recognition and CCG Supertagging) when compared with both cross entropy trained greedy decoding and cross entropy trained beam decoding baselines.

##### Abstract (translated by Google)
束搜索是神经序列模型的测试时间解码算法的理想选择，因为它可以避免由简单的贪婪方法产生的搜索错误。然而，这些模型的典型交叉熵训练过程并不直接考虑最终解码方法的行为。结果，对于交叉熵训练的模型，与贪婪解码相比，波束解码有时会降低测试性能。为了训练可以更有效地利用波束搜索的模型，我们提出了一种新的训练过程，其重点是在波束搜索的输出上评估的最终损失度量（例如，汉明损失）。虽然定义明确，但这种“直接损失”的目标本身是不连续的，因此难以优化。因此，在我们的方法中，我们通过引入波束搜索解码过程的新颖的连续近似来形成可微分的替代目标。在实验中，我们表明，与交叉熵训练的贪婪解码和交叉熵训练的波束解码基线相比，优化这个新的训练目标在两个序列任务（命名的实体识别和CCG超级标签）上产生更好的结果。

##### URL
[https://arxiv.org/abs/1708.00111](https://arxiv.org/abs/1708.00111)

##### PDF
[https://arxiv.org/pdf/1708.00111](https://arxiv.org/pdf/1708.00111)

