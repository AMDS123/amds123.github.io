---
layout: post
title: "Using Neural Generative Models to Release Synthetic Twitter Corpora with Reduced Stylometric Identifiability of Users"
date: 2017-10-13 22:14:38
categories: arXiv_CL
tags: arXiv_CL Re-identification Language_Model
author: Alexander G. Ororbia II, Fridolin Linder, Joshua Snoke
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for generating synthetic versions of Twitter data using neural generative models. The goal is to protect individuals in the source data from stylometric re-identification attacks while still releasing data that carries research value. To generate tweet corpora that maintain user-level word distributions, our proposed approach augments powerful neural language models with local parameters that weight user-specific inputs. We compare our work to two standard text data protection methods: redaction and iterative translation. We evaluate the three methods on risk and utility. We define risk following the stylometric models of re-identification, and we define utility based on two general language measures and two common text analysis tasks. We find that neural models are able to significantly lower risk over previous methods at the cost of some utility. More importantly, we show that the risk utility trade-off depends on how the neural model's logits (or the unscaled pre-activation values of the output layer) are scaled. This work presents promising results for a new tool addressing the problem of privacy for free text and sharing social media data in a way that respects privacy and is ethically responsible.

##### Abstract (translated by Google)
我们介绍一种使用神经生成模型来生成合成版本的Twitter数据的方法。目标是保护源数据中的个人不受测版重新识别攻击，同时仍然释放具有研究价值的数据。为了生成维持用户级词分布的推文语料库，我们提出的方法利用赋予用户特定输入的局部参数来增强强大的神经语言模型。我们将我们的工作与两种标准的文本数据保护方法进行比较：编校和迭代翻译。我们评估风险和效用的三种方法。我们根据重新识别的测字模型定义风险，并且基于两种通用语言测量和两种常见的文本分析任务来定义效用。我们发现神经模型能够以某种效用为代价，显着降低以前方法的风险。更重要的是，我们表明，风险效用的权衡取决于神经模型的logits（或输出层的未缩放的预激活值）是如何缩放的。这项工作提供了一个新的工具，以尊重隐私和道德责任的方式处理自由文本的隐私问题和共享社交媒体数据的有希望的结果。

##### URL
[https://arxiv.org/abs/1606.01151](https://arxiv.org/abs/1606.01151)

##### PDF
[https://arxiv.org/pdf/1606.01151](https://arxiv.org/pdf/1606.01151)

