---
layout: post
title: "Learning feed-forward one-shot learners"
date: 2016-06-16 15:49:26
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding Object_Tracking Classification Deep_Learning
author: Luca Bertinetto, João F. Henriques, Jack Valmadre, Philip H. S. Torr, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
One-shot learning is usually tackled by using generative models or discriminative embeddings. Discriminative methods based on deep learning, which are very effective in other learning scenarios, are ill-suited for one-shot learning as they need large amounts of training data. In this paper, we propose a method to learn the parameters of a deep model in one shot. We construct the learner as a second deep network, called a learnet, which predicts the parameters of a pupil network from a single exemplar. In this manner we obtain an efficient feed-forward one-shot learner, trained end-to-end by minimizing a one-shot classification objective in a learning to learn formulation. In order to make the construction feasible, we propose a number of factorizations of the parameters of the pupil network. We demonstrate encouraging results by learning characters from single exemplars in Omniglot, and by tracking visual objects from a single initial exemplar in the Visual Object Tracking benchmark.

##### Abstract (translated by Google)
通常使用生成模型或有区别的嵌入来处理一次性学习。基于深度学习的判别方法在其他学习场景中非常有效，不适合一次性学习，因为他们需要大量的训练数据。在本文中，我们提出了一种方法来一次性地学习深度模型的参数。我们将学习者构建为第二个深度网络，称为学习网络，它从一个示例中预测学生网络的参数。以这种方式，我们获得了一个有效的前馈一次性学习者，通过最小化学习学习公式中的一次分类目标来端对端地进行训练。为了使建设可行，我们提出了一些对学生网络参数的分解。通过在Omniglot中学习单个示例中的字符，并通过跟踪Visual Object Tracking基准中单个初始示例的可视对象，我们可以得到令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1606.05233](https://arxiv.org/abs/1606.05233)

##### PDF
[https://arxiv.org/pdf/1606.05233](https://arxiv.org/pdf/1606.05233)

