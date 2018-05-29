---
layout: post
title: "Using Syntax to Ground Referring Expressions in Natural Images"
date: 2018-05-26 22:02:05
categories: arXiv_CV
tags: arXiv_CV Relation Recognition
author: Volkan Cirik, Taylor Berg-Kirkpatrick, Louis-Philippe Morency
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce GroundNet, a neural network for referring expression recognition -- the task of localizing (or grounding) in an image the object referred to by a natural language expression. Our approach to this task is the first to rely on a syntactic analysis of the input referring expression in order to inform the structure of the computation graph. Given a parse tree for an input expression, we explicitly map the syntactic constituents and relationships present in the tree to a composed graph of neural modules that defines our architecture for performing localization. This syntax-based approach aids localization of \textit{both} the target object and auxiliary supporting objects mentioned in the expression. As a result, GroundNet is more interpretable than previous methods: we can (1) determine which phrase of the referring expression points to which object in the image and (2) track how the localization of the target object is determined by the network. We study this property empirically by introducing a new set of annotations on the GoogleRef dataset to evaluate localization of supporting objects. Our experiments show that GroundNet achieves state-of-the-art accuracy in identifying supporting objects, while maintaining comparable performance in the localization of target objects.

##### Abstract (translated by Google)
我们引入了GroundNet，这是一种用于表达识别的神经网络 - 将自然语言表达引用的对象定位（或接地）在图像中的任务。我们的这个任务的方法是首先依赖输入引用表达式的句法分析来通知计算图的结构。给定输入表达式的解析树，我们明确地将树中存在的句法成分和关系映射到定义我们执行本地化的架构的神经模块组合图。这种基于语法的方法有助于\ textit {both}表达式中提到的目标对象和辅助支持对象的本地化。因此，GroundNet比以前的方法更能解释：我们可以（1）确定引用表达式中的哪一个词组指向图像中的哪个对象，以及（2）跟踪目标对象的定位是如何由网络确定的。我们通过在GoogleRef数据集中引入一组新的注释来经验性地研究此属性，以评估支持对象的本地化。我们的实验表明，GroundNet在识别支持对象方面达到了最新的精确度，同时在目标对象的本地化方面保持了可比较的性能。

##### URL
[http://arxiv.org/abs/1805.10547](http://arxiv.org/abs/1805.10547)

##### PDF
[http://arxiv.org/pdf/1805.10547](http://arxiv.org/pdf/1805.10547)

