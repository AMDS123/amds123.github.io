---
layout: post
title: "A convex method for classification of groups of examples"
date: 2018-06-21 11:09:46
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Video_Classification Classification
author: Dori Peleg
mathjax: true
---

* content
{:toc}

##### Abstract
There are many applications where it important to perform well on a set of examples as opposed to individual examples. For example in image or video classification the question is does an object appear somewhere in the image or video while there are several candidates of the object per image or video. In this context, it is not important what is the performance per candidate. Instead the performance per group is the ultimate objective. 
 For such problems one popular approach assumes weak supervision where labels exist for the entire group and then multiple instance learning is utilized. Another approach is to optimize per candidate, assuming each candidate is labeled, in the belief that this will achieve good performance per group. 
 We will show that better results can be achieved if we offer a new methodology which synthesizes the aforementioned approaches and directly optimizes for the final optimization objective while consisting of a convex optimization problem which solves the global optimization problem. The benefit of grouping examples is demonstrated on an image classification task for detecting polyps in images from capsule endoscopy of the colon. The algorithm was designed to efficiently handle hundreds of millions of examples. Furthermore, modifications to the penalty function of the standard SVM algorithm, have proven to significantly improve performance in our test case.

##### Abstract (translated by Google)
有许多应用程序对于一组示例执行很好的重要性，而不是单个示例。例如，在图像或视频分类中，问题是对象是否出现在图像或视频的某个位置，而每个图像或视频有多个候选对象。在这种情况下，每位候选人的表现并不重要。相反，每组的表现是最终的目标。
 对于这样的问题，一种流行的方法假定整个组的标签存在弱监督，然后利用多实例学习。另一种方法是对每个候选人进行优化，假设每个候选人都被贴上了标签，相信这样可以实现每个群体的良好表现。
 我们将证明，如果我们提供一种综合前述方法的新方法，并直接优化最终优化目标，同时由解决全局优化问题的凸优化问题构成，则可以获得更好的结果。分组示例的益处在用于检测来自结肠胶囊内窥镜检查的图像中的息肉的图像分类任务上得到证明。该算法旨在有效处理数亿个示例。此外，对标准SVM算法的惩罚函数进行修改，已被证明可以显着提高测试用例的性能。

##### URL
[http://arxiv.org/abs/1806.08169](http://arxiv.org/abs/1806.08169)

##### PDF
[http://arxiv.org/pdf/1806.08169](http://arxiv.org/pdf/1806.08169)

