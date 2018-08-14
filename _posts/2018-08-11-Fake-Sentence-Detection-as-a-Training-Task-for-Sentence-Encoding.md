---
layout: post
title: "Fake Sentence Detection as a Training Task for Sentence Encoding"
date: 2018-08-11 17:31:15
categories: arXiv_CL
tags: arXiv_CL RNN Classification Language_Model Detection
author: Viresh Ranjan, Heeyoung Kwon, Niranjan Balasubramanian, Minh Hoai
mathjax: true
---

* content
{:toc}

##### Abstract
Sentence encoders are typically trained on language modeling tasks which enable them to use large unlabeled datasets. While these models achieve state-of-the-art results on many sentence-level tasks, they are difficult to train with long training cycles. We introduce fake sentence detection as a new training task for learning sentence encodings. We automatically generate fake sentences by corrupting some original sentence and train the encoders to produce representations that are effective at detecting fake sentences. This binary classification task allows for efficient training and forces the encoder to learn the distinctions introduced by a small edit to sentences. We train a basic BiLSTM encoder to produce sentence representations and find that it outperforms a strong sentence encoding model trained on language modeling tasks, while also training much faster on smaller amount of data (20 hours instead of weeks). Further analysis shows the learned representations capture many syntactic and semantic properties expected from good sentence representations.

##### Abstract (translated by Google)
句子编码器通常接受语言建模任务的培训，使他们能够使用大的未标记数据集。虽然这些模型在许多句子级任务中实现了最先进的结果，但是它们很难在长训练周期内进行训练。我们引入假句检测作为学习句子编码的新训练任务。我们通过破坏一些原始句子自动生成假句子并训练编码器以产生有效检测假句子的表示。这种二进制分类任务允许有效的训练并迫使编码器学习由小编辑引入的区别。我们训练一个基本的BiLSTM编码器来产生句子表示，并发现它优于在语言建模任务上训练的强句编码模型，同时在较少量的数据上训练得更快（20小时而不是数周）。进一步的分析表明，学习的表示可以捕获从良好的句子表示中预期的许多句法和语义属性。

##### URL
[http://arxiv.org/abs/1808.03840](http://arxiv.org/abs/1808.03840)

##### PDF
[http://arxiv.org/pdf/1808.03840](http://arxiv.org/pdf/1808.03840)

