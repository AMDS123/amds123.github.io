---
layout: post
title: "Social Behavior Prediction from First Person Videos"
date: 2016-11-29 03:04:41
categories: arXiv_CV
tags: arXiv_CV Attention CNN Prediction
author: Shan Su, Jung Pyo Hong, Jianbo Shi, Hyun Soo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to predict the future movements (location and gaze direction) of basketball players as a whole from their first person videos. The predicted behaviors reflect an individual physical space that affords to take the next actions while conforming to social behaviors by engaging to joint attention. Our key innovation is to use the 3D reconstruction of multiple first person cameras to automatically annotate each other's the visual semantics of social configurations. We leverage two learning signals uniquely embedded in first person videos. Individually, a first person video records the visual semantics of a spatial and social layout around a person that allows associating with past similar situations. Collectively, first person videos follow joint attention that can link the individuals to a group. We learn the egocentric visual semantics of group movements using a Siamese neural network to retrieve future trajectories. We consolidate the retrieved trajectories from all players by maximizing a measure of social compatibility---the gaze alignment towards joint attention predicted by their social formation, where the dynamics of joint attention is learned by a long-term recurrent convolutional network. This allows us to characterize which social configuration is more plausible and predict future group trajectories.

##### Abstract (translated by Google)
本文提出了一种从第一人称视频预测篮球运动员未来运动（位置和注视方向）的方法。预测的行为反映了一个个体的物理空间，通过参与到共同的关注中，这个空间可以采取下一步行动，同时符合社会行为。我们的主要创新是使用多个第一人称摄像机的3D重构来自动注释彼此的社交配置的视觉语义。我们利用唯一嵌入第一人称视频的两个学习信号。单独地，第一人称视频记录围绕人的空间和社交布局的视觉语义，其允许与过去类似的情况相关联。第一人称视频集合在一起，可以将个人联系到一个群体。我们使用连体神经网络来学习群体运动的自我中心视觉语义来检索未来的轨迹。我们通过最大化社会兼容性度量来统一所有参与者的检索轨迹---通过社会形成预测共同关注的注视对齐，其中共同关注的动态是由长期循环卷积网络学习的。这使我们能够表征哪个社会配置更合理，并预测未来的群组轨迹。

##### URL
[https://arxiv.org/abs/1611.09464](https://arxiv.org/abs/1611.09464)

##### PDF
[https://arxiv.org/pdf/1611.09464](https://arxiv.org/pdf/1611.09464)

