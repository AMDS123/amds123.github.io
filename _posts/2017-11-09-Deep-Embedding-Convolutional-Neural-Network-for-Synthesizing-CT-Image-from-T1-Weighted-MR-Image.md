---
layout: post
title: "Deep Embedding Convolutional Neural Network for Synthesizing CT Image from T1-Weighted MR Image"
date: 2017-11-09 04:06:13
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN
author: Lei Xiang, Qian Wang, Xiyao Jin, Dong Nie, Yu Qiao, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, more and more attention is drawn to the field of medical image synthesis across modalities. Among them, the synthesis of computed tomography (CT) image from T1-weighted magnetic resonance (MR) image is of great importance, although the mapping between them is highly complex due to large gaps of appearances of the two modalities. In this work, we aim to tackle this MR-to-CT synthesis by a novel deep embedding convolutional neural network (DECNN). Specifically, we generate the feature maps from MR images, and then transform these feature maps forward through convolutional layers in the network. We can further compute a tentative CT synthesis from the midway of the flow of feature maps, and then embed this tentative CT synthesis back to the feature maps. This embedding operation results in better feature maps, which are further transformed forward in DECNN. After repeat-ing this embedding procedure for several times in the network, we can eventually synthesize a final CT image in the end of the DECNN. We have validated our proposed method on both brain and prostate datasets, by also compar-ing with the state-of-the-art methods. Experimental results suggest that our DECNN (with repeated embedding op-erations) demonstrates its superior performances, in terms of both the perceptive quality of the synthesized CT image and the run-time cost for synthesizing a CT image.

##### Abstract (translated by Google)
近来，越来越多的关注医学图像综合模式领域。其中，从T1加权磁共振（MR）图像合成计算机断层扫描（CT）图像是非常重要的，虽然由于这两种方式的出现间隙大，它们之间的映射非常复杂。在这项工作中，我们的目标是通过一个新的深度嵌入卷积神经网络（DECNN）来解决这个MR到CT的合成问题。具体而言，我们从MR图像生成特征映射，然后通过网络中的卷积层向前转换这些特征映射。我们可以从特征地图流的中途进一步计算一个初步的CT合成，然后将这个临时的CT合成嵌入到特征地图中。这种嵌入操作产生更好的特征图，在DECNN中进一步转换。在网络中多次重复嵌入过程之后，我们最终可以在DECNN的末尾合成最终的CT图像。我们通过与最先进的方法进行比较，验证了我们提出的脑和前列腺数据集的方法。实验结果表明，我们的DECNN（重复嵌入操作）在合成CT图像的感知质量和合成CT图像的运行时间成本方面表现出优越的性能。

##### URL
[https://arxiv.org/abs/1709.02073](https://arxiv.org/abs/1709.02073)

##### PDF
[https://arxiv.org/pdf/1709.02073](https://arxiv.org/pdf/1709.02073)

