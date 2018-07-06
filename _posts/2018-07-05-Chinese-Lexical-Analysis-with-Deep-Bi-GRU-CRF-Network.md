---
layout: post
title: "Chinese Lexical Analysis with Deep Bi-GRU-CRF Network"
date: 2018-07-05 07:45:25
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention RNN Recognition
author: Zhenyu Jiao, Shuqi Sun, Ke Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Lexical analysis is believed to be a crucial step towards natural language understanding and has been widely studied. Recent years, end-to-end lexical analysis models with recurrent neural networks have gained increasing attention. In this report, we introduce a deep Bi-GRU-CRF network that jointly models word segmentation, part-of-speech tagging and named entity recognition tasks. We trained the model using several massive corpus pre-tagged by our best Chinese lexical analysis tool, together with a small, yet high-quality human annotated corpus. We conducted balanced sampling between different corpora to guarantee the influence of human annotations, and fine-tune the CRF decoding layer regularly during the training progress. As evaluated by linguistic experts, the model achieved a 95.5% accuracy on the test set, roughly 13% relative error reduction over our (previously) best Chinese lexical analysis tool. The model is computationally efficient, achieving the speed of 2.3K characters per second with one thread.

##### Abstract (translated by Google)
词法分析被认为是迈向自然语言理解的关键步骤，并且已被广泛研究。近年来，具有递归神经网络的端到端词法分析模型受到越来越多的关注。在本报告中，我们介绍了一个深层的Bi-GRU-CRF网络，它共同模拟了分词，词性标注和命名实体识别任务。我们使用我们最好的中文词法分析工具预先标记的几个大型语料库，以及一个小而高质量的人类注释语料库来训练模型。我们在不同语料库之间进行了平衡采样，以保证人类注释的影响，并在训练过程中定期微调CRF解码层。根据语言专家的评估，该模型在测试集上达到了95.5％的准确率，与我们（之前）最好的中文词法分析工具相比，相对误差降低了大约13％。该模型具有计算效率，使用一个线程实现每秒2.3K字符的速度。

##### URL
[http://arxiv.org/abs/1807.01882](http://arxiv.org/abs/1807.01882)

##### PDF
[http://arxiv.org/pdf/1807.01882](http://arxiv.org/pdf/1807.01882)

