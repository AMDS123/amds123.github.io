---
layout: post
title: "Learning a Robust Society of Tracking Parts"
date: 2017-05-26 14:51:43
categories: arXiv_CV
tags: arXiv_CV GAN Tracking Object_Tracking
author: Elena Burceanu, Marius Leordeanu
mathjax: true
---

* content
{:toc}

##### Abstract
Object tracking is an essential task in computer vision that has been studied since the early days of the field. Being able to follow objects that undergo different transformations in the video sequence, including changes in scale, illumination, shape and occlusions, makes the problem extremely difficult. One of the real challenges is to keep track of the changes in objects appearance and not drift towards the background clutter. Different from previous approaches, we obtain robustness against background with a tracker model that is composed of many different parts. They are classifiers that respond at different scales and locations. The tracker system functions as a society of parts, each having its own role and level of credibility. Reliable classifiers decide the tracker's next move, while newcomers are first monitored before gaining the necessary level of reliability to participate in the decision process. Some parts that loose their consistency are rejected, while others that show consistency for a sufficiently long time are promoted to permanent roles. The tracker system, as a whole, could also go through different phases, from the usual, normal functioning to states of weak agreement and even crisis. The tracker system has different governing rules in each state. What truly distinguishes our work from others is not necessarily the strength of individual tracking parts, but the way in which they work together and build a strong and robust organization. We also propose an efficient way to learn simultaneously many tracking parts, with a single closed-form formulation. We obtain a fast and robust tracker with state of the art performance on the challenging OTB50 dataset.

##### Abstract (translated by Google)
对象跟踪是计算机视觉中的一项重要任务，自从该领域早期开始就已经进行了研究。能够跟踪在视频序列中经历不同变换的对象，包括尺度，光照，形状和遮挡的变化，使得问题变得非常困难。其中一个真正的挑战是跟踪物体外观的变化，而不是背景混乱。与以前的方法不同，我们通过由许多不同部分组成的跟踪器模型获得对背景的鲁棒性。它们是分类器，可以在不同的尺度和位置进行响应。跟踪系统的功能是作为一个部分的社会，每个部门都有自己的角色和可信度。可靠的分类器决定跟踪者的下一步行动，而在获得必要的可靠性参与决策过程之前，首先监测新手。一些松散一致性的部分被拒绝，而另一些长时间显示一致性的部分被提升为永久性角色。整个跟踪系统也可以经历不同的阶段，从通常的正常运行到弱的一致甚至危机状态。跟踪系统在每个州都有不同的管理规则。真正将我们的工作与其他人区分开来的不一定是个人追踪部分的力量，而是他们一起工作的方式，建立一个强大而健全的组织。我们还提出了一种有效的方法来同时学习多个跟踪部件，只需一个封闭的形式。我们获得了具有挑战性的OTB50数据集上最先进的性能的快速和强大的追踪器。

##### URL
[https://arxiv.org/abs/1705.09602](https://arxiv.org/abs/1705.09602)

##### PDF
[https://arxiv.org/pdf/1705.09602](https://arxiv.org/pdf/1705.09602)

