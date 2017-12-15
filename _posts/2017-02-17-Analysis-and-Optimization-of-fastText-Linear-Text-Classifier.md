---
layout: post
title: "Analysis and Optimization of fastText Linear Text Classifier"
date: 2017-02-17 22:10:28
categories: arXiv_SD
tags: arXiv_SD Text_Classification Embedding Optimization Classification Deep_Learning
author: Vladimir Zolotov, David Kung
mathjax: true
---

* content
{:toc}

##### Abstract
The paper [1] shows that simple linear classifier can compete with complex deep learning algorithms in text classification applications. Combining bag of words (BoW) and linear classification techniques, fastText [1] attains same or only slightly lower accuracy than deep learning algorithms [2-9] that are orders of magnitude slower. We proved formally that fastText can be transformed into a simpler equivalent classifier, which unlike fastText does not have any hidden layer. We also proved that the necessary and sufficient dimensionality of the word vector embedding space is exactly the number of document classes. These results help constructing more optimal linear text classifiers with guaranteed maximum classification capabilities. The results are proven exactly by pure formal algebraic methods without attracting any empirical data.

##### Abstract (translated by Google)
文[1]表明，简单的线性分类器可以与复杂的深度学习算法在文本分类应用中竞争。 fastText [1]与单词袋（BoW）和线性分类技术相结合的速度与深度学习算法[2-9]的速度相比，速度要慢一些。我们在形式上证明了fastText可以转换成一个更简单的等价分类器，它不像fastText没有任何隐藏层。我们还证明了矢量嵌入空间的必要和充分的维数正是文档类的数量。这些结果帮助构建具有保证的最大分类能力的更优化的线性文本分类器。结果被纯粹的形式化代数方法完全证明，没有吸引任何经验数据。

##### URL
[https://arxiv.org/abs/1702.05531](https://arxiv.org/abs/1702.05531)

##### PDF
[https://arxiv.org/pdf/1702.05531](https://arxiv.org/pdf/1702.05531)

