---
layout: post
title: "Detecting and Recognizing Human-Object Interactions"
date: 2017-04-24 17:14:24
categories: arXiv_CV
tags: arXiv_CV
author: Georgia Gkioxari, Ross Girshick, Piotr Dollár, Kaiming He
mathjax: true
---

* content
{:toc}

##### Abstract
To understand the visual world, a machine must not only recognize individual object instances but also how they interact. Humans are often at the center of such interactions and detecting human-object interactions is an important practical and scientific problem. In this paper, we address the task of detecting <human, verb, object> triplets in challenging everyday photos. We propose a novel model that is driven by a human-centric approach. Our hypothesis is that the appearance of a person -- their pose, clothing, action -- is a powerful cue for localizing the objects they are interacting with. To exploit this cue, our model learns to predict an action-specific density over target object locations based on the appearance of a detected person. Our model also jointly learns to detect people and objects, and by fusing these predictions it efficiently infers interaction triplets in a clean, jointly trained end-to-end system we call Interact. We validate our approach on the recently introduced Verbs in COCO (V-COCO) dataset, where we show qualitatively and quantitatively compelling results.

##### Abstract (translated by Google)
为了理解视觉世界，机器不仅要识别单个对象实例，还要识别它们如何相互作用。人类经常处于这种相互作用的中心，探测人与物体的相互作用是一个重要的实际和科学问题。在这篇论文中，我们讨论了在具有挑战性的日常照片中检测<人，动词，宾语>三胞胎的任务。我们提出了一个以人为中心的方法驱动的新模型。我们的假设是，一个人的外表 - 他们的姿势，衣着，行动 - 是一个强大的线索，用于本地化他们正在互动的对象。为了利用这个提示，我们的模型学习根据检测到的人物的外观来预测针对目标物体位置的动作特定密度。我们的模型还共同学习探测人员和对象，通过融合这些预测，它可以在一个干净，共同训练的端对端系统（我们称之为Interact）中有效地推断出交互三元组。我们验证了我们最近在COCO（V-COCO）数据集中引入的动词的方法，其中我们展示了定性和定量的引人注目的结果。

##### URL
[https://arxiv.org/abs/1704.07333](https://arxiv.org/abs/1704.07333)

