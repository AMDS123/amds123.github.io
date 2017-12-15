---
layout: post
title: "A Simple and Accurate Syntax-Agnostic Neural Model for Dependency-based Semantic Role Labeling"
date: 2017-06-15 16:47:47
categories: arXiv_SD
tags: arXiv_SD Inference RNN
author: Diego Marcheggiani, Anton Frolov, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a simple and accurate neural model for dependency-based semantic role labeling. Our model predicts predicate-argument dependencies relying on states of a bidirectional LSTM encoder. The semantic role labeler achieves competitive performance on English, even without any kind of syntactic information and only using local inference. However, when automatically predicted part-of-speech tags are provided as input, it substantially outperforms all previous local models and approaches the best reported results on the English CoNLL-2009 dataset. We also consider Chinese, Czech and Spanish where our approach also achieves competitive results. Syntactic parsers are unreliable on out-of-domain data, so standard (i.e., syntactically-informed) SRL models are hindered when tested in this setting. Our syntax-agnostic model appears more robust, resulting in the best reported results on standard out-of-domain test sets.

##### Abstract (translated by Google)
我们引入了一个简单而准确的神经模型，用于基于依赖关系的语义角色标注。我们的模型预测依赖于双向LSTM编码器的状态的谓词 - 论点依赖性。语义角色标签者即使没有任何形式的句法信息，也只能使用局部推理，才能在英语上达到有竞争力的表现。然而，当自动预测的词性标签作为输入提供时，它大大优于以前的所有本地模型，并接近英语CoNLL-2009数据集上最好的报告结果。我们也考虑中国，捷克和西班牙语，我们的方法也取得了有竞争力的结果。句法分析器在域外数据上是不可靠的，所以当在这个设置中测试时，标准的（即，语法知识的）SRL模型受到阻碍。我们的语法不可知模型看起来更加健壮，从而在标准的域外测试集上得到最好的报告结果。

##### URL
[https://arxiv.org/abs/1701.02593](https://arxiv.org/abs/1701.02593)

##### PDF
[https://arxiv.org/pdf/1701.02593](https://arxiv.org/pdf/1701.02593)

