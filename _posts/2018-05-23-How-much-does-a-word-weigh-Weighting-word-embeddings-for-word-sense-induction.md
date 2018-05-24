---
layout: post
title: "How much does a word weigh? Weighting word embeddings for word sense induction"
date: 2018-05-23 14:58:13
categories: arXiv_CL
tags: arXiv_CL GAN Embedding
author: Nikolay Arefyev, Pavel Ermolaev, Alexander Panchenko
mathjax: true
---

* content
{:toc}

##### Abstract
The paper describes our participation in the first shared task on word sense induction and disambiguation for the Russian language RUSSE'2018 (Panchenko et al., 2018). For each of several dozens of ambiguous words, the participants were asked to group text fragments containing it according to the senses of this word, which were not provided beforehand, therefore the "induction" part of the task. For instance, a word "bank" and a set of text fragments (also known as "contexts") in which this word occurs, e.g. "bank is a financial institution that accepts deposits" and "river bank is a slope beside a body of water" were given. A participant was asked to cluster such contexts in the unknown in advance number of clusters corresponding to, in this case, the "company" and the "area" senses of the word "bank". The organizers proposed three evaluation datasets of varying complexity and text genres based respectively on texts of Wikipedia, Web pages, and a dictionary of the Russian language. 
 We present two experiments: a positive and a negative one, based respectively on clustering of contexts represented as a weighted average of word embeddings and on machine translation using two state-of-the-art production neural machine translation systems. Our team showed the second best result on two datasets and the third best result on the remaining one dataset among 18 participating teams. We managed to substantially outperform competitive state-of-the-art baselines from the previous years based on sense embeddings.

##### Abstract (translated by Google)
该论文描述了我们参与第一个关于俄语RUSSE'2018（Panchenko等人，2018）的词义感应和消歧的共同任务。对于几十个含糊不清的单词中的每一个，参与者被要求根据这个单词的意义将它们包含它的文本片断分组，这些事先没有提供，因此是任务的“归纳”部分。例如，词“银行”以及其中出现该词的一组文本片段（也称为“上下文”），例如， “银行是接受存款的金融机构”，“河岸是一个水体旁边的斜坡”。要求参与者在事先未知的群集中对应于（在这种情况下）“银行”这个词的“公司”和“区域”意义上的这种情况。组织者分别根据维基百科的文本，网页和俄语词典提出了三种不同复杂度和文本流派的评估数据集。
 我们提出了两个实验：正面和负面，分别基于表示为词嵌入的加权平均值的上下文聚类和使用两个最先进的生产神经机器翻译系统的机器翻译。我们的团队在两个数据集中表现出第二好的结果，在剩余的一个数据集中，在18个参赛队伍中表现出第三好的结果。基于意义嵌入，我们设法大大超越了前几年竞争力最强的国家最先进的基线。

##### URL
[http://arxiv.org/abs/1805.09209](http://arxiv.org/abs/1805.09209)

##### PDF
[http://arxiv.org/pdf/1805.09209](http://arxiv.org/pdf/1805.09209)

