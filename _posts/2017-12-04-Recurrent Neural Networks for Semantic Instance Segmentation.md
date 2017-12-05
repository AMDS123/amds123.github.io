---
layout: post
title:  'Recurrent Neural Networks for Semantic Instance Segmentation'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Amaia Salvador, Miriam Bellver, Manel Baradad, Ferran Marques, Jordi Torres, Xavier Giro-i-Nieto
---

* content
{:toc}

##### Abstract
We present a recurrent model for semantic instance segmentation that sequentially generates pairs of masks and their associated class probabilities for every object in an image. Our proposed system is trainable end-to-end, does not require post-processing steps on its output and is conceptually simpler than current methods relying on object proposals. We observe that our model learns to follow a consistent pattern to generate object sequences, which correlates with the activations learned in the encoder part of our network. We achieve competitive results on three different instance segmentation benchmarks (Pascal VOC 2012, Cityscapes and CVPPP Plant Leaf Segmentation). Code is available at https://imatge-upc.github.io/rsis .

##### Abstract (translated by Google)
我们提出了一个经常性的语义实例分割模型，为图像中的每个对象顺序生成一对掩码及其相关的类概率。我们提出的系统是可端到端的可训练的，不需要后处理步骤的输出，在概念上比依靠对象建议的方法简单。我们观察到，我们的模型学习遵循一致的模式来生成对象序列，这与在我们的网络的编码器部分中学习到的激活相关。我们在三个不同的实例分段基准（Pascal VOC 2012，Cityscapes和CVPPP植物叶片分割）上获得了有竞争力的结果。代码可在https://imatge-upc.github.io/rsis上找到。

