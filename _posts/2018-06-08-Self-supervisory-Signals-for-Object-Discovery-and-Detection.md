---
layout: post
title: "Self-supervisory Signals for Object Discovery and Detection"
date: 2018-06-08 22:50:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face Embedding Detection
author: Etienne Pot, Alexander Toshev, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
In robotic applications, we often face the challenge of discovering new objects while having very little or no labelled training data. In this paper we explore the use of self-supervision provided by a robot traversing an environment to learn representations of encountered objects. Knowledge of ego-motion and depth perception enables the agent to effectively associate multiple object proposals, which serve as training data for learning object representations from unlabelled images. We demonstrate the utility of this representation in two ways. First, we can automatically discover objects by performing clustering in the learned embedding space. Each resulting cluster contains examples of one instance seen from various viewpoints and scales. Second, given a small number of labeled images, we can efficiently learn detectors for these labels. In the few-shot regime, these detectors have a substantially higher mAP of 0.22 compared to 0.12 of off-the-shelf standard detectors trained on this limited data. Thus, the proposed self-supervision results in effective environment specific object discovery and detection at no or very small human labeling cost.

##### Abstract (translated by Google)
在机器人应用中，我们经常面临发现新物体的挑战，同时只有很少或没有标记的训练数据。在本文中，我们探讨了使用机器人穿越环境提供的自我监督来学习遇到物体的表示。对自我运动和深度知觉的了解使代理人能够有效地关联多个对象提议，这些提议作为未标记图像学习对象表示的训练数据。我们通过两种方式展示了这种表示的效用。首先，我们可以通过在学习的嵌入空间中执行聚类来自动发现对象。每个结果集群都包含从各种观点和比例中看到的一个实例的示例。其次，给定少量的标记图像，我们可以有效地学习这些标签的检测器。在少数情况下，这些检测器具有0.22的相当高的mAP，而在这个有限的数据上，0.12的现成标准检测器被训练。因此，提议的自我监督导致有效的环境特定对象发现和检测，而没有或非常小的人类标签成本。

##### URL
[http://arxiv.org/abs/1806.03370](http://arxiv.org/abs/1806.03370)

##### PDF
[http://arxiv.org/pdf/1806.03370](http://arxiv.org/pdf/1806.03370)

