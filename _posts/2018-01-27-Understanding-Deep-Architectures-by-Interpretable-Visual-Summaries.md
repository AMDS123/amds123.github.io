---
layout: post
title: "Understanding Deep Architectures by Interpretable Visual Summaries"
date: 2018-01-27 15:26:07
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Classification
author: Marco Carletti, Marco Godi, Maedeh Aghaei, Marco Cristani
mathjax: true
---

* content
{:toc}

##### Abstract
A consistent body of research investigates the recurrent visual patterns exploited by deep networks for object classification with the help of diverse visualization techniques. Unfortunately, no effort has been spent in showing that these techniques are effective in leading researchers to univocal and exhaustive explanations. This paper goes in this direction, presenting a visualization framework owing to a group of clusters or summaries, each one formed by crisp image regions focusing on a particular part that the network has exploited with high regularity to classify a given class. In most of the cases, these parts carry a semantic meaning, making the explanation simple and universal. For example, the method suggests that AlexNet, when classifying the ImageNet class "robin", is very sensible to the patterns of the head, the body, the legs, the wings and the tail, providing five summaries where these parts are consistently highlighted. The approach is composed by a sparse optimization step providing sharp image masks whose perturbation causes high loss in the classification. Regions composing the masks are then clustered together by means of a proposal flow-based similarity score, that associates visually similar patterns of diverse objects which are in corresponding positions. The final clusters are visual summaries easy to be interpreted, as found by the very first user study of this kind. The summaries can be also used to compare different architectures: for example, the superiority of GoogleNet w.r.t. AlexNet is explained by our approach since the former gives rise to more summaries, indicating its ability in capturing a higher number of diverse semantic parts.

##### Abstract (translated by Google)
一个一致的研究调查深层网络利用不同的可视化技术帮助对象分类的复发视觉模式。不幸的是，没有花费在显示这些技术有效地引导研究者进行明确和详尽的解释。本文以这个方向为基础，提出一个可视化的框架，由一组聚类或摘要组成，每一个都由清晰的图像区域组成，重点放在网络利用高规则性对特定类别进行分类的特定部分。在大多数情况下，这些部分具有语义，使得解释简单而通用。例如，该方法建议AlexNet在对ImageNet类“robin”进行分类时，对头部，身体，腿部，翅膀和尾部的图案非常敏感，提供了总是突出显示这些部分的五个概要。该方法由一个稀疏的优化步骤组成，提供清晰的图像掩模，其扰动造成分类中的高损失。然后通过基于提议基于流的相似性分数将构成掩模的区域聚集在一起，该相似性分数将处于相应位置的不同对象的视觉上相似的图案相关联。最后的集群是易于解释的视觉总结，正如这种第一次用户研究所发现的。摘要也可以用来比较不同的体系结构：例如GoogleNet w.r.t的优越性。 AlexNet是由我们的方法解释，因为前者产生更多的摘要，表明它捕获更多不同的语义部分的能力。

##### URL
[http://arxiv.org/abs/1801.09103](http://arxiv.org/abs/1801.09103)

##### PDF
[http://arxiv.org/pdf/1801.09103](http://arxiv.org/pdf/1801.09103)

