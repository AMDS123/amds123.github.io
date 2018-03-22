---
layout: post
title: "PyramidBox: A Context-assisted Single Shot Face Detector"
date: 2018-03-21 03:50:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Prediction Detection Face_Detection
author: Xu Tang, Daniel K. Du, Zeqiang He, Jingtuo Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Face detection has been well studied for many years and one of the remaining challenges is to detect small, blurred and partially occluded faces in uncontrolled environment. This paper proposes a novel context-assisted single shot face detector, named PyramidBox, to handle the hard face detection problem. Observing the importance of the context, we improve the utilization of contextual information in the following three aspects. First, we design a novel contextual anchor to supervise high-level contextual feature learning by a semi-supervised method, which we call it PyramidAnchors. Second, we propose the Low-level Feature Pyramid Network to combine adequate high-level contextual semantic feature and Low-level facial feature together, which also allows the PyramidBox to predict faces of all scales in a single shot. Third, we introduce a context-sensitive structure to increase the capacity of prediction network to improve the final accuracy of output. In addition, we use the method of Data-anchor-sampling to augment the training samples across different scales, which increases the diversities of training data for smaller faces. By exploiting the value of context, PyramidBox achieves superior performance among the state-of-the-art on the two common face detection benchmarks, FDDB and WIDER FACE.

##### Abstract (translated by Google)
人脸检测已经进行了很多年的研究，其余挑战之一是在不受控制的环境中检测小的，模糊的和部分遮挡的人脸。本文提出了一种名为PyramidBox的新型上下文辅助单次人脸检测器来处理人脸检测问题。注意语境的重要性，我们在以下三个方面提高语境信息的利用率。首先，我们设计了一种新的上下文锚来监督通过半监督方法进行的高级上下文特征学习，我们称之为PyramidAnchors。其次，我们提出低级特征金字塔网络将足够高级的上下文语义特征和低级别的面部特征组合在一起，这也允许PyramidBox在单个镜头中预测所有比例的面部。第三，我们引入一个上下文敏感结构来增加预测网络的容量，以提高输出的最终准确度。另外，我们使用数据锚定采样的方法来扩展不同尺度的训练样本，这增加了较小面孔的训练数据的多样性。通过利用上下文的价值，PyramidBox在两种常见的人脸检测基准，FDDB和WIDER FACE上实现了最高水平的性能。

##### URL
[http://arxiv.org/abs/1803.07737](http://arxiv.org/abs/1803.07737)

##### PDF
[http://arxiv.org/pdf/1803.07737](http://arxiv.org/pdf/1803.07737)

