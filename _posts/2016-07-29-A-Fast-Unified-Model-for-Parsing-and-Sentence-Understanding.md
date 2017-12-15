---
layout: post
title: "A Fast Unified Model for Parsing and Sentence Understanding"
date: 2016-07-29 18:36:15
categories: arXiv_SD
tags: arXiv_SD
author: Samuel R. Bowman, Jon Gauthier, Abhinav Rastogi, Raghav Gupta, Christopher D. Manning, Christopher Potts
mathjax: true
---

* content
{:toc}

##### Abstract
Tree-structured neural networks exploit valuable syntactic parse information as they interpret the meanings of sentences. However, they suffer from two key technical problems that make them slow and unwieldy for large-scale NLP tasks: they usually operate on parsed sentences and they do not directly support batched computation. We address these issues by introducing the Stack-augmented Parser-Interpreter Neural Network (SPINN), which combines parsing and interpretation within a single tree-sequence hybrid model by integrating tree-structured sentence interpretation into the linear sequential structure of a shift-reduce parser. Our model supports batched computation for a speedup of up to 25 times over other tree-structured models, and its integrated parser can operate on unparsed data with little loss in accuracy. We evaluate it on the Stanford NLI entailment task and show that it significantly outperforms other sentence-encoding models.

##### Abstract (translated by Google)
树形结构的神经网络在解释句子的意义时利用了有价值的句法分析信息。然而，他们面临着两个关键的技术问题，这使得它们对于大规模的NLP任务来说变得缓慢和笨拙：它们通常运行在被解析的句子上，而不直接支持批量计算。我们通过引入堆叠增强解析器 - 解释器神经网络（SPINN）来解决这些问题，该解决方案将解析和解释结合到单个树序列混合模型中，将树形句子解释集成到移位 - 缩减解析器的线性顺序结构中。我们的模型支持批量计算，比其他树形结构模型的加速时间高达25倍，并且其集成的解析器可以对未分离的数据进行操作，精度损失很小。我们在斯坦福NLI包含任务上评估它，并且显示它明显优于其他句子编码模型。

##### URL
[https://arxiv.org/abs/1603.06021](https://arxiv.org/abs/1603.06021)

##### PDF
[https://arxiv.org/pdf/1603.06021](https://arxiv.org/pdf/1603.06021)

