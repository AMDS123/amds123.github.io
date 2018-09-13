---
layout: post
title: "A Call for Clarity in Reporting BLEU Scores"
date: 2018-09-12 14:13:33
categories: arXiv_CL
tags: arXiv_CL Face
author: Matt Post
mathjax: true
---

* content
{:toc}

##### Abstract
The field of machine translation faces an under-recognized problem because of inconsistency in the reporting of scores from its dominant metric. Although people refer to "the" BLEU score, BLEU is in fact a parameterized metric whose values can vary wildly with changes to these parameters. These parameters are often not reported or are hard to find, and consequently, BLEU scores between papers cannot be directly compared. I quantify this variation, finding differences as high as 1.8 between commonly used configurations. The main culprit is different tokenization and normalization schemes applied to the reference. Pointing to the success of the parsing community, I suggest machine translation researchers settle upon the BLEU scheme used by the annual Conference on Machine Translation (WMT), which does not allow for user-supplied reference processing, and provide a new tool, SacreBLEU, to facilitate this.

##### Abstract (translated by Google)
机器翻译领域面临一个未被充分认识的问题，因为从其主导度量报告得分不一致。虽然人们提到“BLEU”分数，但BLEU实际上是一个参数化度量，其值随着这些参数的变化而变化很大。这些参数通常没有报告或很难找到，因此，不能直接比较论文之间的BLEU分数。我量化了这种变化，发现常用配置之间的差异高达1.8。主要罪魁祸首是应用于参考的不同标记化和规范化方案。针对解析社区的成功，我建议机器翻译研究人员采用年度机器翻译会议（WMT）所使用的BLEU方案，该方案不允许用户提供的参考处理，并提供新的工具，SacreBLEU，为此提供便利。

##### URL
[http://arxiv.org/abs/1804.08771](http://arxiv.org/abs/1804.08771)

##### PDF
[http://arxiv.org/pdf/1804.08771](http://arxiv.org/pdf/1804.08771)

