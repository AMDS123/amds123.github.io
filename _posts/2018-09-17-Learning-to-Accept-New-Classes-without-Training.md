---
layout: post
title: "Learning to Accept New Classes without Training"
date: 2018-09-17 03:08:58
categories: arXiv_AI
tags: arXiv_AI Classification
author: Hu Xu, Bing Liu, Lei Shu, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Classic supervised learning makes the closed-world assumption, meaning that classes seen in testing must have been seen in training. However, in the dynamic world, new or unseen class examples may appear constantly. A model working in such an environment must be able to reject unseen classes (not seen or used in training). If enough data is collected for the unseen classes, the system should incrementally learn to accept/classify them. This learning paradigm is called open-world learning (OWL). Existing OWL methods all need some form of re-training to accept or include the new classes in the overall model. In this paper, we propose a meta-learning approach to the problem. Its key novelty is that it only needs to train a meta-classifier, which can then continually accept new classes when they have enough labeled data for the meta-classifier to use, and also detect/reject future unseen classes. No re-training of the meta-classifier or a new overall classifier covering all old and new classes is needed. In testing, the method only uses the examples of the seen classes (including the newly added classes) on-the-fly for classification and rejection. Experimental results demonstrate the effectiveness of the new approach.

##### Abstract (translated by Google)
经典的监督学习使得闭合世界的假设，意味着在测试中看到的类必须在训练中被看到。但是，在动态世界中，新的或看不见的类示例可能会不断出现。在这样的环境中工作的模型必须能够拒绝看不见的类（在培训中没有看到或使用过）。如果为看不见的类收集了足够的数据，系统应逐步学习接受/分类它们。这种学习范式被称为开放世界学习（OWL）。现有的OWL方法都需要某种形式的重新训练来接受或包括整个模型中的新类。在本文中，我们提出了一种针对该问题的元学习方法。它的关键新颖之处在于它只需要训练一个元分类器，当元分类器有足够的标记数据供元分类器使用时，它可以继续接受新类，并检测/拒绝未来看不见的类。不需要重新训练元分类器或覆盖所有新旧类的新的整体分类器。在测试中，该方法仅使用所见类（包括新添加的类）的示例来进行分类和拒绝。实验结果证明了新方法的有效性。

##### URL
[http://arxiv.org/abs/1809.06004](http://arxiv.org/abs/1809.06004)

##### PDF
[http://arxiv.org/pdf/1809.06004](http://arxiv.org/pdf/1809.06004)

