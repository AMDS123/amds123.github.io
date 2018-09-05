---
layout: post
title: "Natural Language Person Search Using Deep Reinforcement Learning"
date: 2018-09-02 16:19:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Reinforcement_Learning Detection
author: Ankit Shah, Tyler Vuong
mathjax: true
---

* content
{:toc}

##### Abstract
Recent success in deep reinforcement learning is having an agent learn how to play Go and beat the world champion without any prior knowledge of the game. In that task, the agent has to make a decision on what action to take based on the positions of the pieces. Person Search is recently explored using natural language based text description of images for video surveillance applications (S.Li et.al). We see (Fu.et al) provides an end to end approach for object-based retrieval using deep reinforcement learning without constraints placed on which objects are being detected. However, we believe for real-world applications such as person search defining specific constraints which identify a person as opposed to starting with a general object detection will have benefits in terms of performance and computational resources required. In our task, Deep reinforcement learning would localize the person in an image by reshaping the sizes of the bounding boxes. Deep Reinforcement learning with appropriate constraints would look only for the relevant person in the image as opposed to an unconstrained approach where each individual objects in the image are ranked. For person search, the agent is trying to form a tight bounding box around the person in the image who matches the description. The bounding box is initialized to the full image and at each time step, the agent makes a decision on how to change the current bounding box so that it has a tighter bound around the person based on the description of the person and the pixel values of the current bounding box. After the agent takes an action, it will be given a reward based on the Intersection over Union (IoU) of the current bounding box and the ground truth box. Once the agent believes that the bounding box is covering the person, it will indicate that the person is found.

##### Abstract (translated by Google)
最近在深度强化学习方面的成功是让代理人学习如何在没有任何游戏知识的情况下玩Go并击败世界冠军。在该任务中，代理必须根据部分的位置决定采取什么行动。最近使用基于自然语言的图像文本描述来探索人物搜索，用于视频监视应用（S.Li等人）。我们看到（Fu.et al）使用深度强化学习提供了基于对象的检索的端到端方法，而没有对正在检测哪些对象的约束。然而，我们相信真人世界的应用程序，例如定义识别人的特定约束的人搜索，而不是从一般对象检测开始，将在性能和所需的计算资源方面具有益处。在我们的任务中，深度强化学习将通过重新定义边界框的大小来定位图像中的人。具有适当约束的深度强化学习仅针对图像中的相关人员而不是无约束方法，其中图像中的每个单独对象被排序。对于人物搜索，代理正试图在图像中与描述匹配的人周围形成紧密的边界框。边界框初始化为完整图像，并且在每个时间步，代理人决定如何更改当前边界框，以便根据人员的描述和像素值对人物进行更紧密的约束。当前的边界框。在代理人采取行动之后，将根据当前边界框和地面实况框的联合交叉（IoU）给予奖励。一旦代理人认为边界框覆盖了该人，它将指示该人被找到。

##### URL
[http://arxiv.org/abs/1809.00365](http://arxiv.org/abs/1809.00365)

##### PDF
[http://arxiv.org/pdf/1809.00365](http://arxiv.org/pdf/1809.00365)

