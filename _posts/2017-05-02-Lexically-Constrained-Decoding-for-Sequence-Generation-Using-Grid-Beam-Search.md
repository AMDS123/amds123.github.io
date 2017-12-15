---
layout: post
title: "Lexically Constrained Decoding for Sequence Generation Using Grid Beam Search"
date: 2017-05-02 13:52:08
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Chris Hokamp, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We present Grid Beam Search (GBS), an algorithm which extends beam search to allow the inclusion of pre-specified lexical constraints. The algorithm can be used with any model that generates a sequence $ \mathbf{\hat{y}} = \{y_{0}\ldots y_{T}\} $, by maximizing $ p(\mathbf{y} | \mathbf{x}) = \prod\limits_{t}p(y_{t} | \mathbf{x}; \{y_{0} \ldots y_{t-1}\}) $. Lexical constraints take the form of phrases or words that must be present in the output sequence. This is a very general way to incorporate additional knowledge into a model's output without requiring any modification of the model parameters or training data. We demonstrate the feasibility and flexibility of Lexically Constrained Decoding by conducting experiments on Neural Interactive-Predictive Translation, as well as Domain Adaptation for Neural Machine Translation. Experiments show that GBS can provide large improvements in translation quality in interactive scenarios, and that, even without any user input, GBS can be used to achieve significant gains in performance in domain adaptation scenarios.

##### Abstract (translated by Google)
我们提出了网格梁搜索（GBS），一种扩展束搜索以允许包含预先指定的词汇约束的算法。该算法可以用于通过最大化$ p（\ mathbf {y} |）来生成序列$ \ mathbf {\ hat {y}} = \ {y_ {0} \ ldots y_ {T} \} $的任何模型。 \ mathbf {x}）= \ prod \ limits_ {t} p（y_ {t} | \ mathbf {x}; \ {y_ {0} \ ldots y_ {t-1} \}）$。词汇约束采取必须出现在输出序列中的短语或单词的形式。将其他知识纳入模型的输出，而不需要对模型参数或训练数据进行任何修改，这是一种非常普遍的方法。我们通过进行神经交互预测翻译实验以及神经机器翻译的领域适应来证明词法约束解码的可行性和灵活性。实验表明，GBS可以在交互场景中提供较大的翻译质量改进，即使没有任何用户输入，也可以使用GBS在领域适应场景中获得显着的性能增益。

##### URL
[https://arxiv.org/abs/1704.07138](https://arxiv.org/abs/1704.07138)

##### PDF
[https://arxiv.org/pdf/1704.07138](https://arxiv.org/pdf/1704.07138)

