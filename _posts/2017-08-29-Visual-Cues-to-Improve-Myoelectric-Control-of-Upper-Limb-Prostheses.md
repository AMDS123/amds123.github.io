---
layout: post
title: "Visual Cues to Improve Myoelectric Control of Upper Limb Prostheses"
date: 2017-08-29 16:59:19
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification
author: Andrea Gigli, Arjan Gijsberts, Valentina Gregori, Matteo Cognolato, Manfredo Atzori, Barbara Caputo
mathjax: true
---

* content
{:toc}

##### Abstract
The instability of myoelectric signals over time complicates their use to control highly articulated prostheses. To address this problem, studies have tried to combine surface electromyography with modalities that are less affected by the amputation and environment, such as accelerometry or gaze information. In the latter case, the hypothesis is that a subject looks at the object he or she intends to manipulate and that knowing this object's affordances allows to constrain the set of possible grasps. In this paper, we develop an automated way to detect stable fixations and show that gaze information is indeed helpful in predicting hand movements. In our multimodal approach, we automatically detect stable gazes and segment an object of interest around the subject's fixation in the visual frame. The patch extracted around this object is subsequently fed through an off-the-shelf deep convolutional neural network to obtain a high level feature representation, which is then combined with traditional surface electromyography in the classification stage. Tests have been performed on a dataset acquired from five intact subjects who performed ten types of grasps on various objects as well as in a functional setting. They show that the addition of gaze information increases the classification accuracy considerably. Further analysis demonstrates that this improvement is consistent for all grasps and concentrated during the movement onset and offset.

##### Abstract (translated by Google)
随着时间的推移肌电信号的不稳定性使其用于控制​​高度铰接的假体变得复杂。为了解决这个问题，研究人员尝试将表面肌电图与受截肢和环境影响较小的模式（如加速度计或凝视信息）结合起来。在后一种情况下，假设是一个主体看着他或她想要操纵的对象，知道这个对象的可供性允许限制一组可能的抓握。在本文中，我们开发了一种自动化的方法来检测稳定的注视，并显示凝视信息确实有助于预测手部动作。在我们的多模式方法中，我们自动检测稳定的凝视，并在视觉框架中围绕主体的固定分割感兴趣的对象。随后通过现成的深度卷积神经网络提取周围提取的贴片，获得高级特征表示，然后在分类阶段将其与传统的表面肌电图相结合。已经对从五个完整的对象获得的数据集进行了测试，这些对象在各种对象以及功能设置上执行了十种类型的抓握。他们表明，增加凝视信息大大提高了分类精度。进一步分析表明，这种改善是一致的所有抓住和集中在运动开始和抵消。

##### URL
[https://arxiv.org/abs/1709.02236](https://arxiv.org/abs/1709.02236)

##### PDF
[https://arxiv.org/pdf/1709.02236](https://arxiv.org/pdf/1709.02236)

