---
layout: post
title: "Depth-bounding is effective: Improvements and evaluation of unsupervised PCFG induction"
date: 2018-09-10 03:02:46
categories: arXiv_CL
tags: arXiv_CL Inference
author: Lifeng Jin, Finale Doshi-Velez, Timothy Miller, William Schuler, Lane Schwartz
mathjax: true
---

* content
{:toc}

##### Abstract
There have been several recent attempts to improve the accuracy of grammar induction systems by bounding the recursive complexity of the induction model (Ponvert et al., 2011; Noji and Johnson, 2016; Shain et al., 2016; Jin et al., 2018). Modern depth-bounded grammar inducers have been shown to be more accurate than early unbounded PCFG inducers, but this technique has never been compared against unbounded induction within the same system, in part because most previous depth-bounding models are built around sequence models, the complexity of which grows exponentially with the maximum allowed depth. The present work instead applies depth bounds within a chart-based Bayesian PCFG inducer (Johnson et al., 2007b), where bounding can be switched on and off, and then samples trees with and without bounding. Results show that depth-bounding is indeed significantly effective in limiting the search space of the inducer and thereby increasing the accuracy of the resulting parsing model. Moreover, parsing results on English, Chinese and German show that this bounded model with a new inference technique is able to produce parse trees more accurately than or competitively with state-of-the-art constituency-based grammar induction models.

##### Abstract (translated by Google)
最近有几种尝试通过限制归纳模型的递归复杂性来提高语法诱导系统的准确性（Ponvert等，2011; Noji和Johnson，2016; Shain等，2016; Jin等，2018） ）。现代深度限制语法诱导器已被证明比早期无界PCFG诱导器更准确，但这种技术从未与同一系统内的无界诱导进行比较，部分原因是大多数先前的深度边界模型是围绕序列模型构建的，其复杂性随着最大允许深度呈指数增长。本工作改为在基于图表的贝叶斯PCFG诱导剂（Johnson等人，2007b）中应用深度界限，其中可以打开和关闭边界，然后对有和没有边界的树进行采样。结果表明，深度限制确实在限制诱导物的搜索空间方面非常有效，从而提高了所得解析模型的准确性。此外，对英语，中文和德语的解析结果表明，这种带有新推理技术的有界模型能够比最先进的基于选区的语法归纳模型更准确地生成解析树。

##### URL
[http://arxiv.org/abs/1809.03112](http://arxiv.org/abs/1809.03112)

##### PDF
[http://arxiv.org/pdf/1809.03112](http://arxiv.org/pdf/1809.03112)

