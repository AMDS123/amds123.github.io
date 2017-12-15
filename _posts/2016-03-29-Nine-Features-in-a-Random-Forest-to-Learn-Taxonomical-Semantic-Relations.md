---
layout: post
title: "Nine Features in a Random Forest to Learn Taxonomical Semantic Relations"
date: 2016-03-29 10:00:40
categories: arXiv_SD
tags: arXiv_SD Classification Relation
author: Enrico Santus, Alessandro Lenci, Tin-Shing Chiu, Qin Lu, Chu-Ren Huang
mathjax: true
---

* content
{:toc}

##### Abstract
ROOT9 is a supervised system for the classification of hypernyms, co-hyponyms and random words that is derived from the already introduced ROOT13 (Santus et al., 2016). It relies on a Random Forest algorithm and nine unsupervised corpus-based features. We evaluate it with a 10-fold cross validation on 9,600 pairs, equally distributed among the three classes and involving several Parts-Of-Speech (i.e. adjectives, nouns and verbs). When all the classes are present, ROOT9 achieves an F1 score of 90.7%, against a baseline of 57.2% (vector cosine). When the classification is binary, ROOT9 achieves the following results against the baseline: hypernyms-co-hyponyms 95.7% vs. 69.8%, hypernyms-random 91.8% vs. 64.1% and co-hyponyms-random 97.8% vs. 79.4%. In order to compare the performance with the state-of-the-art, we have also evaluated ROOT9 in subsets of the Weeds et al. (2014) datasets, proving that it is in fact competitive. Finally, we investigated whether the system learns the semantic relation or it simply learns the prototypical hypernyms, as claimed by Levy et al. (2015). The second possibility seems to be the most likely, even though ROOT9 can be trained on negative examples (i.e., switched hypernyms) to drastically reduce this bias.

##### Abstract (translated by Google)
ROOT9是一个监督系统，用于对已经引入的ROOT13（Santus et al。，2016）的上位词，联合词和随机词进行分类。它依赖随机森林算法和九个无监督的基于语料库的功能。我们通过9,600对10倍交叉验证来评估它，这三个类之间平均分配，涉及几个词类（即形容词，名词和动词）。当所有类别都存在时，ROOT9达到90.7％的F1得分，而基线为57.2％（向量余弦）。当分类为二元时，ROOT9对基线的结果如下：上位词 - 下位词95.7％比69.8％，上位词 - 随机91.8％比64.1％和联合下位词 - 随机97.8％比79.4％。为了比较性能和最先进的技术，我们还评估了ROOT9在Weeds等人的子集中。 （2014年）的数据集，证明它实际上是有竞争力的。最后，我们研究了系统学习语义关系还是仅仅学习原型上位语，如Levy等人所声称的那样。 （2015年）。第二种可能性似乎是最有可能的，尽管ROOT9可以训练负面的例子（即切换的上位词），以大大减少这种偏见。

##### URL
[https://arxiv.org/abs/1603.08702](https://arxiv.org/abs/1603.08702)

##### PDF
[https://arxiv.org/pdf/1603.08702](https://arxiv.org/pdf/1603.08702)

