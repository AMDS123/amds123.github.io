---
layout: post
title: "ModelHub: Towards Unified Data and Lifecycle Management for Deep Learning"
date: 2016-11-18 20:59:25
categories: arXiv_CV
tags: arXiv_CV Inference Deep_Learning
author: Hui Miao, Ang Li, Larry S. Davis, Amol Deshpande
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has improved state-of-the-art results in many important fields, and has been the subject of much research in recent years, leading to the development of several systems for facilitating deep learning. Current systems, however, mainly focus on model building and training phases, while the issues of data management, model sharing, and lifecycle management are largely ignored. Deep learning modeling lifecycle generates a rich set of data artifacts, such as learned parameters and training logs, and comprises of several frequently conducted tasks, e.g., to understand the model behaviors and to try out new models. Dealing with such artifacts and tasks is cumbersome and largely left to the users. This paper describes our vision and implementation of a data and lifecycle management system for deep learning. First, we generalize model exploration and model enumeration queries from commonly conducted tasks by deep learning modelers, and propose a high-level domain specific language (DSL), inspired by SQL, to raise the abstraction level and accelerate the modeling process. To manage the data artifacts, especially the large amount of checkpointed float parameters, we design a novel model versioning system (dlv), and a read-optimized parameter archival storage system (PAS) that minimizes storage footprint and accelerates query workloads without losing accuracy. PAS archives versioned models using deltas in a multi-resolution fashion by separately storing the less significant bits, and features a novel progressive query (inference) evaluation algorithm. Third, we show that archiving versioned models using deltas poses a new dataset versioning problem and we develop efficient algorithms for solving it. We conduct extensive experiments over several real datasets from computer vision domain to show the efficiency of the proposed techniques.

##### Abstract (translated by Google)
深度学习在许多重要领域已经取得了最先进的成果，近年来一直是大量的研究课题，导致了一些促进深度学习的系统的发展。然而，现有的系统主要集中在模型建立和训练阶段，而数据管理，模型共享和生命周期管理等问题却被忽略。深度学习建模生命周期会生成一组丰富的数据构件，例如学习参数和训练日志，并且包含若干频繁执行的任务，例如了解模型行为并尝试新模型。处理这些工件和任务是麻烦的，很大程度上留给用户。本文描述了深度学习的数据和生命周期管理系统的远景和实施。首先，通过深度学习建模人员从常用任务中推广模型探索和模型枚举查询，并在SQL的启发下，提出一种高层次的领域特定语言（DSL），提高抽象层次，加速建模过程。为了管理数据工件，尤其是大量的检查点浮点参数，我们设计了一个新的模型版本管理系统（dlv）和一个读取优化的参数档案存储系统（PAS），最大限度地减少了存储空间，加快了查询工作负载的准确性。 PAS通过分开存储不太重要的位，以多分辨率方式使用deltas对版本化模型进行归档，并具有新颖的逐步查询（推理）评估算法。第三，我们展示了使用deltas归档版本模型提出了一个新的数据集版本问题，并且我们开发了解决这个问题的高效算法。我们对来自计算机视觉领域的几个真实数据集进行了广泛的实验，以展示所提出的技术的效率。

##### URL
[https://arxiv.org/abs/1611.06224](https://arxiv.org/abs/1611.06224)

##### PDF
[https://arxiv.org/pdf/1611.06224](https://arxiv.org/pdf/1611.06224)

