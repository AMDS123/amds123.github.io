---
layout: post
title: "Subjects and Their Objects: Localizing Interactees for a Person-Centric View of Importance"
date: 2016-04-17 08:26:31
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Detection Recognition
author: Chao-Yeh Chen, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding images with people often entails understanding their \emph{interactions} with other objects or people. As such, given a novel image, a vision system ought to infer which other objects/people play an important role in a given person's activity. However, existing methods are limited to learning action-specific interactions (e.g., how the pose of a tennis player relates to the position of his racquet when serving the ball) for improved recognition, making them unequipped to reason about novel interactions with actions or objects unobserved in the training data. We propose to predict the "interactee" in novel images---that is, to localize the \emph{object} of a person's action. Given an arbitrary image with a detected person, the goal is to produce a saliency map indicating the most likely positions and scales where that person's interactee would be found. To that end, we explore ways to learn the generic, action-independent connections between (a) representations of a person's pose, gaze, and scene cues and (b) the interactee object's position and scale. We provide results on a newly collected UT Interactee dataset spanning more than 10,000 images from SUN, PASCAL, and COCO. We show that the proposed interaction-informed saliency metric has practical utility for four tasks: contextual object detection, image retargeting, predicting object importance, and data-driven natural language scene description. All four scenarios reveal the value in linking the subject to its object in order to understand the story of an image.

##### Abstract (translated by Google)
与人们了解图像往往需要了解与其他物体或人物的“互动”。因此，给定一个新颖的图像，一个视觉系统应该推断哪一个其他物体/人在一个给定的人的活动中起着重要的作用。然而，现有的方法仅限于学习特定于动作的交互（例如，网球运动员的姿势如何与球在服球时的位置相关）以提高识别性，使得他们没有理由关于与动作或物体的新颖交互在训练数据中未观察到。我们提出在新颖的图像中预测“互动”，即将一个人的行为的“对象”本地化。给定一个被检测到的人的任意图像，目标是产生一个显着地图，指示该人的交互对象被发现的最有可能的位置和尺度。为此，我们探索了如何学习（a）人物的姿态，注视和场景线索的表示，以及（b）互动对象的位置和尺度之间的通用的，与动作无关的连接。我们在新收集的UT Interactee数据集上提供了结果，这些数据集涵盖了SUN，PASCAL和COCO的10,000多幅图像。我们表明，提出的交互通知显着性度量有四个任务的实际效用：上下文对象检测，图像重定向，预测对象的重要性，和数据驱动的自然语言场景描述。所有这四种情景都揭示了将主体与客体联系起来的价值，以便了解图像的故事。

##### URL
[https://arxiv.org/abs/1604.04842](https://arxiv.org/abs/1604.04842)

##### PDF
[https://arxiv.org/pdf/1604.04842](https://arxiv.org/pdf/1604.04842)

