---
layout: post
title: "Joint Input-Label Embedding for Neural Text Classification"
date: 2018-06-16 10:47:41
categories: arXiv_CL
tags: arXiv_CL Text_Classification Embedding Classification
author: Nikolaos Pappas, James Henderson
mathjax: true
---

* content
{:toc}

##### Abstract
Neural text classification methods typically treat output classes as categorical labels which lack description and semantics. This leads to an inability to train them well on large label sets or to generalize to unseen labels and makes speed and parameterization dependent on the size of the label set. Joint input-label space methods ameliorate the above issues by exploiting label texts or descriptions, but often at the expense of weak performance on the labels seen frequently during training. In this paper, we propose a label-aware text classification model which addresses these issues without compromising performance on the seen labels. The model consists of a joint input-label multiplicative space and a label-set-size independent classification unit and is trained with cross-entropy loss to optimize accuracy. We evaluate our model on text classification for multilingual news and for biomedical text with a large label set. The label-aware model consistently outperforms both monolingual and multilingual classification models which do not leverage label semantics and previous joint input-label space models.

##### Abstract (translated by Google)
神经文本分类方法通常将输出类视为缺乏描述和语义的分类标签。这导致无法在大型标签集上很好地训练它们，或导致看不见的标签，并使速度和参数化取决于标签集的大小。联合输入标签空间方法通过利用标签文本或描述来改善上述问题，但通常以牺牲培训期间频繁出现的标签上的弱性能为代价。在本文中，我们提出了一个标签感知文本分类模型，可以解决这些问题，而不会影响所见标签的性能。该模型由联合输入 - 标签乘法空间和独立于标签集大小的分类单元组成，并用交叉熵损失进行训练以优化精度。我们评估我们的模型在多语种新闻的文本分类和生物医学文本与大标签集。标签感知模型始终优于单语言和多语言分类模型，这些模型不利用标签语义和先前的联合输入标签空间模型。

##### URL
[http://arxiv.org/abs/1806.06219](http://arxiv.org/abs/1806.06219)

##### PDF
[http://arxiv.org/pdf/1806.06219](http://arxiv.org/pdf/1806.06219)

