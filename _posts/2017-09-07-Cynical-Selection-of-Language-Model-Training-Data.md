---
layout: post
title: "Cynical Selection of Language Model Training Data"
date: 2017-09-07 14:30:50
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Amittai Axelrod
mathjax: true
---

* content
{:toc}

##### Abstract
The Moore-Lewis method of "intelligent selection of language model training data" is very effective, cheap, efficient... and also has structural problems. (1) The method defines relevance by playing language models trained on the in-domain and the out-of-domain (or data pool) corpora against each other. This powerful idea-- which we set out to preserve-- treats the two corpora as the opposing ends of a single spectrum. This lack of nuance does not allow for the two corpora to be very similar. In the extreme case where the come from the same distribution, all of the sentences have a Moore-Lewis score of zero, so there is no resulting ranking. (2) The selected sentences are not guaranteed to be able to model the in-domain data, nor to even cover the in-domain data. They are simply well-liked by the in-domain model; this is necessary, but not sufficient. (3) There is no way to tell what is the optimal number of sentences to select, short of picking various thresholds and building the systems. We present a greedy, lazy, approximate, and generally efficient information-theoretic method of accomplishing the same goal using only vocabulary counts. The method has the following properties: (1) Is responsive to the extent to which two corpora differ. (2) Quickly reaches near-optimal vocabulary coverage. (3) Takes into account what has already been selected. (4) Does not involve defining any kind of domain, nor any kind of classifier. (6) Knows approximately when to stop. This method can be used as an inherently-meaningful measure of similarity, as it measures the bits of information to be gained by adding one text to another.

##### Abstract (translated by Google)
摩尔 - 刘易斯“语言模型训练数据的智能选择”方法是非常有效，廉价，高效的，也存在结构性问题。 （1）该方法通过播放在域内和域外（或数据池）语料库上训练的语言模型来定义相关性。这个强有力的想法 - 我们着手保留 - 把两个语料作为单一谱的两端对待。这种缺乏细微差别不允许两个语料库非常相似。在来自同一分布的极端情况下，所有句子的摩尔 - 刘易斯分数为零，因此没有得到的排名。 （2）所选择的句子不能保证能够模拟域内数据，甚至不能覆盖域内数据。他们只是喜欢的领域模型;这是必要的，但不够。 （3）没有办法说出最佳的句子数目是多少，挑选各种门槛和建立系统。我们提出了一个贪婪的，懒惰的，近似的，通常有效的信息论方法，只用词汇量来实现同样的目标。该方法具有以下特点：（1）对两个语料库的差异程度有反应。 （2）迅速达到近乎最佳的词汇覆盖率。 （3）考虑到已经选定的内容。 （4）不涉及定义任何类型的域，也不涉及任何类型的分类器。 （6）知道什么时候停止。这种方法可以被用来作为一个固有的有意义的相似性度量，因为它通过增加一个文本到另一个文本来度量要获得的信息的位数。

##### URL
[https://arxiv.org/abs/1709.02279](https://arxiv.org/abs/1709.02279)

##### PDF
[https://arxiv.org/pdf/1709.02279](https://arxiv.org/pdf/1709.02279)

