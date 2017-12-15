---
layout: post
title: "Stack-propagation: Improved Representation Learning for Syntax"
date: 2016-06-08 01:39:25
categories: arXiv_SD
tags: arXiv_SD Represenation_Learning
author: Yuan Zhang, David Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional syntax models typically leverage part-of-speech (POS) information by constructing features from hand-tuned templates. We demonstrate that a better approach is to utilize POS tags as a regularizer of learned representations. We propose a simple method for learning a stacked pipeline of models which we call "stack-propagation". We apply this to dependency parsing and tagging, where we use the hidden layer of the tagger network as a representation of the input tokens for the parser. At test time, our parser does not require predicted POS tags. On 19 languages from the Universal Dependencies, our method is 1.3% (absolute) more accurate than a state-of-the-art graph-based approach and 2.7% more accurate than the most comparable greedy model.

##### Abstract (translated by Google)
传统的语法模型通常通过构建来自手动调整的模板的特征来利用词性（POS）信息。我们证明更好的方法是利用POS标签作为学习表示的正规化。我们提出了一个简单的方法来学习我们称之为“堆栈传播”的模型堆叠管道。我们将其应用于依赖性解析和标记，我们使用标记网络的隐藏层作为解析器的输入标记的表示。在测试时间，我们的解析器不需要预测的POS标签。从通用相关性的19种语言中，我们的方法比最先进的基于图的方法更精确1.3％（绝对），比最相似的贪婪模型精确2.7％。

##### URL
[https://arxiv.org/abs/1603.06598](https://arxiv.org/abs/1603.06598)

##### PDF
[https://arxiv.org/pdf/1603.06598](https://arxiv.org/pdf/1603.06598)

