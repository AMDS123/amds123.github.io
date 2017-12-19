---
layout: post
title: "Visual Explanation by Interpretation: Improving Visual Feedback Capabilities of Deep Neural Networks"
date: 2017-12-18 09:17:44
categories: arXiv_CV
tags: arXiv_CV Prediction Quantitative
author: Jose Oramas, Kaili Wang, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
Learning-based representations have become the defacto means to address computer vision tasks. Despite their massive adoption, the amount of work aiming at understanding the internal representations learned by these models is rather limited. Existing methods aimed at model interpretation either require exhaustive manual inspection of visualizations, or link internal network activations with external "possibly useful" annotated concepts. We propose an intermediate scheme in which, given a pretrained model, we automatically identify internal features relevant for the set of classes considered by the model, without requiring additional annotations. We interpret the model through average visualizations of these features. Then, at test time, we explain the network prediction by accompanying the predicted class label with supporting heatmap visualizations derived from the identified relevant features. In addition, we propose a method to address the artifacts introduced by strided operations in deconvnet-based visualizations. Our evaluation on the MNIST, ILSVRC 12 and Fashion 144k datasets quantitatively shows that the proposed method is able to identify relevant internal features for the classes of interest while improving the quality of the produced visualizations.

##### Abstract (translated by Google)
基于学习的表示已经成为解决计算机视觉任务的事实手段。尽管他们被大量采用，但旨在了解这些模型所学内部表征的工作量是相当有限的。针对模型解释的现有方法要么需要对可视化进行详尽的手工检查，要么将内部网络激活与外部“可能有用的”注释概念联系起来。我们提出了一个中间方案，其中，在预训练模型的情况下，我们自动识别与模型考虑的类集相关的内部特征，而不需要额外的注释。我们通过对这些特征的平均可视化来解释模型。然后，在测试时，我们通过伴随着预测的类别标签与从所识别的相关特征导出的支持热图可视化来解释网络预测。另外，我们提出了一种方法来解决在基于deconvnet的可视化中由步进操作引入的工件。我们对MNIST，ILSVRC 12和Fashion 144k数据集的评估定量表明，所提出的方法能够在提高所生成的可视化的质量的同时，识别相关类别的相关内部特征。

##### URL
[http://arxiv.org/abs/1712.06302](http://arxiv.org/abs/1712.06302)

##### PDF
[http://arxiv.org/pdf/1712.06302](http://arxiv.org/pdf/1712.06302)

