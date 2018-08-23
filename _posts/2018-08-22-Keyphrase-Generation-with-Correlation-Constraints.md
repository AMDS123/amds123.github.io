---
layout: post
title: "Keyphrase Generation with Correlation Constraints"
date: 2018-08-22 02:06:08
categories: arXiv_CL
tags: arXiv_CL RNN Relation
author: Jun Chen, Xiaoming Zhang, Yu Wu, Zhao Yan, Zhoujun Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study automatic keyphrase generation. Although conventional approaches to this task show promising results, they neglect correlation among keyphrases, resulting in duplication and coverage issues. To solve these problems, we propose a new sequence-to-sequence architecture for keyphrase generation named CorrRNN, which captures correlation among multiple keyphrases in two ways. First, we employ a coverage vector to indicate whether the word in the source document has been summarized by previous phrases to improve the coverage for keyphrases. Second, preceding phrases are taken into account to eliminate duplicate phrases and improve result coherence. Experiment results show that our model significantly outperforms the state-of-the-art method on benchmark datasets in terms of both accuracy and diversity.

##### Abstract (translated by Google)
在本文中，我们研究自动密钥短语生成。虽然这项任务的传统方法显示出有希望的结果，但它们忽略了关键短语之间的相关性，导致重复和覆盖问题。为了解决这些问题，我们提出了一种新的用于密钥短语生成的序列到序列架构，名为CorrRNN，它以两种方式捕获多个关键短语之间的相关性。首先，我们使用覆盖向量来指示源文档中的单词是否已由先前的短语汇总，以改善关键短语的覆盖范围。其次，考虑前面的短语以消除重复的短语并改善结果的一致性。实验结果表明，我们的模型在准确性和多样性方面明显优于基准数据集的最新方法。

##### URL
[http://arxiv.org/abs/1808.07185](http://arxiv.org/abs/1808.07185)

##### PDF
[http://arxiv.org/pdf/1808.07185](http://arxiv.org/pdf/1808.07185)

