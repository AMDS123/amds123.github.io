---
layout: post
title: "Conditional BERT Contextual Augmentation"
date: 2018-12-17 11:26:42
categories: arXiv_AI
tags: arXiv_AI Text_Classification CNN RNN Classification Language_Model
author: Xing Wu, Shangwen Lv, Liangjun Zang, Jizhong Han, Songlin Hu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel data augmentation method for labeled sentences called conditional BERT contextual augmentation. Data augmentation methods are often applied to prevent overfitting and improve generalization of deep neural network models. Recently proposed contextual augmentation augments labeled sentences by randomly replacing words with more varied substitutions predicted by language model. BERT demonstrates that a deep bidirectional language model is more powerful than either an unidirectional language model or the shallow concatenation of a forward and backward model. We retrofit BERT to conditional BERT by introducing a new conditional masked language model\footnote{The term "conditional masked language model" appeared once in original BERT paper, which indicates context-conditional, is equivalent to term "masked language model". In our paper, "conditional masked language model" indicates we apply extra label-conditional constraint to the "masked language model".} task. The well trained conditional BERT can be applied to enhance contextual augmentation. Experiments on six various different text classification tasks show that our method can be easily applied to both convolutional or recurrent neural networks classifier to obtain obvious improvement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06705](http://arxiv.org/abs/1812.06705)

##### PDF
[http://arxiv.org/pdf/1812.06705](http://arxiv.org/pdf/1812.06705)

