---
layout: post
title: "Deep RNNs Encode Soft Hierarchical Syntax"
date: 2018-05-11 01:34:52
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Prediction
author: Terra Blevins, Omer Levy, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
We present a set of experiments to demonstrate that deep recurrent neural networks (RNNs) learn internal representations that capture soft hierarchical notions of syntax from highly varied supervision. We consider four syntax tasks at different depths of the parse tree; for each word, we predict its part of speech as well as the first (parent), second (grandparent) and third level (great-grandparent) constituent labels that appear above it. These predictions are made from representations produced at different depths in networks that are pretrained with one of four objectives: dependency parsing, semantic role labeling, machine translation, or language modeling. In every case, we find a correspondence between network depth and syntactic depth, suggesting that a soft syntactic hierarchy emerges. This effect is robust across all conditions, indicating that the models encode significant amounts of syntax even in the absence of an explicit syntactic training supervision.

##### Abstract (translated by Google)
我们提出了一组实验来证明深回归神经网络（RNN）学习内部表示，从高度不同的监督中捕捉语法的软分层概念。我们在分析树的不同深度考虑四个语法任务;对于每个单词，我们都会预测其词性以及出现在其上方的第一个（父母），第二个（祖父母）和第三级（祖父母）成分标签。这些预测是从网络中的不同深度产生的表示形成的，这些网络被预先设定了四个目标之一：依赖分析，语义角色标注，机器翻译或语言建模。在每种情况下，我们都发现网络深度和句法深度之间的对应关系，表明软句法层次结构出现。这种效应在所有条件下都很稳健，即使在没有明确的句法训练监督的情况下，这些模型也可以对大量语法进行编码。

##### URL
[http://arxiv.org/abs/1805.04218](http://arxiv.org/abs/1805.04218)

##### PDF
[http://arxiv.org/pdf/1805.04218](http://arxiv.org/pdf/1805.04218)

