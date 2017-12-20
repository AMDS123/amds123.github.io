---
layout: post
title: "Learning Fixation Point Strategy for Object Detection and Classification"
date: 2017-12-19 12:28:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Classification Detection
author: Jie Lyu, Zejian Yuan, Dapeng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel recurrent attentional structure to localize and recognize objects jointly. The network can learn to extract a sequence of local observations with detailed appearance and rough context, instead of sliding windows or convolutions on the entire image. Meanwhile, those observations are fused to complete detection and classification tasks. On training, we present a hybrid loss function to learn the parameters of the multi-task network end-to-end. Particularly, the combination of stochastic and object-awareness strategy, named SA, can select more abundant context and ensure the last fixation close to the object. In addition, we build a real-world dataset to verify the capacity of our method in detecting the object of interest including those small ones. Our method can predict a precise bounding box on an image, and achieve high speed on large images without pooling operations. Experimental results indicate that the proposed method can mine effective context by several local observations. Moreover, the precision and speed are easily improved by changing the number of recurrent steps. Finally, we will open the source code of our proposed approach.

##### Abstract (translated by Google)
我们提出了一个新颖的反复注意结构来共同定位和识别对象。网络可以学习提取具有详细的外观和粗糙的上下文的本地观察序列，而不是在整个图像上滑动窗口或卷积。同时，这些观察被融合以完成检测和分类任务。在训练中，我们提出了混合丢失函数来学习端到端多任务网络的参数。特别是，随机和对象感知策略的组合SA可以选择更丰富的上下文，并确保最后的注视靠近对象。另外，我们建立了一个真实世界的数据集来验证我们的方法在检测感兴趣的对象（包括那些小的对象）方面的能力。我们的方法可以预测图像上的精确边界框，并且在没有汇集操作的情况下在大图像上实现高速。实验结果表明，该方法可以通过多次局部观测来挖掘有效的背景。而且，通过改变重复步骤的数量，容易提高精度和速度。最后，我们将打开我们提出的方法的源代码。

##### URL
[http://arxiv.org/abs/1712.06897](http://arxiv.org/abs/1712.06897)

##### PDF
[http://arxiv.org/pdf/1712.06897](http://arxiv.org/pdf/1712.06897)

