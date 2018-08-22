---
layout: post
title: "Adversarial Removal of Demographic Attributes from Text Data"
date: 2018-08-20 18:20:01
categories: arXiv_CL
tags: arXiv_CL Adversarial Represenation_Learning Classification
author: Yanai Elazar, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in Representation Learning and Adversarial Training seem to succeed in removing unwanted features from the learned representation. We show that demographic information of authors is encoded in -- and can be recovered from -- the intermediate representations learned by text-based neural classifiers. The implication is that decisions of classifiers trained on textual data are not agnostic to -- and likely condition on -- demographic attributes. When attempting to remove such demographic information using adversarial training, we find that while the adversarial component achieves chance-level development-set accuracy during training, a post-hoc classifier, trained on the encoded sentences from the first part, still manages to reach substantially higher classification accuracies on the same data. This behavior is consistent across several tasks, demographic properties and datasets. We explore several techniques to improve the effectiveness of the adversarial component. Our main conclusion is a cautionary one: do not rely on the adversarial training to achieve invariant representation to sensitive features.

##### Abstract (translated by Google)
表象学习和对抗训练的最新进展似乎成功地从学习的表示中删除了不需要的特征。我们表明，作者的人口统计信息被编码在 - 并且可以从 - 基于文本的神经分类器学习的中间表示中恢复。这意味着，对文本数据进行过培训的分类器的决策与人口统计学属性无关，也可能与之有关。当尝试使用对抗训练去除这些人口统计信息时，我们发现虽然对抗组件在训练期间达到了机会级别的开发设置准确性，但是对第一部分的编码句子进行过训练的事后分类器仍然设法达到对同一数据的分类准确度更高。此行为在多个任务，人口统计属性和数据集中保持一致。我们探索了几种提高对抗性成分效果的技术。我们的主要结论是警示性：不依靠对抗性训练来实现对敏感特征的不变表示。

##### URL
[http://arxiv.org/abs/1808.06640](http://arxiv.org/abs/1808.06640)

##### PDF
[http://arxiv.org/pdf/1808.06640](http://arxiv.org/pdf/1808.06640)

