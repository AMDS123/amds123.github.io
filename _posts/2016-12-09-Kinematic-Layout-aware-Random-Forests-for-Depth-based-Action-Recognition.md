---
layout: post
title: "Kinematic-Layout-aware Random Forests for Depth-based Action Recognition"
date: 2016-12-09 11:32:54
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Relation Recognition
author: Seungryul Baek, Zhiyuan Shi, Masato Kawade, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we tackle the problem of 24 hours-monitoring patient actions in a ward such as "stretching an arm out of the bed", "falling out of the bed", where temporal movements are subtle or significant. In the concerned scenarios, the relations between scene layouts and body kinematics (skeletons) become important cues to recognize actions; however they are hard to be secured at a testing stage. To address this problem, we propose a kinematic-layout-aware random forest which takes into account the kinematic-layout (\ie layout and skeletons), to maximize the discriminative power of depth image appearance. We integrate the kinematic-layout in the split criteria of random forests to guide the learning process by 1) determining the switch to either the depth appearance or the kinematic-layout information, and 2) implicitly closing the gap between two distributions obtained by the kinematic-layout and the appearance, when the kinematic-layout appears useful. The kinematic-layout information is not required for the test data, thus called "privileged information prior". The proposed method has also been testified in cross-view settings, by the use of view-invariant features and enforcing the consistency among synthetic-view data. Experimental evaluations on our new dataset PATIENT, CAD-60 and UWA3D (multiview) demonstrate that our method outperforms various state-of-the-arts.

##### Abstract (translated by Google)
在本文中，我们解决了24小时监控病房病人行动的问题，如“伸出床”，“从床上跳下来”，这些时间动作是微妙的或显着的。在相关场景中，场景布局与身体运动学（骨架）之间的关系成为识别动作的重要线索;但是在测试阶段很难保证。为了解决这个问题，我们提出了一个运动学布局意识随机森林，考虑到运动学布局（即布局和骨架），以最大限度地提高深度图像外观的判别力。我们将运动学布局集成在随机森林的分裂标准中，以指导学习过程：1）确定切换到深度外观或运动学布局信息; 2）隐含地关闭通过运动学获得的两个分布之间的间隙布局和外观，当运动学布局显示有用。测试数据不需要运动学布局信息，因此称之为“优先信息”。所提出的方法也已经在交叉视图设置中得到证实，通过使用视图不变特征和强化合成视图数据之间的一致性。对我们的新数据集PATIENT，CAD-60和UWA3D（多视图）的实验评估表明，我们的方法胜过了各种各样的艺术。

##### URL
[https://arxiv.org/abs/1607.06972](https://arxiv.org/abs/1607.06972)

##### PDF
[https://arxiv.org/pdf/1607.06972](https://arxiv.org/pdf/1607.06972)

