---
layout: post
title: "Parallel Tracking and Verifying"
date: 2018-01-30 00:18:22
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Inference Deep_Learning SLAM Relation
author: Heng Fan, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Being intensively studied, visual object tracking has witnessed great advances in either speed (e.g., with correlation filters) or accuracy (e.g., with deep features). Real-time and high accuracy tracking algorithms, however, remain scarce. In this paper we study the problem from a new perspective and present a novel parallel tracking and verifying (PTAV) framework, by taking advantage of the ubiquity of multi-thread techniques and borrowing ideas from the success of parallel tracking and mapping in visual SLAM. The proposed PTAV framework is typically composed of two components, a (base) tracker T and a verifier V, working in parallel on two separate threads. The tracker T aims to provide a super real-time tracking inference and is expected to perform well most of the time; by contrast, the verifier V validates the tracking results and corrects T when needed. The key innovation is that, V does not work on every frame but only upon the requests from T; on the other end, T may adjust the tracking according to the feedback from V. With such collaboration, PTAV enjoys both the high efficiency provided by T and the strong discriminative power by V. Meanwhile, to adapt V to object appearance changes over time, we maintain a dynamic target template pool for adaptive verification, resulting in further performance improvements. In our extensive experiments on popular benchmarks including OTB2015, TC128, UAV20L and VOT2016, PTAV achieves the best tracking accuracy among all real-time trackers, and in fact even outperforms many deep learning based algorithms. Moreover, as a general framework, PTAV is very flexible with great potentials for future improvement and generalization.

##### Abstract (translated by Google)
经过深入研究，视觉对象跟踪在速度（例如，具有相关滤波器）或精度（例如具有深度特征）方面已经见证了巨大的进步。然而，实时和高精度的跟踪算法仍然很少。在本文中，我们从一个新的角度来研究这个问题，并且利用多线程技术的普遍性，并从视觉SLAM中并行跟踪和映射的成功中借鉴了一些思想，提出了一种新的并行跟踪和验证（PTAV）框架。所提出的PTAV框架通常由两个组件组成，一个（基本）跟踪器T和一个验证器V，在两个独立的线程上并行工作。跟踪器T旨在提供超级实时跟踪推断，预计在大多数时间表现良好;相反，验证者V验证跟踪结果并在需要时校正T.关键的创新之处在于，V并不是在每一帧上都工作，而只是在T的请求下工作;另一方面，T可以根据来自V的反馈来调整跟踪。通过这样的协作，PTAV既享有T提供的高效率，又享受V强烈的判别力。同时，为了适应V随时间的变化，我们为适应性验证维护一个动态目标模板池，进一步提高性能。在我们对包括OTB2015，TC128，UAV20L和VOT2016等常用基准的广泛实验中，PTAV实现了所有实时跟踪器中最好的跟踪精度，实际上甚至超过许多基于深度学习的算法。此外，作为一个总体框架，PTAV非常灵活，未来的改进和推广有很大的潜力。

##### URL
[http://arxiv.org/abs/1801.10496](http://arxiv.org/abs/1801.10496)

##### PDF
[http://arxiv.org/pdf/1801.10496](http://arxiv.org/pdf/1801.10496)

