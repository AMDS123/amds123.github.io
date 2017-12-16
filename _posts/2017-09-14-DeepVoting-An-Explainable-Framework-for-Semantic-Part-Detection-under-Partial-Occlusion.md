---
layout: post
title: "DeepVoting: An Explainable Framework for Semantic Part Detection under Partial Occlusion"
date: 2017-09-14 01:37:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Classification Detection Relation
author: Zhishuai Zhang, Cihang Xie, Jianyu Wang, Lingxi Xie, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the task of detecting semantic parts of an object. This is very important in computer vision, as it provides the possibility to parse an object as human do, and helps us better understand object detection algorithms. Also, detecting semantic parts is very challenging especially when the parts are partially or fully occluded. In this scenario, the popular proposal-based methods like Faster-RCNN often produce unsatisfactory results, because both the proposal extraction and classification stages may be confused by the irrelevant occluders. To this end, we propose a novel detection framework, named DeepVoting, which accumulates local visual cues, called visual concepts (VC), to locate the semantic parts. Our approach involves adding two layers after the intermediate outputs of a deep neural network. The first layer is used to extract VC responses, and the second layer performs a voting mechanism to capture the spatial relationship between VC's and semantic parts. The benefit is that each semantic part is supported by multiple VC's. Even if some of the supporting VC's are missing due to occlusion, we can still infer the presence of the target semantic part using the remaining ones. To avoid generating an exponentially large training set to cover all occlusion cases, we train our model without seeing occlusion and transfer the learned knowledge to deal with occlusions. This setting favors learning the models which are naturally robust and adaptive to occlusions instead of over-fitting the occlusion patterns in the training data. In experiments, DeepVoting shows significantly better performance on semantic part detection in occlusion scenarios, compared with Faster-RCNN, with one order of magnitude fewer parameters and 2.5x testing speed. In addition, DeepVoting is explainable as the detection result can be diagnosed via looking up the voted VC's.

##### Abstract (translated by Google)
在本文中，我们研究检测对象的语义部分的任务。这在计算机视觉中非常重要，因为它提供了像人一样解析对象的可能性，并且帮助我们更好地理解对象检测算法。而且，检测语义部分是非常具有挑战性的，特别是当部分或全部被遮挡时。在这种情况下，像Faster-RCNN这样的流行的基于提议的方法通常会产生不令人满意的结果，因为提案提取和分类阶段可能被不相关的遮蔽者混淆。为此，我们提出了一种名为DeepVoting的新型检测框架，它将局部视觉线索（称为视觉概念（VC））进行累加以定位语义部分。我们的方法涉及在深度神经网络的中间输出之后添加两层。第一层用于提取VC响应，第二层用于执行投票机制来捕获VC和语义部分之间的空间关系。好处是每个语义部分都被多个VC支持。即使某些支持VC由于遮挡而丢失，我们仍然可以使用剩余的部分来推断目标语义部分的存在。为了避免产生一个指数大的训练集来覆盖所有的遮挡情况，我们训练我们的模型而不会看到遮挡，并把学习的知识传递给遮挡。这种设置有利于学习模型，这些模型自然是鲁棒的，并适应于遮挡，而不是过度拟合训练数据中的遮挡模式。在实验中，与Faster-RCNN相比，DeepVoting在遮挡场景下的语义部分检测性能显着提高，参数少一个数量级，测试速度为2.5倍。此外，DeepVoting可以解释，因为检测结果可以通过查找投票的VC来诊断。

##### URL
[https://arxiv.org/abs/1709.04577](https://arxiv.org/abs/1709.04577)

##### PDF
[https://arxiv.org/pdf/1709.04577](https://arxiv.org/pdf/1709.04577)

