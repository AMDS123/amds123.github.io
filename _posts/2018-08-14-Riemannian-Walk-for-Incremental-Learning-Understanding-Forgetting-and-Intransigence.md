---
layout: post
title: "Riemannian Walk for Incremental Learning: Understanding Forgetting and Intransigence"
date: 2018-08-14 16:10:46
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention
author: Arslan Chaudhry, Puneet K. Dokania, Thalaiyasingam Ajanthan, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Incremental learning (IL) has received a lot of attention recently, however, the literature lacks a precise problem definition, proper evaluation settings, and metrics tailored specifically for the IL problem. One of the main objectives of this work is to fill these gaps so as to provide a common ground for better understanding of IL. The main challenge for an IL algorithm is to update the classifier whilst preserving existing knowledge. We observe that, in addition to forgetting, a known issue while preserving knowledge, IL also suffers from a problem we call intransigence, inability of a model to update its knowledge. We introduce two metrics to quantify forgetting and intransigence that allow us to understand, analyse, and gain better insights into the behaviour of IL algorithms. We present RWalk, a generalization of EWC++ (our efficient version of EWC [Kirkpatrick2016EWC]) and Path Integral [Zenke2017Continual] with a theoretically grounded KL-divergence based perspective. We provide a thorough analysis of various IL algorithms on MNIST and CIFAR-100 datasets. In these experiments, RWalk obtains superior results in terms of accuracy, and also provides a better trade-off between forgetting and intransigence.

##### Abstract (translated by Google)
增量学习（IL）最近受到了很多关注，但是，文献缺乏精确的问题定义，适当的评估设置以及专门针对IL问题量身定制的指标。这项工作的主要目标之一是填补这些空白，以便为更好地理解IL提供共同点。 IL算法的主要挑战是更新分类器，同时保留现有知识。我们观察到，除了忘记一个已知的问题，同时保留知识，IL也会遇到一个我们称之为不妥协的问题，模型无法更新其知识。我们引入了两个量化遗忘和不妥协的指标，使我们能够理解，分析并获得对IL算法行为的更好洞察。我们提出了RWalk，EWC ++（我们的EWC [Kirkpatrick2016EWC]的高效版本）和Path Integral [Zenke2017Continual]的概括，具有理论上基于KL-divergence的视角。我们对MNIST和CIFAR-100数据集上的各种IL算法进行了全面分析。在这些实验中，RWalk在准确性方面获得了优异的结果，并且在遗忘和不妥协之间提供了更好的权衡。

##### URL
[http://arxiv.org/abs/1801.10112](http://arxiv.org/abs/1801.10112)

##### PDF
[http://arxiv.org/pdf/1801.10112](http://arxiv.org/pdf/1801.10112)

