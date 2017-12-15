---
layout: post
title: "A Dictionary-based Approach to Racism Detection in Dutch Social Media"
date: 2016-08-31 06:28:28
categories: arXiv_CL
tags: arXiv_CL Language_Model Detection
author: Stéphan Tulkens, Lisa Hilte, Elise Lodewyckx, Ben Verhoeven, Walter Daelemans
mathjax: true
---

* content
{:toc}

##### Abstract
We present a dictionary-based approach to racism detection in Dutch social media comments, which were retrieved from two public Belgian social media sites likely to attract racist reactions. These comments were labeled as racist or non-racist by multiple annotators. For our approach, three discourse dictionaries were created: first, we created a dictionary by retrieving possibly racist and more neutral terms from the training data, and then augmenting these with more general words to remove some bias. A second dictionary was created through automatic expansion using a \texttt{word2vec} model trained on a large corpus of general Dutch text. Finally, a third dictionary was created by manually filtering out incorrect expansions. We trained multiple Support Vector Machines, using the distribution of words over the different categories in the dictionaries as features. The best-performing model used the manually cleaned dictionary and obtained an F-score of 0.46 for the racist class on a test set consisting of unseen Dutch comments, retrieved from the same sites used for the training set. The automated expansion of the dictionary only slightly boosted the model's performance, and this increase in performance was not statistically significant. The fact that the coverage of the expanded dictionaries did increase indicates that the words that were automatically added did occur in the corpus, but were not able to meaningfully impact performance. The dictionaries, code, and the procedure for requesting the corpus are available at: this https URL

##### Abstract (translated by Google)
我们提出了一个基于字典的方法来检测荷兰社交媒体中的种族主义评论，这些评论是从两个比利时公共社交媒体网站上检索出来的，可能会引起种族主义反应。这些评论被多个注释者标记为种族主义或非种族主义者。对于我们的方法，创建了三个话语词典：首先，我们创建一个字典，从训练数据中检索可能的种族主义和更中性的词汇，然后用更一般的词语来扩充这些词汇，以消除一些偏见。第二个字典是通过使用在大量荷兰语文本大文集上训练的\ text2 {}模型进行自动扩展而创建的。最后，通过手动过滤不正确的扩展来创建第三个字典。我们训练了多个支持向量机，利用词典中不同类别的词语分布作为特征。表现最好的模型使用手工清理的字典，并且在由用于训练集的相同站点检索的由不可见的荷兰语评论组成的测试集上获得0.46的F评分。字典的自动扩展只能略微提高模型的性能，而这种性能的提高并不具有统计意义。扩展字典的覆盖范围确实增加的事实表明，自动添加的单词确实发生在语料库中，但是不能对性能产生有意义的影响。字典，代码和请求语料库的程序可在以下网址获得：https URL

##### URL
[https://arxiv.org/abs/1608.08738](https://arxiv.org/abs/1608.08738)

##### PDF
[https://arxiv.org/pdf/1608.08738](https://arxiv.org/pdf/1608.08738)

