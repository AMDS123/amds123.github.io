---
layout: post
title: "Grounding Visual Explanations"
date: 2017-11-17 09:33:58
categories: arXiv_CV
tags: arXiv_CV
author: Lisa Anne Hendricks, Ronghang Hu, Trevor Darrell, Zeynep Akata
mathjax: true
---

* content
{:toc}

##### Abstract
Existing models which generate textual explanations enforce task relevance through a discriminative term loss function, but such mechanisms only weakly constrain mentioned object parts to actually be present in the image. In this paper, a new model is proposed for generating explanations by utilizing localized grounding of constituent phrases in generated explanations to ensure image relevance. Specifically, we introduce a phrase-critic model to refine (re-score/re-rank) generated candidate explanations and employ a relative-attribute inspired ranking loss using "flipped" phrases as negative examples for training. At test time, our phrase-critic model takes an image and a candidate explanation as input and outputs a score indicating how well the candidate explanation is grounded in the image.

##### Abstract (translated by Google)
生成文本解释的现有模型通过区分性词语丢失函数来强化任务相关性，但是这样的机制仅仅弱地限制了所提到的对象部分实际上存在于图像中。本文提出了一种新的模型，利用生成的解释中构成短语的局部接地来生成解释，以保证图像的相关性。具体而言，我们引入了一个短语 - 评论模型，以改进（重新评分/重新排名）生成的候选人解释，并采用“翻转”短语的相对属性启发排名损失作为训练的负面例子。在考试时间，我们的短语评论模型将图像和候选解释作为输入，并输出表示候选解释如何在图像中基础的评分。

##### URL
[https://arxiv.org/abs/1711.06465](https://arxiv.org/abs/1711.06465)

##### PDF
[https://arxiv.org/pdf/1711.06465](https://arxiv.org/pdf/1711.06465)

