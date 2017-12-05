---
layout: post
title:  'Learning by Asking Questions'
date:   2017-12-05 18:47:33
categories: CV
tags: CV
author: Ishan Misra, Ross Girshick, Rob Fergus, Martial Hebert, Abhinav Gupta, Laurens van der Maaten
---

* content
{:toc}

##### Abstract
We introduce an interactive learning framework for the development and testing of intelligent visual systems, called learning-by-asking (LBA). We explore LBA in context of the Visual Question Answering (VQA) task. LBA differs from standard VQA training in that most questions are not observed during training time, and the learner must ask questions it wants answers to. Thus, LBA more closely mimics natural learning and has the potential to be more data-efficient than the traditional VQA setting. We present a model that performs LBA on the CLEVR dataset, and show that it automatically discovers an easy-to-hard curriculum when learning interactively from an oracle. Our LBA generated data consistently matches or outperforms the CLEVR train data and is more sample efficient. We also show that our model asks questions that generalize to state-of-the-art VQA models and to novel test time distributions.

##### Abstract (translated by Google)
我们为智能视觉系统的开发和测试引入了一个交互式的学习框架，叫做问问学习（LBA）。我们在视觉问答（VQA）任务的背景下探索LBA。 LBA不同于标准的VQA训练，因为在训练时间内大多数问题都没有被观察到，学习者必须提出它想要的答案。因此，LBA更加模仿自然学习，并有可能比传统的VQA设置更具数据效率。我们提出了一个在CLEVR数据集上执行LBA的模型，并且表明当从oracle中交互式地学习时，它会自动发现一个容易到难的课程。我们的LBA生成的数据始终匹配或优于CLEVR列车数据，更高效的样本。我们还展示了我们的模型提出的问题，推广到最先进的VQA模型和新的测试时间分布。

##### URL
[http://arxiv.org/abs/1712.01238](http://arxiv.org/abs/1712.01238)

