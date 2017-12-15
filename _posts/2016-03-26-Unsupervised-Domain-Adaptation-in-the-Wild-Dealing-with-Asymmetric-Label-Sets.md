---
layout: post
title: "Unsupervised Domain Adaptation in the Wild: Dealing with Asymmetric Label Sets"
date: 2016-03-26 13:22:55
categories: arXiv_CV
tags: arXiv_CV Classification
author: Ayush Mittal, Anant Raj, Vinay P. Namboodiri, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of domain adaptation is to adapt models learned on a source domain to a particular target domain. Most methods for unsupervised domain adaptation proposed in the literature to date, assume that the set of classes present in the target domain is identical to the set of classes present in the source domain. This is a restrictive assumption that limits the practical applicability of unsupervised domain adaptation techniques in real world settings ("in the wild"). Therefore, we relax this constraint and propose a technique that allows the set of target classes to be a subset of the source classes. This way, large publicly available annotated datasets with a wide variety of classes can be used as source, even if the actual set of classes in target can be more limited and, maybe most importantly, unknown beforehand. To this end, we propose an algorithm that orders a set of source subspaces that are relevant to the target classification problem. Our method then chooses a restricted set from this ordered set of source subspaces. As an extension, even starting from multiple source datasets with varied sets of categories, this method automatically selects an appropriate subset of source categories relevant to a target dataset. Empirical analysis on a number of source and target domain datasets shows that restricting the source subspace to only a subset of categories does indeed substantially improve the eventual target classification accuracy over the baseline that considers all source classes.

##### Abstract (translated by Google)
领域适应的目标是使在源领域学到的模型适应特定的目标领域。迄今为止在文献中提出的大多数无监督域自适应方法都假定目标域中存在的类集合与源域中存在的类集合相同。这是一个限制性的假设，限制了无监督域适应技术在现实世界中的实际应用（“野外”）。因此，我们放松这个约束，并提出一种技术，使目标类的集合成为源类的一个子集。这样，即使目标中的实际类别集合可能更有限，并且可能最重要的是，事先未知，但可以使用具有各种各样类别的大型公开可用注释数据集作为源。为此，我们提出了一个算法来排序一组与源目标分类问题相关的源子空间。然后，我们的方法从这个有序的源子空间集合中选择一个受限制的集合。作为一个扩展，即使从具有不同类别的多个源数据集开始，此方法也会自动选择与目标数据集相关的源类别的适当子集。对许多源域和目标域数据集的实证分析表明，将源子空间限制为只有子类别的子集确实大大提高了在考虑所有源类别的基线上的最终目标分类精度。

##### URL
[https://arxiv.org/abs/1603.08105](https://arxiv.org/abs/1603.08105)

##### PDF
[https://arxiv.org/pdf/1603.08105](https://arxiv.org/pdf/1603.08105)

