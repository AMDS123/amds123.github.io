---
layout: post
title: "Sistema de Navegação Autônomo Baseado em Visão Computacional"
date: 2017-10-17 22:37:07
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Michel Conrado Cardoso Meneses
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous robots are used as the tool to solve many kinds of problems, such as environmental mapping and monitoring. Either for adverse conditions related to the human presence or even for the need to reduce costs, it is certain that many efforts have been made to develop robots with an increasingly high level of autonomy. They must be capable of locomotion through dynamic environments, without human operators or assistant systems' help. It is noted, thus, that the form of perception and modeling of the environment becomes significantly relevant to navigation. Among the main sensing methods are those based on vision. Through this, it is possible to create highly-detailed models about the environment, since many characteristics can be measured, such as texture, color, and illumination. However, the most accurate vision-based navigation techniques are computationally expensive to run on low-cost mobile platforms. Therefore, the goal of this work was to develop a low-cost robot, controlled by a Raspberry Pi, whose navigation system is based on vision. For this purpose, the strategy used consisted in identifying obstacles via optical flow pattern recognition. Through this signal, it is possible to infer the relative displacement between the robot and other elements in the environment. Its estimation was done using the Lucas-Kanade algorithm, which can be executed by the Raspberry Pi without harming its performance. Finally, an SVM based classifier was used to identify patterns of this signal associated with obstacles movement. The developed system was evaluated considering its execution over an optical flow pattern dataset extracted from a real navigation environment. In the end, it was verified that the processing frequency of the system was superior to the others. Furthermore, its accuracy and acquisition cost were, respectively, higher and lower than most of the cited works.

##### Abstract (translated by Google)
自主机器人作为解决环境制图和监测等多种问题的工具。无论是与人的存在相关的不利条件，还是降低成本的需要，可以肯定的是，已经做出了许多努力来发展具有越来越高的自治水平的机器人。他们必须能够通过动态的环境进行移动，而不需要操作人员或助手系统的帮助。因此，人们注意到环境的感知和建模的形式与导航显着相关。主要的感知方法之一是基于视觉的方法。通过这样，可以创建关于环境的高度详细的模型，因为可以测量许多特征，例如纹理，颜色和照明。然而，最准确的基于视觉的导航技术在低成本的移动平台上运行起来在计算上是昂贵的。因此，这项工作的目标是开发一种由Raspberry Pi控制的低成本机器人，其导航系统是基于视觉的。为此，所使用的策略是通过光流模式识别识别障碍物。通过这个信号，可以推断机器人与环境中的其他元件之间的相对位移。它的估计是使用Lucas-Kanade算法完成的，该算法可以在不损害性能的情况下由Raspberry Pi执行。最后，使用基于SVM的分类器来识别与障碍物移动相关的该信号的模式。考虑到在实际导航环境中提取的光流模式数据集的执行情况，开发的系统被评估。最后，验证了系统的处理频率优于其他系统。此外，其准确性和购置成本分别高于和低于大多数引用的作品。

##### URL
[https://arxiv.org/abs/1710.06518](https://arxiv.org/abs/1710.06518)

##### PDF
[https://arxiv.org/pdf/1710.06518](https://arxiv.org/pdf/1710.06518)

