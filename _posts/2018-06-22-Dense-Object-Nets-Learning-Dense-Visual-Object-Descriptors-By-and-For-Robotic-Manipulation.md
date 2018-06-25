---
layout: post
title: "Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation"
date: 2018-06-22 16:38:01
categories: arXiv_CV
tags: arXiv_CV
author: Peter R. Florence, Lucas Manuelli, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
What is the right object representation for manipulation? We would like robots to visually perceive scenes and learn an understanding of the objects in them that (i) is task-agnostic and can be used as a building block for a variety of manipulation tasks, (ii) is generally applicable to both rigid and non-rigid objects, (iii) takes advantage of the strong priors provided by 3D vision, and (iv) is entirely learned from self-supervision. This is hard to achieve with previous methods: much recent work in grasping does not extend to grasping specific objects or other tasks, whereas task-specific learning may require many trials to generalize well across object configurations or other tasks. In this paper we present Dense Object Nets, which build on recent developments in self-supervised dense descriptor learning, as a consistent object representation for visual understanding and manipulation. We demonstrate they can be trained quickly (approximately 20 minutes) for a wide variety of previously unseen and potentially non-rigid objects. We additionally present novel contributions to enable multi-object descriptor learning, and show that by modifying our training procedure, we can either acquire descriptors which generalize across classes of objects, or descriptors that are distinct for each object instance. Finally, we demonstrate the novel application of learned dense descriptors to robotic manipulation. We demonstrate grasping of specific points on an object across potentially deformed object configurations, and demonstrate using class general descriptors to transfer specific grasps across objects in a class.

##### Abstract (translated by Google)
操纵的正确对象表示是什么？我们希望机器人能够在视觉上感知场景并了解其中的物体，这些物体（i）是与任务无关的，并且可以用作各种操纵任务的构建块，（ii）通常适用于刚性和（iii）利用三维视觉提供的强大先验优势，以及（iv）完全从自我监督中学习。使用以前的方法很难实现：近期的大量抓握工作并未扩展到掌握特定对象或其他任务，而针对特定任务的学习可能需要许多试验才能在对象配置或其他任务中进行很好的概括。在本文中，我们提出密集对象网络，它基于自监督稠密描述符学习的最新发展，作为视觉理解和操纵的一致对象表示。我们证明他们可以快速训练（大约20分钟），用于各种以前看不见的和可能非刚性的物体。我们另外还提出了一些新的贡献来实现多对象描述符学习，并且通过修改我们的训练过程，我们可以获取在对象类中泛化的描述符，或者为每个对象实例分别描述的描述符。最后，我们展示了学习密集描述符在机器人操纵中的新颖应用。我们演示如何抓取可能变形的对象配置中对象上的特定点，并演示如何使用类一般描述符在类中的对象间传递特定的抓握。

##### URL
[http://arxiv.org/abs/1806.08756](http://arxiv.org/abs/1806.08756)

##### PDF
[http://arxiv.org/pdf/1806.08756](http://arxiv.org/pdf/1806.08756)

