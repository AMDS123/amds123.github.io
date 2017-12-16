---
layout: post
title: "Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks"
date: 2017-07-18 16:45:29
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Image_Classification Classification Gradient_Descent
author: Chelsea Finn, Pieter Abbeel, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an algorithm for meta-learning that is model-agnostic, in the sense that it is compatible with any model trained with gradient descent and applicable to a variety of different learning problems, including classification, regression, and reinforcement learning. The goal of meta-learning is to train a model on a variety of learning tasks, such that it can solve new learning tasks using only a small number of training samples. In our approach, the parameters of the model are explicitly trained such that a small number of gradient steps with a small amount of training data from a new task will produce good generalization performance on that task. In effect, our method trains the model to be easy to fine-tune. We demonstrate that this approach leads to state-of-the-art performance on two few-shot image classification benchmarks, produces good results on few-shot regression, and accelerates fine-tuning for policy gradient reinforcement learning with neural network policies.

##### Abstract (translated by Google)
我们提出了一种模型不可知的元学习算法，它与任何使用梯度下降训练的模型兼容，适用于各种不同的学习问题，包括分类，回归和强化学习。元学习的目标是在各种学习任务上训练一个模型，以便仅使用少量的训练样本即可解决新的学习任务。在我们的方法中，模型的参数被明确地训练，使得来自新任务的具有少量训练数据的少量梯度步骤将在该任务上产生良好的泛化性能。实际上，我们的方法训练模型很容易进行微调。我们证明，这种方法导致两个少数镜头图像分类基准上的最先进的性能，在少数镜头回归上产生良好的结果，并加速对神经网络策略进行政策梯度强化学习的微调。

##### URL
[https://arxiv.org/abs/1703.03400](https://arxiv.org/abs/1703.03400)

##### PDF
[https://arxiv.org/pdf/1703.03400](https://arxiv.org/pdf/1703.03400)

