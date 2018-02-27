---
layout: post
title: "Bonnet: An Open-Source Training and Deployment Framework for Semantic Segmentation in Robotics using CNNs"
date: 2018-02-25 06:47:30
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Face CNN Semantic_Segmentation Prediction
author: Andres Milioto, Cyrill Stachniss
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to interpret a scene is an important capability for a robot that is supposed to interact with its environment. The knowledge of what is in front of the robot is, for example, key to navigation, manipulation, or planning. Semantic segmentation labels each pixel of an image with a class label and thus provides a detailed semantic annotation of the surroundings to the robot. Convolutional neural networks (CNNs) became popular methods for addressing this type of problem. The available software for training and the integration of CNNs in real robots, however, is quite fragmented and difficult to use for non-experts, despite the availability of several high-quality open-source frameworks for neural network implementation and training. In this paper, we propose a novel framework called Bonnet, which addresses this fragmentation problem. It provides a modular approach to simplify the training of a semantic segmentation CNN independently of the used dataset and the intended task. Furthermore, we also address the deployment on a real robotic platform. Thus, we do not propose a new CNN approach in this paper. Instead, we provide a stable and easy-to-use tool to make this technology more approachable in the context of autonomous systems. In this sense, we aim at closing a gap between computer vision research and its use in robotics research. We provide an open-source framework for training and deployment. The training interface is implemented in Python using TensorFlow and the deployment interface provides a C++ library that can be easily integrated in an existing robotics codebase, a ROS node, and two standalone applications for label prediction in images and videos.

##### Abstract (translated by Google)
解释场景的能力对于一个应该与环境相互作用的机器人来说是一个重要的能力。例如，关于机器人前方的知识是导航，操纵或计划的关键。语义分割使用类标签对图像的每个像素进行标记，从而为机器人提供周围环境的详细语义标注。卷积神经网络（CNN）成为解决这类问题的常用方法。然而，尽管可用于神经网络实施和培训的几个高质量开放源代码框架，但用于培训和将CNN集成到真实机器人中的可用软件非常分散且难以用于非专家。在本文中，我们提出了一个名为Bonnet的新框架，它解决了这个碎片问题。它提供了一种模块化的方法来简化语义分割CNN的训练，而不依赖于使用的数据集和预期的任务。此外，我们还致力于在真正的机器人平台上进行部署。因此，我们不在本文中提出新的CNN方法。相反，我们提供了一个稳定且易于使用的工具，使这种技术在自治系统环境下更易于使用。从这个意义上说，我们的目标是缩小计算机视觉研究与其在机器人研究中的应用之间的差距。我们提供了用于培训和部署的开源框架。培训界面使用TensorFlow在Python中实现，部署界面提供了一个C ++库，可以轻松地将其集成到现有的机器人代码库，ROS节点和两个用于图像和视频中标签预测的独立应用程序中。

##### URL
[http://arxiv.org/abs/1802.08960](http://arxiv.org/abs/1802.08960)

##### PDF
[http://arxiv.org/pdf/1802.08960](http://arxiv.org/pdf/1802.08960)

