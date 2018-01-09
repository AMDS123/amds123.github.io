---
layout: post
title: "Robot Localisation and 3D Position Estimation Using a Free-Moving Camera and Cascaded Convolutional Neural Networks"
date: 2018-01-06 14:50:07
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning Relation
author: Justinas Miseikis, Patrick Knobelreiter, Inka Brijacak, Saeed Yahyanejad, Kyrre Glette, Ole Jakob Elle, Jim Torresen
mathjax: true
---

* content
{:toc}

##### Abstract
Many works in collaborative robotics and human-robot interaction focuses on identifying and predicting human behaviour while considering the information about the robot itself as given. This can be the case when sensors and the robot are calibrated in relation to each other and often the reconfiguration of the system is not possible, or extra manual work is required. We present a deep learning based approach to remove the constraint of having the need for the robot and the vision sensor to be fixed and calibrated in relation to each other. The system learns the visual cues of the robot body and is able to localise it, as well as estimate the position of robot joints in 3D space by just using a 2D color image. The method uses a cascaded convolutional neural network, and we present the structure of the network, describe our own collected dataset, explain the network training and achieved results. A fully trained system shows promising results in providing an accurate mask of where the robot is located and a good estimate of its joints positions in 3D. The accuracy is not good enough for visual servoing applications yet, however, it can be sufficient for general safety and some collaborative tasks not requiring very high precision. The main benefit of our method is the possibility of the vision sensor to move freely. This allows it to be mounted on moving objects, for example, a body of the person or a mobile robot working in the same environment as the robots are operating in.

##### Abstract (translated by Google)
在协作机器人和人机交互方面的许多作品着重于识别和预测人类的行为，同时考虑关于给定的机器人本身的信息。当传感器和机器人彼此相互校准并且通常不可能重新配置系统或需要额外的手动工作时，情况可能如此。我们提出了一种深度学习的方法来消除机器人和视觉传感器需要相互固定和校准的限制。该系统学习机器人的视觉线索，并能够定位它，以及通过使用二维彩色图像估计机器人关节在三维空间中的位置。该方法采用级联卷积神经网络，提出网络结构，描述自己收集的数据集，解释网络训练并取得成果。一个训练有素的系统在提供机器人所在位置的精确掩模以及3D关节位置的良好估计方面显示出有希望的结果。对于视觉伺服应用来说，精确度还不够好，但对于一般的安全性和一些不需要非常高的精度的协作任务来说就足够了。我们的方法的主要好处是视觉传感器可以自由移动。这使得它可以安装在移动的物体上，例如人的身体或移动机器人在与机器人相同的环境中工作。

##### URL
[http://arxiv.org/abs/1801.02025](http://arxiv.org/abs/1801.02025)

##### PDF
[http://arxiv.org/pdf/1801.02025](http://arxiv.org/pdf/1801.02025)

