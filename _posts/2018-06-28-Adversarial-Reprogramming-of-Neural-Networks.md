---
layout: post
title: "Adversarial Reprogramming of Neural Networks"
date: 2018-06-28 19:06:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Gamaleldin F. Elsayed, Ian Goodfellow, Jascha Sohl-Dickstein
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are susceptible to adversarial attacks. In computer vision, well-crafted perturbations to images can cause neural networks to make mistakes such as identifying a panda as a gibbon or confusing a cat with a computer. Previous adversarial examples have been designed to degrade performance of models or cause machine learning models to produce specific outputs chosen ahead of time by the attacker. We introduce adversarial attacks that instead reprogram the target model to perform a task chosen by the attacker---without the attacker needing to specify or compute the desired output for each test-time input. This attack is accomplished by optimizing for a single adversarial perturbation, of unrestricted magnitude, that can be added to all test-time inputs to a machine learning model in order to cause the model to perform a task chosen by the adversary when processing these inputs---even if the model was not trained to do this task. These perturbations can be thus considered a program for the new task. We demonstrate adversarial reprogramming on six ImageNet classification models, repurposing these models to perform a counting task, as well as two classification tasks: classification of MNIST and CIFAR-10 examples presented within the input to the ImageNet model.

##### Abstract (translated by Google)
深度神经网络容易受到对抗性攻击。在计算机视觉中，精心设计的图像扰动可能导致神经网络出错，例如将熊猫识别为长臂猿或将猫与计算机混淆。以前的对抗性示例旨在降低模型的性能，或导致机器学习模型产生攻击者提前选择的特定输出。我们引入了对抗性攻击，而不是重新编程目标模型以执行攻击者选择的任务 - 攻击者无需为每个测试时输入指定或计算所需的输出。这种攻击是通过优化单个不受限制的对抗性扰动来实现的，可以将其添加到机器学习模型的所有测试时输入中，以便在处理这些输入时使模型执行对手选择的任务 -  - 即使模型没有被训练去完成这项任务。这些扰动因此可以被认为是新任务的一个程序。我们在六个ImageNet分类模型上展示了对抗性重新编程，重新利用这些模型来执行计数任务，以及两个分类任务：在ImageNet模型的输入中呈现的MNIST和CIFAR-10示例的分类。

##### URL
[http://arxiv.org/abs/1806.11146](http://arxiv.org/abs/1806.11146)

##### PDF
[http://arxiv.org/pdf/1806.11146](http://arxiv.org/pdf/1806.11146)

