---
layout: post
title: "First Person Action-Object Detection with EgoNet"
date: 2017-06-10 18:04:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Embedding Detection
author: Gedas Bertasius, Hyun Soo Park, Stella X. Yu, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Unlike traditional third-person cameras mounted on robots, a first-person camera, captures a person's visual sensorimotor object interactions from up close. In this paper, we study the tight interplay between our momentary visual attention and motor action with objects from a first-person camera. We propose a concept of action-objects---the objects that capture person's conscious visual (watching a TV) or tactile (taking a cup) interactions. Action-objects may be task-dependent but since many tasks share common person-object spatial configurations, action-objects exhibit a characteristic 3D spatial distance and orientation with respect to the person. We design a predictive model that detects action-objects using EgoNet, a joint two-stream network that holistically integrates visual appearance (RGB) and 3D spatial layout (depth and height) cues to predict per-pixel likelihood of action-objects. Our network also incorporates a first-person coordinate embedding, which is designed to learn a spatial distribution of the action-objects in the first-person data. We demonstrate EgoNet's predictive power, by showing that it consistently outperforms previous baseline approaches. Furthermore, EgoNet also exhibits a strong generalization ability, i.e., it predicts semantically meaningful objects in novel first-person datasets. Our method's ability to effectively detect action-objects could be used to improve robots' understanding of human-object interactions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1603.04908](https://arxiv.org/abs/1603.04908)

##### PDF
[https://arxiv.org/pdf/1603.04908](https://arxiv.org/pdf/1603.04908)

