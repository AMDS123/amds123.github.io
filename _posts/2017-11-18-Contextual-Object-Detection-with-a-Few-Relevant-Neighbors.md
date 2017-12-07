---
layout: post
title: "Contextual Object Detection with a Few Relevant Neighbors"
date: 2017-11-18 19:08:40
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection Relation
author: Ehud Barnea, Ohad Ben-Shahar
mathjax: true
---

* content
{:toc}

##### Abstract
A natural way to improve the detection of objects is to consider the contextual constraints imposed by the detection of additional objects in a given scene. In this work, we exploit the spatial relations between objects in order to improve detection capacity, as well as analyze various properties of the contextual object detection problem. To precisely calculate context-based probabilities of objects, we developed a model that examines the interactions between objects in an exact probabilistic setting, in contrast to previous methods that typically utilize approximations based on pairwise interactions. Such a scheme is facilitated by the single realistic assumption that the existence of an object in any given location is influenced by only few informative locations in space. Based on this assumption, we suggest a method for identifying these relevant locations and integrating them into an exact calculation of probability based on their raw detector responses. This scheme is shown to improve detection results and provides unique insights about the process of contextual inference for object detection. We show that it is generally difficult to learn that a particular object reduces the probability of another, and that in cases when the context and detector strongly disagree this learning becomes virtually impossible for the purposes of improving the results of an object detector. Finally, we demonstrate improved detection results through use of our approach as applied to the PASCAL VOC dataset.

##### Abstract (translated by Google)
改善物体检测的一种自然的方法是考虑在给定场景中检测附加物体所施加的上下文约束。在这项工作中，我们利用对象之间的空间关系，以提高检测能力，以及分析上下文对象检测问题的各种属性。为了精确地计算对象的基于上下文的概率，我们开发了一个模型，在一个精确的概率设置中检查对象之间的相互作用，与以前的方法通常利用基于成对相互作用的近似方法相反。这种方案是由一个单一的现实假设促进的，一个物体在任何给定位置的存在只受到太空信息位置的影响。基于这个假设，我们建议一种方法来识别这些相关的位置，并根据它们的原始探测器响应将它们整合到一个精确的概率计算中。该方案被证明可以改善检测结果，并且提供对物体检测的上下文推断过程的独特见解。我们表明，通常很难知道一个特定的对象降低了另一个对象的概率，并且在上下文和检测器完全不同意这种学习的情况下，对于改善对象检测器的结果而言，事实上变得不可能。最后，我们通过使用我们的方法应用于PASCAL VOC数据集来证明改进的检测结果。

##### URL
[https://arxiv.org/abs/1711.05705](https://arxiv.org/abs/1711.05705)

##### PDF
[https://arxiv.org/pdf/1711.05705](https://arxiv.org/pdf/1711.05705)

