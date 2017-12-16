---
layout: post
title: "Single Image Action Recognition using Semantic Body Part Actions"
date: 2016-12-14 07:54:55
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Zhichen Zhao, Huimin Ma, Shaodi You
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel single image action recognition algorithm which is based on the idea of semantic body part actions. Unlike existing bottom up methods, we argue that the human action is a combination of meaningful body part actions. In detail, we divide human body into five parts: head, torso, arms, hands and legs. And for each of the body parts, we define several semantic body part actions, e.g., hand holding, hand waving. These semantic body part actions are strongly related to the body actions, e.g., writing, and jogging. Based on the idea, we propose a deep neural network based system: first, body parts are localized by a Semi-FCN network. Second, for each body parts, a Part Action Res-Net is used to predict semantic body part actions. And finally, we use SVM to fuse the body part actions and predict the entire body action. Experiments on two dataset: PASCAL VOC 2012 and Stanford-40 report mAP improvement from the state-of-the-art by 3.8% and 2.6% respectively.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于语义身体部分动作思想的新颖的单幅图像动作识别算法。与现有的自下而上的方法不同，我们认为人的行为是有意义的身体部位行为的组合。详细地说，我们把人体分成五部分：头部，躯干，手臂，手和腿。对于每个身体部位，我们定义了几个语义身体部位的动作，例如手握，挥手。这些语义身体部位动作与身体动作强烈相关，例如写作和慢跑。基于这个思想，我们提出了一个基于深度神经网络的系统：首先，身体部位通过半FCN网络进行本地化。其次，对于每个身体部位，使用Part Action Res-Net来预测语义身体部位动作。最后，我们使用SVM来融合身体部位的动作并预测整个身体动作。两个数据集的实验：PASCAL VOC 2012和Stanford-40分别报告最新的mAP和3.8％和2.6％。

##### URL
[https://arxiv.org/abs/1612.04520](https://arxiv.org/abs/1612.04520)

##### PDF
[https://arxiv.org/pdf/1612.04520](https://arxiv.org/pdf/1612.04520)

