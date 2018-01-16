---
layout: post
title: "Black-box Generation of Adversarial Text Sequences to Evade Deep Learning Classifiers"
date: 2018-01-13 00:42:30
categories: arXiv_CL
tags: arXiv_CL Review Adversarial Attention Classification Deep_Learning Prediction
author: Ji Gao, Jack Lanchantin, Mary Lou Soffa, Yanjun Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Although various techniques have been proposed to generate adversarial samples for white-box attacks on text, little attention has been paid to a black-box attack, which is a more realistic scenario. In this paper, we present a novel algorithm, DeepWordBug, to effectively generate small text perturbations in a black-box setting that forces a deep-learning classifier to misclassify a text input. We develop novel scoring strategies to find the most important words to modify such that the deep classifier makes a wrong prediction. Simple character-level transformations are applied to the highest-ranked words in order to minimize the edit distance of the perturbation. We evaluated DeepWordBug on two real-world text datasets: Enron spam emails and IMDB movie reviews. Our experimental results indicate that DeepWordBug can reduce the classification accuracy from $99\%$ to around $40\%$ on Enron data and from $87\%$ to about $26\%$ on IMDB. Also, our experimental results strongly demonstrate that the generated adversarial sequences from a deep-learning model can similarly evade other deep models.

##### Abstract (translated by Google)
尽管已经提出了各种技术来生成用于文本白盒攻击的对抗样本，但是对黑盒攻击的关注不多，这是一种更现实的情况。在本文中，我们提出了一种新的算法，DeepWordBug，在黑盒子设置中有效地生成小文本扰动，迫使深度学习分类器错误分类文本输入。我们开发新颖的评分策略，以找到最重要的词语进行修改，使深层分类器做出错误的预测。为了使扰动的编辑距离最小化，简单的字符级转换应用于排名最高的词。我们评估DeepWordBug两个真实世界的文本数据集：安全垃圾邮件和IMDB电影评论。我们的实验结果表明，DeepWordBug可以将安全数据上的分类精度从$ 99 \％$降低到$ 40 \％$左右，IMDB上的$ 87 $％$降到$ 26 $％$左右。此外，我们的实验结果强烈地表明，从深度学习模型生成的敌对序列可以类似地逃避其他深层模型。

##### URL
[http://arxiv.org/abs/1801.04354](http://arxiv.org/abs/1801.04354)

##### PDF
[http://arxiv.org/pdf/1801.04354](http://arxiv.org/pdf/1801.04354)

