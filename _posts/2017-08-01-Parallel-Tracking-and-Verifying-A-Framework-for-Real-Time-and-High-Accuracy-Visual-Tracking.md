---
layout: post
title: "Parallel Tracking and Verifying: A Framework for Real-Time and High Accuracy Visual Tracking"
date: 2017-08-01 04:16:34
categories: arXiv_CV
tags: arXiv_CV Tracking Inference Deep_Learning SLAM Relation
author: Heng Fan, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Being intensively studied, visual tracking has seen great recent advances in either speed (e.g., with correlation filters) or accuracy (e.g., with deep features). Real-time and high accuracy tracking algorithms, however, remain scarce. In this paper we study the problem from a new perspective and present a novel parallel tracking and verifying (PTAV) framework, by taking advantage of the ubiquity of multi-thread techniques and borrowing from the success of parallel tracking and mapping in visual SLAM. Our PTAV framework typically consists of two components, a tracker T and a verifier V, working in parallel on two separate threads. The tracker T aims to provide a super real-time tracking inference and is expected to perform well most of the time; by contrast, the verifier V checks the tracking results and corrects T when needed. The key innovation is that, V does not work on every frame but only upon the requests from T; on the other end, T may adjust the tracking according to the feedback from V. With such collaboration, PTAV enjoys both the high efficiency provided by T and the strong discriminative power by V. In our extensive experiments on popular benchmarks including OTB2013, OTB2015, TC128 and UAV20L, PTAV achieves the best tracking accuracy among all real-time trackers, and in fact performs even better than many deep learning based solutions. Moreover, as a general framework, PTAV is very flexible and has great rooms for improvement and generalization.

##### Abstract (translated by Google)
经过深入研究，视觉跟踪在速度（例如，相关滤波器）或准确性（例如具有深度特征）方面已经取得了很大的进步。然而，实时和高精度的跟踪算法仍然很少。在本文中，我们从一个新的角度来研究这个问题，并利用多线程技术的普遍性，借鉴可视SLAM中并行跟踪与映射的成功，提出了一种新的并行跟踪与验证（PTAV）框架。我们的PTAV框架通常由两个组件组成，一个跟踪器T和一个验证器V，在两个独立的线程上并行工作。跟踪器T旨在提供超级实时跟踪推断，预计在大多数时间表现良好;相反，验证者V检查跟踪结果并在需要时校正T.关键的创新之处在于，V并不是在每一帧上都工作，而只是在T的请求下工作;另一方面，T可以根据V的反馈来调整跟踪。通过这样的合作，PTAV同时具有T提供的高效率和V的强判别能力。在我们对常用基准（包括OTB2013，OTB2015）的广泛实验中， TC128和UAV20L，PTAV在所有实时跟踪器中实现了最佳的跟踪精度，事实上它比许多深度学习解决方案的表现更好。而且，作为一个总体框架，PTAV非常灵活，有很大的改进和推广的余地。

##### URL
[https://arxiv.org/abs/1708.00153](https://arxiv.org/abs/1708.00153)

##### PDF
[https://arxiv.org/pdf/1708.00153](https://arxiv.org/pdf/1708.00153)

