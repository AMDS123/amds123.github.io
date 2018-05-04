---
layout: post
title: "Joint Surgical Gesture and Task Classification with Multi-Task and Multimodal Learning"
date: 2018-05-02 10:43:12
categories: arXiv_CV
tags: arXiv_CV RNN Classification
author: Duygu Sarikaya, Khurshid A. Guru, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel multi-modal and multi-task architecture for simultaneous low level gesture and surgical task classification in Robot Assisted Surgery (RAS) videos.Our end-to-end architecture is based on the principles of a long short-term memory network (LSTM) that jointly learns temporal dynamics on rich representations of visual and motion features, while simultaneously classifying activities of low-level gestures and surgical tasks. Our experimental results show that our approach is superior compared to an ar- chitecture that classifies the gestures and surgical tasks separately on visual cues and motion cues respectively. We train our model on a fixed random set of 1200 gesture video segments and use the rest 422 for testing. This results in around 42,000 gesture frames sampled for training and 14,500 for testing. For a 6 split experimentation, while the conventional approach reaches an Average Precision (AP) of only 29% (29.13%), our architecture reaches an AP of 51% (50.83%) for 3 tasks and 14 possible gesture labels, resulting in an improvement of 22% (21.7%). Our architecture learns temporal dynamics on rich representations of visual and motion features that compliment each other for classification of low-level gestures and surgical tasks. Its multi-task learning nature makes use of learned joint re- lationships and combinations of shared and task-specific representations. While benchmark studies focus on recognizing gestures that take place under specific tasks, we focus on recognizing common gestures that reoccur across different tasks and settings and significantly perform better compared to conventional architectures.

##### Abstract (translated by Google)
我们提出了一种新的多模式和多任务架构，用于机器人辅助手术（RAS）视频中的同时低级手势和手术任务分类。我们的端到端架构基于长期短期记忆网络（LSTM）共同学习视觉和运动特征的丰富表示的时间动态，同时分类低级手势和手术任务的活动。我们的实验结果表明，与分别在视觉线索和运动线索上分别对手势和手术任务进行分类的架构相比，我们的方法更加优越。我们在1200个手势视频片段的固定随机集上训练我们的模型，并使用其余的422进行测试。这导致大约42,000个手势帧被抽样用于训练，14,500个用于测试。对于6次分割实验，尽管传统方法的平均精确度（AP）仅为29％（29.13％），但我们的架构对于3个任务和14个可能的手势标签达到51％（50.83％）的AP，导致提高22％（21.7％）。我们的体系结构学习视觉和运动特征的丰富表示中的时间动态，这些特征相互补充，用于分类低级手势和手术任务。其多任务学习性质利用学习的联合关系以及共享和任务特定表示的组合。虽然基准研究关注于识别在特定任务下发生的手势，但我们专注于识别在不同任务和设置中重复出现的常见手势，并且与传统体系结构相比显着提高性能。

##### URL
[https://arxiv.org/abs/1805.00721](https://arxiv.org/abs/1805.00721)

##### PDF
[https://arxiv.org/pdf/1805.00721](https://arxiv.org/pdf/1805.00721)

