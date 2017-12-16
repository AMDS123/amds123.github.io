---
layout: post
title: "Improving 6D Pose Estimation of Objects in Clutter via Physics-aware Monte Carlo Tree Search"
date: 2017-10-24 02:13:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Optimization Detection
author: Chaitanya Mitash, Abdeslam Boularias, Kostas E. Bekris
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a process for efficiently searching over combinations of individual object 6D pose hypotheses in cluttered scenes, especially in cases involving occlusions and objects resting on each other. The initial set of candidate object poses is generated from state-of-the-art object detection and global point cloud registration techniques. The best-scored pose per object by using these techniques may not be accurate due to overlaps and occlusions. Nevertheless, experimental indications provided in this work show that object poses with lower ranks may be closer to the real poses than ones with high ranks according to registration techniques. This motivates a global optimization process for improving these poses by taking into account scene-level physical interactions between objects. It also implies that the Cartesian product of candidate poses for interacting objects must be searched so as to identify the best scene-level hypothesis. To perform the search efficiently, the candidate poses for each object are clustered so as to reduce their number but still keep a sufficient diversity. Then, searching over the combinations of candidate object poses is performed through a Monte Carlo Tree Search (MCTS) process that uses the similarity between the observed depth image of the scene and a rendering of the scene given the hypothesized pose as a score that guides the search procedure. MCTS handles in a principled way the tradeoff between fine-tuning the most promising poses and exploring new ones, by using the Upper Confidence Bound (UCB) technique. Experimental results indicate that this process is able to quickly identify in cluttered scenes physically-consistent object poses that are significantly closer to ground truth compared to poses found by point cloud registration methods.

##### Abstract (translated by Google)
这项工作提出了一个过程，有效地搜索混杂的场景中的个别对象六维姿态假设的组合，特别是在涉及到遮挡和对象彼此休息的情况下。候选对象姿势的初始集合是由最先进的对象检测和全局点云注册技术生成的。由于重叠和遮挡，通过使用这些技术每个对象得分最高的姿势可能不准确。然而，这项工作提供的实验指示表明，根据注册技术，较低级别的对象姿势可能更接近真实姿势。这激发了全局优化过程，通过考虑对象之间的场景级物理交互来改善这些姿势。这也意味着必须搜索交互对象的候选姿态的笛卡尔乘积，以便确定最佳的场景级假设。为了有效地执行搜索，对每个对象的候选姿态进行聚类，以减少它们的数量，但仍然保持足够的多样性。然后，通过蒙特卡洛树搜索（MCTS）过程来执行对候选对象姿态的组合的搜索，所述MCTS过程使用场景的观察深度图像与给定假设姿势的场景的渲染之间的相似度作为引导搜索程序。通过使用上置信区间（UCB）技术，MCTS在原则上处理微调最有前途的姿势和探索新姿势之间的权衡。实验结果表明，该过程能够在杂乱的场景中快速识别物理一致的物体姿态，与通过点云配准方法发现的姿态相比，该物体姿态显着接近于地面真实。

##### URL
[https://arxiv.org/abs/1710.08577](https://arxiv.org/abs/1710.08577)

##### PDF
[https://arxiv.org/pdf/1710.08577](https://arxiv.org/pdf/1710.08577)

