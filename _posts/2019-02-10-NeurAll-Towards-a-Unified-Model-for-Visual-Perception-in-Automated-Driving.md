---
layout: post
title: "NeurAll: Towards a Unified Model for Visual Perception in Automated Driving"
date: 2019-02-10 12:45:49
categories: arXiv_CV
tags: arXiv_CV Review Object_Detection Segmentation Survey CNN Semantic_Segmentation Optimization Detection SLAM Recognition
author: Ganesh Sistu, Isabelle Leang, Sumanth Chennupati, Stefan Milz, Senthil Yogamani, Samir Rawashdeh
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) are successfully used for the important automotive visual perception tasks including object recognition, motion and depth estimation, visual SLAM, etc. However, these tasks are independently explored and modeled. In this paper, we propose a joint multi-task network design called NeurAll for learning all tasks simultaneously. Our main motivation is the computational efficiency achieved by sharing the expensive initial convolutional layers between all tasks. Indeed, the main bottleneck in automated driving systems is the limited processing power available on deployment hardware. There could be other benefits in improving accuracy for some tasks and it eases development effort. It also offers scalability to add more tasks leveraging existing features and achieving better generalization. We survey various CNN based solutions for visual perception tasks in automated driving. Then we propose a unified CNN model for the important tasks and discuss several advanced optimization and architecture design techniques to improve the baseline model. The paper is partly review and partly positional with demonstration of several preliminary results promising for future research. Firstly, we show that an efficient two-task model performing semantic segmentation and object detection achieves similar accuracies compared to separate models on various datasets with minimized runtime. We then illustrate that using depth regression as auxiliary task improves semantic segmentation and using multi-stream semantic segmentation outperforms one-stream semantic segmentation. The two-task network achieves 30 fps on an automotive grade low power SOC for 1280x384 image resolution

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03589](http://arxiv.org/abs/1902.03589)

##### PDF
[http://arxiv.org/pdf/1902.03589](http://arxiv.org/pdf/1902.03589)

