---
layout: post
title: "eSCAPE: a Large-scale Synthetic Corpus for Automatic Post-Editing"
date: 2018-03-20 06:59:27
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Matteo Negri, Marco Turchi, Rajen Chatterjee, Nicola Bertoldi
mathjax: true
---

* content
{:toc}

##### Abstract
Training models for the automatic correction of machine-translated text usually relies on data consisting of (source, MT, human post- edit) triplets providing, for each source sentence, examples of translation errors with the corresponding corrections made by a human post-editor. Ideally, a large amount of data of this kind should allow the model to learn reliable correction patterns and effectively apply them at test stage on unseen (source, MT) pairs. In practice, however, their limited availability calls for solutions that also integrate in the training process other sources of knowledge. Along this direction, state-of-the-art results have been recently achieved by systems that, in addition to a limited amount of available training data, exploit artificial corpora that approximate elements of the "gold" training instances with automatic translations. Following this idea, we present eSCAPE, the largest freely-available Synthetic Corpus for Automatic Post-Editing released so far. eSCAPE consists of millions of entries in which the MT element of the training triplets has been obtained by translating the source side of publicly-available parallel corpora, and using the target side as an artificial human post-edit. Translations are obtained both with phrase-based and neural models. For each MT paradigm, eSCAPE contains 7.2 million triplets for English-German and 3.3 millions for English-Italian, resulting in a total of 14,4 and 6,6 million instances respectively. The usefulness of eSCAPE is proved through experiments in a general-domain scenario, the most challenging one for automatic post-editing. For both language directions, the models trained on our artificial data always improve MT quality with statistically significant gains. The current version of eSCAPE can be freely downloaded from: <a href="http://hltshare.fbk.eu/QT21/eSCAPE.html.">this http URL</a>

##### Abstract (translated by Google)
自动校正机器翻译文本的训练模型通常依赖于由（源，MT，人工编辑后）三元组构成的数据，这些三元组针对每个源句子提供翻译错误的示例以及由人类后编辑器进行的相应更正。理想情况下，这种大量的数据应该允许模型学习可靠的校正模式，并在测试阶段有效地将它们应用于看不见的（源，MT）对。然而，实际上，它们的有限可用性需要解决方案，这些解决方案也将整合到培训过程中的其他知识来源。沿着这个方向，最近已经通过系统获得最先进的结果，除了有限的可用训练数据之外，还利用人造语料库来近似自动翻译的“黄金”训练实例的元素。遵循这个想法，我们展示了迄今为止发布的eSCAPE，它是迄今为止发布的最大的免费提供的自动编辑后合成语料库。 eSCAPE由数百万个条目组成，其中通过翻译公开可用的平行语料库的源端获得训练三胞胎的MT元素，并将目标侧用作人造人后编辑。翻译通过基于短语和神经模型获得。对于每个MT范例，eSCAPE包含英语 - 德语720万三胞胎和英 - 意三百三十万，分别总计14,4和6,600,000个实例。 eSCAPE的实用性通过通用场景中的实验得以证明，这是自动后期编辑中最具挑战性的一种场景。对于这两种语言方向，训练我们人造数据的模型总是可以提高MT质量，并获得统计显着的收益。当前版本的eSCAPE可以从以下网址免费下载：<a href="http://hltshare.fbk.eu/QT21/eSCAPE.html.">此http URL </a>

##### URL
[http://arxiv.org/abs/1803.07274](http://arxiv.org/abs/1803.07274)

##### PDF
[http://arxiv.org/pdf/1803.07274](http://arxiv.org/pdf/1803.07274)

