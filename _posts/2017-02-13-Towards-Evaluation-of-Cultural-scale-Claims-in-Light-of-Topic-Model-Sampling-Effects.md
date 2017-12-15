---
layout: post
title: "Towards Evaluation of Cultural-scale Claims in Light of Topic Model Sampling Effects"
date: 2017-02-13 15:48:16
categories: arXiv_CL
tags: arXiv_CL Classification
author: Jaimie Murdock, Jiaan Zeng, Colin Allen
mathjax: true
---

* content
{:toc}

##### Abstract
Cultural-scale models of full text documents are prone to over-interpretation by researchers making unintentionally strong socio-linguistic claims (Pechenick et al., 2015) without recognizing that even large digital libraries are merely samples of all the books ever produced. In this study, we test the sensitivity of the topic models to the sampling process by taking random samples of books in the Hathi Trust Digital Library from different areas of the Library of Congress Classification Outline. For each classification area, we train several topic models over the entire class with different random seeds, generating a set of spanning models. Then, we train topic models on random samples of books from the classification area, generating a set of sample models. Finally, we perform a topic alignment between each pair of models by computing the Jensen-Shannon distance (JSD) between the word probability distributions for each topic. We take two measures on each model alignment: alignment distance and topic overlap. We find that sample models with a large sample size typically have an alignment distance that falls in the range of the alignment distance between spanning models. Unsurprisingly, as sample size increases, alignment distance decreases. We also find that the topic overlap increases as sample size increases. However, the decomposition of these measures by sample size differs by number of topics and by classification area. We speculate that these measures could be used to find classes which have a common "canon" discussed among all books in the area, as shown by high topic overlap and low alignment distance even in small sample sizes.

##### Abstract (translated by Google)
全文本文件的文化规模模型很容易被研究者无意识地强烈的社会语言主张（Pechenick等，2015）忽视，甚至没有意识到即使是大型数字图书馆也仅仅是有史以来所有图书的样本。在这项研究中，我们通过在国会图书馆分类大纲的不同区域的Hathi信任数字图书馆随机抽取样本来测试主题模型对抽样过程的敏感性。对于每个分类区域，我们用不同的随机种子在整个班级上训练几个主题模型，生成一组生成模型。然后，我们从分类区的随机样本中训练主题模型，生成一组样本模型。最后，通过计算每个主题的概率分布之间的Jensen-Shannon距离（JSD），我们在每对模型之间进行主题对齐。我们对每个模型对齐采取两个措施：对齐距离和主题重叠。我们发现具有大样本尺寸的样本模型通常具有落在跨越模型之间的对准距离范围内的对准距离。不出所料，随着样本量的增加，对齐距离减小。我们还发现，随着样本量的增加，话题重叠程度增加。然而，这些措施的分解样本大小因主题的数量和分类区域而异。我们推测，这些措施可以用来找到在该地区的所有书籍中讨论共同“佳能”的课程，即使在小样本量下，高话题重叠和低对准距离也表现出来。

##### URL
[https://arxiv.org/abs/1512.05004](https://arxiv.org/abs/1512.05004)

##### PDF
[https://arxiv.org/pdf/1512.05004](https://arxiv.org/pdf/1512.05004)

