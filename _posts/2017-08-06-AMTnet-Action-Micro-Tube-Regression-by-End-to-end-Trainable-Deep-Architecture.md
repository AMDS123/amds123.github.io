---
layout: post
title: "AMTnet: Action-Micro-Tube Regression by End-to-end Trainable Deep Architecture"
date: 2017-08-06 14:18:44
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Suman Saha, Gurkirt Singh, Fabio Cuzzolin
mathjax: true
---

* content
{:toc}

##### Abstract
Dominant approaches to action detection can only provide sub-optimal solutions to the problem, as they rely on seeking frame-level detections, to later compose them into "action tubes" in a post-processing step. With this paper we radically depart from current practice, and take a first step towards the design and implementation of a deep network architecture able to classify and regress whole video subsets, so providing a truly optimal solution of the action detection problem. In this work, in particular, we propose a novel deep net framework able to regress and classify 3D region proposals spanning two successive video frames, whose core is an evolution of classical region proposal networks (RPNs). As such, our 3D-RPN net is able to effectively encode the temporal aspect of actions by purely exploiting appearance, as opposed to methods which heavily rely on expensive flow maps. The proposed model is end-to-end trainable and can be jointly optimised for action localisation and classification in a single step. At test time the network predicts "micro-tubes" encompassing two successive frames, which are linked up into complete action tubes via a new algorithm which exploits the temporal encoding learned by the network and cuts computation time by 50%. Promising results on the J-HMDB-21 and UCF-101 action detection datasets show that our model does outperform the state-of-the-art when relying purely on appearance.

##### Abstract (translated by Google)
主流的行为检测方法只能提供次优的解决方案，因为他们依赖寻求帧级别的检测，以后在后处理步骤中将其组合成“行动管”。本文从根本上偏离了目前的实践，为深度网络体系结构的设计和实现迈出了第一步，该体系结构能够对整个视频子集进行分类和回归，从而为动作检测问题提供真正的最优解决方案。特别是在这项工作中，我们提出了一个新的深层网络框架，能够对两个连续视频帧的3D地区提案进行回归和分类，其核心是经典地区提案网络（RPNs）的演变。因此，我们的3D-RPN网络能够通过纯粹利用外观来有效地编码行为的时间方面，而不是严重依赖昂贵的流程图的方法。所提出的模型是端到端可训练的，并且可以在一个步骤中针对动作定位和分类进行联合优化。在测试时间，网络预测包含两个连续帧的“微管”，通过利用网络学习的时间编码并将计算时间减少50％的新算法连接成完整的操作管。 J-HMDB-21和UCF-101动作检测数据集的有希望的结果表明，我们的模型在纯粹依靠外观时确实超过了最新的技术水平。

##### URL
[https://arxiv.org/abs/1704.04952](https://arxiv.org/abs/1704.04952)

##### PDF
[https://arxiv.org/pdf/1704.04952](https://arxiv.org/pdf/1704.04952)

