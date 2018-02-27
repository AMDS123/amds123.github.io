---
layout: post
title: "Adaptive Deep Learning through Visual Domain Localization"
date: 2018-02-24 10:36:51
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning
author: Gabriele Angeletti, Barbara Caputo, Tatiana Tommasi
mathjax: true
---

* content
{:toc}

##### Abstract
A commercial robot, trained by its manufacturer to recognize a predefined number and type of objects, might be used in many settings, that will in general differ in their illumination conditions, background, type and degree of clutter, and so on. Recent computer vision works tackle this generalization issue through domain adaptation methods, assuming as source the visual domain where the system is trained and as target the domain of deployment. All approaches assume to have access to images from all classes of the target during training, an unrealistic condition in robotics applications. We address this issue proposing an algorithm that takes into account the specific needs of robot vision. Our intuition is that the nature of the domain shift experienced mostly in robotics is local. We exploit this through the learning of maps that spatially ground the domain and quantify the degree of shift, embedded into an end-to-end deep domain adaptation architecture. By explicitly localizing the roots of the domain shift we significantly reduce the number of parameters of the architecture to tune, we gain the flexibility necessary to deal with subset of categories in the target domain at training time, and we provide a clear feedback on the rationale behind any classification decision, which can be exploited in human-robot interactions. Experiments on two different settings of the iCub World database confirm the suitability of our method for robot vision.

##### Abstract (translated by Google)
商业机器人，由其制造商培训以识别预定义数量和类型的物体，可用于许多设置中，这些设置通常在其照明条件，背景，类型和杂波程度等方面不同。最近的计算机视觉工程通过域适应方法解决了这个泛化问题，假设源是系统被训练的可视域和目标域的部署。所有的方法都假设在训练期间可以从目标的所有级别访问图像，这在机器人应用中是不现实的。我们针对这个问题提出了一种算法，该算法考虑了机器人视觉的特定需求。我们的直觉是，主要在机器人领域发生的领域转变的本质是局部的。我们通过学习地图来学习这些知识，这些地图在空间上对领域进行研究并量化移动的程度，并嵌入到端到端的深层领域适应架构中。通过明确定位域转移的根源，我们显着减少了要调整的体系结构的参数数量，我们获得了在训练时间处理目标域中的子类别所需的灵活性，并且我们提供了有关理论基础的明确反馈在任何分类决策之后，可以在人机交互中利用。 iCub World数据库的两个不同设置的实验证实了我们的方法适用于机器人视觉。

##### URL
[http://arxiv.org/abs/1802.08833](http://arxiv.org/abs/1802.08833)

##### PDF
[http://arxiv.org/pdf/1802.08833](http://arxiv.org/pdf/1802.08833)

