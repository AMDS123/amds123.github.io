---
layout: post
title: "Real-time Monocular Object SLAM"
date: 2015-04-09 17:46:19
categories: arXiv_CV
tags: arXiv_CV Optimization Detection SLAM Recognition
author: Dorian Gálvez-López, Marta Salas, Juan D. Tardós, J. M. M. Montiel
mathjax: true
---

* content
{:toc}

##### Abstract
We present a real-time object-based SLAM system that leverages the largest object database to date. Our approach comprises two main components: 1) a monocular SLAM algorithm that exploits object rigidity constraints to improve the map and find its real scale, and 2) a novel object recognition algorithm based on bags of binary words, which provides live detections with a database of 500 3D objects. The two components work together and benefit each other: the SLAM algorithm accumulates information from the observations of the objects, anchors object features to especial map landmarks and sets constrains on the optimization. At the same time, objects partially or fully located within the map are used as a prior to guide the recognition algorithm, achieving higher recall. We evaluate our proposal on five real environments showing improvements on the accuracy of the map and efficiency with respect to other state-of-the-art techniques.

##### Abstract (translated by Google)
我们提出了一个实时的基于对象的SLAM系统，它利用了迄今为止最大的对象数据库。我们的方法包括两个主要部分：1）单目SLAM算法，利用对象刚度约束来改善地图，并找到其真实的规模，2）一种基于二进制字袋的新型对象识别算法，提供实时检测与数据库500个3D对象。这两个组件协同工作，相互受益：SLAM算法从对象的观测中积累信息，将对象特征锚定到特定的地标上，并对优化设置约束条件。与此同时，部分或全部位于地图内的对象被用作指导识别算法的先决条件，实现更高的召回率。我们在五个真实的环境中评估我们的建议，显示出地图的准确性和其他最先进技术的效率方面的改进。

##### URL
[https://arxiv.org/abs/1504.02398](https://arxiv.org/abs/1504.02398)

##### PDF
[https://arxiv.org/pdf/1504.02398](https://arxiv.org/pdf/1504.02398)

