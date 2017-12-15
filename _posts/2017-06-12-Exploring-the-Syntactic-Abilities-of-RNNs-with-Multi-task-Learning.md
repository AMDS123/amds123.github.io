---
layout: post
title: "Exploring the Syntactic Abilities of RNNs with Multi-task Learning"
date: 2017-06-12 10:00:47
categories: arXiv_CL
tags: arXiv_CL Knowledge RNN Language_Model
author: Emile Enguehard, Yoav Goldberg, Tal Linzen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has explored the syntactic abilities of RNNs using the subject-verb agreement task, which diagnoses sensitivity to sentence structure. RNNs performed this task well in common cases, but faltered in complex sentences (Linzen et al., 2016). We test whether these errors are due to inherent limitations of the architecture or to the relatively indirect supervision provided by most agreement dependencies in a corpus. We trained a single RNN to perform both the agreement task and an additional task, either CCG supertagging or language modeling. Multi-task training led to significantly lower error rates, in particular on complex sentences, suggesting that RNNs have the ability to evolve more sophisticated syntactic representations than shown before. We also show that easily available agreement training data can improve performance on other syntactic tasks, in particular when only a limited amount of training data is available for those tasks. The multi-task paradigm can also be leveraged to inject grammatical knowledge into language models.

##### Abstract (translated by Google)
最近的研究利用主谓一致性任务探索了RNNs的句法能力，从而诊断了对句子结构的敏感性。 RNNs在普通情况下完成了这项任务，但在复杂的句子中失败（Linzen et al。，2016）。我们测试这些错误是由于架构的固有限制，还是由语料库中大多数协议依赖提供的相对间接的监督。我们训练了一个RNN来执行协议任务和一个额外的任务，CCG超级标签或语言建模。多任务训练导致错误率显着降低，特别是在复杂的句子上，这表明RNN有能力演化比以前显示更复杂的句法表示。我们还表明，容易获得的协议训练数据可以提高其他语法任务的性能，特别是当只有有限的训练数据可用于这些任务时。多任务模式也可以用来将语法知识注入语言模型。

##### URL
[https://arxiv.org/abs/1706.03542](https://arxiv.org/abs/1706.03542)

##### PDF
[https://arxiv.org/pdf/1706.03542](https://arxiv.org/pdf/1706.03542)

