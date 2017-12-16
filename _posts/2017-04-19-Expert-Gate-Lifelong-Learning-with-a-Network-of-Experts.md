---
layout: post
title: "Expert Gate: Lifelong Learning with a Network of Experts"
date: 2017-04-19 09:25:55
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Prediction
author: Rahaf Aljundi, Punarjay Chakravarty, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce a model of lifelong learning, based on a Network of Experts. New tasks / experts are learned and added to the model sequentially, building on what was learned before. To ensure scalability of this process,data from previous tasks cannot be stored and hence is not available when learning a new task. A critical issue in such context, not addressed in the literature so far, relates to the decision which expert to deploy at test time. We introduce a set of gating autoencoders that learn a representation for the task at hand, and, at test time, automatically forward the test sample to the relevant expert. This also brings memory efficiency as only one expert network has to be loaded into memory at any given time. Further, the autoencoders inherently capture the relatedness of one task to another, based on which the most relevant prior model to be used for training a new expert, with finetuning or learning without-forgetting, can be selected. We evaluate our method on image classification and video prediction problems.

##### Abstract (translated by Google)
在本文中，我们介绍了一个基于专家网络的终身学习模型。学习新的任务/专家，并根据以前学到的知识，逐步添加到模型中。为了确保这个过程的可扩展性，以前任务的数据不能被存储，因此在学习新任务时不可用。在这样的背景下的一个关键问题，到目前为止在文献中没有提到，涉及到在测试时间部署专家的决定。我们介绍一套门控自动编码器，用于学习手头任务的表示，并在测试时自动将测试样本转发给相关专家。这也带来了内存效率，因为在任何时候只有一个专家网络必须被加载到内存中。此外，自动编码器本身捕捉到一个任务与另一个任务的相关性，基于此，可以选择用于训练新专家的最相关的在先模型，以及微调或不忘记学习。我们评估我们的方法在图像分类和视频预测问题。

##### URL
[https://arxiv.org/abs/1611.06194](https://arxiv.org/abs/1611.06194)

##### PDF
[https://arxiv.org/pdf/1611.06194](https://arxiv.org/pdf/1611.06194)

