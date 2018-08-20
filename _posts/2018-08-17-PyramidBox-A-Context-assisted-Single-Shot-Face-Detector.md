---
layout: post
title: "PyramidBox: A Context-assisted Single Shot Face Detector"
date: 2018-08-17 02:43:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Prediction Detection Face_Detection
author: Xu Tang, Daniel K. Du, Zeqiang He, Jingtuo Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Face detection has been well studied for many years and one of remaining challenges is to detect small, blurred and partially occluded faces in uncontrolled environment. This paper proposes a novel context-assisted single shot face detector, named \emph{PyramidBox} to handle the hard face detection problem. Observing the importance of the context, we improve the utilization of contextual information in the following three aspects. First, we design a novel context anchor to supervise high-level contextual feature learning by a semi-supervised method, which we call it PyramidAnchors. Second, we propose the Low-level Feature Pyramid Network to combine adequate high-level context semantic feature and Low-level facial feature together, which also allows the PyramidBox to predict faces of all scales in a single shot. Third, we introduce a context-sensitive structure to increase the capacity of prediction network to improve the final accuracy of output. In addition, we use the method of Data-anchor-sampling to augment the training samples across different scales, which increases the diversity of training data for smaller faces. By exploiting the value of context, PyramidBox achieves superior performance among the state-of-the-art over the two common face detection benchmarks, FDDB and WIDER FACE. Our code is available in PaddlePaddle: \href{https://github.com/PaddlePaddle/models/tree/develop/fluid/face_detection}{\url{https://github.com/PaddlePaddle/models/tree/develop/fluid/face_detection}}.

##### Abstract (translated by Google)
多年来人脸检测已经得到很好的研究，其中一个挑战是在不受控制的环境中检测小的，模糊的和部分遮挡的面部。本文提出了一种新颖的上下文辅助单镜头人脸检测器，命名为\ emph {PyramidBox}来处理硬面检测问题。观察背景的重要性，我们在以下三个方面提高了背景信息的利用率。首先，我们设计了一个新的上下文锚点，通过半监督方法监督高级语境特征学习，我们将其称为PyramidAnchors。其次，我们提出了低级特征金字塔网络，将足够的高级语境语义特征和低级人脸特征结合在一起，这也允许PyramidBox在单个镜头中预测所有音阶的面部。第三，我们引入了一个上下文敏感的结构来增加预测网络的容量，以提高输出的最终准确性。此外，我们使用数据锚点采样的方法来增加不同尺度的训练样本，这增加了较小面部的训练数据的多样性。通过利用上下文的价值，PyramidBox在两种常见的人脸检测基准FDDB和WIDER FACE中实现了最先进的性能。我们的代码在PaddlePaddle中提供：\ href {https://github.com/PaddlePaddle/models/tree/develop/fluid/face_detection} {\ url {https://github.com/PaddlePaddle/models/tree/develop/流体/ face_detection}}。

##### URL
[http://arxiv.org/abs/1803.07737](http://arxiv.org/abs/1803.07737)

##### PDF
[http://arxiv.org/pdf/1803.07737](http://arxiv.org/pdf/1803.07737)

