---
layout: post
title: "A Novel ECOC Algorithm with Centroid Distance Based Soft Coding Scheme"
date: 2018-06-22 01:35:39
categories: arXiv_AI
tags: arXiv_AI Knowledge Classification
author: Kaijie Feng, Kunhong Liu, Beizhan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In ECOC framework, the ternary coding strategy is widely deployed in coding process. It relabels classes with {"-1,0,1" }, where -1/1 means to assign the corresponding classes to the negative/positive group, and label 0 leads to ignore the corresponding classes in the training process. However, the application of hard labels may lose some information about the tendency of class distributions. Instead, we propose a Centroid distance-based Soft coding scheme to indicate such tendency, named as CSECOC. In our algorithm, Sequential Forward Floating Selection (SFFS) is applied to search an optimal class assignment by minimizing the ratio of intra-group and inter-group distance. In this way, a hard coding matrix is generated initially. Then we propose a measure, named as coverage, to describe the probability of a sample in a class falling to a correct group. The coverage of a class a group replace the corresponding hard element, so as to form a soft coding matrix. Compared with the hard ones, such soft elements can reflect the tendency of a class belonging to positive or negative group. Instead of classifiers, regressors are used as base learners in this algorithm. To the best of our knowledge, it is the first time that soft coding scheme has been proposed. The results on five UCI datasets show that compared with some state-of-art ECOC algorithms, our algorithm can produce comparable or better classification accuracy with small scale ensembles.

##### Abstract (translated by Google)
在ECOC框架中，三进制编码策略在编码过程中被广泛部署。它用{“-1,0,1”}对类进行重新标记，其中-1/1意味着将相应的类分配给负/正组，而标号0导致在训练过程中忽略相应的类。然而，硬标签的应用可能会失去一些关于阶级分布趋势的信息。相反，我们提出一种基于质心距离的软编码方案来表明这种趋势，命名为CSECOC。在我们的算法中，序列正向浮动选择（SFFS）用于通过最小化组内和组间距离的比率来搜索最佳类别指派。以这种方式，最初生成硬编码矩阵。然后，我们提出一个名为覆盖范围的度量来描述班级中的样本落入正确群体的概率。一组类的覆盖率取代了相应的硬件元素，从而形成一个软编码矩阵。与坚硬的元素相比，这些软元素可以反映属于正面或负面群体的阶层的倾向。该算法不使用分类器，而是将回归器用作基础学习器。据我们所知，这是第一次提出软编码方案。五个UCI数据集的结果显示，与一些最先进的ECOC算法相比，我们的算法可以产生与小规模集合相当或更好的分类准确性。

##### URL
[http://arxiv.org/abs/1806.08465](http://arxiv.org/abs/1806.08465)

##### PDF
[http://arxiv.org/pdf/1806.08465](http://arxiv.org/pdf/1806.08465)

