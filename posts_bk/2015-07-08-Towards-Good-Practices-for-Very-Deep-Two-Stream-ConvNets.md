---
layout: post
title: "Towards Good Practices for Very Deep Two-Stream ConvNets"
date: 2015-07-08 14:00:35
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Limin Wang, Yuanjun Xiong, Zhe Wang, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks have achieved great success for object recognition in still images. However, for action recognition in videos, the improvement of deep convolutional networks is not so evident. We argue that there are two reasons that could probably explain this result. First the current network architectures (e.g. Two-stream ConvNets) are relatively shallow compared with those very deep models in image domain (e.g. VGGNet, GoogLeNet), and therefore their modeling capacity is constrained by their depth. Second, probably more importantly, the training dataset of action recognition is extremely small compared with the ImageNet dataset, and thus it will be easy to over-fit on the training dataset. To address these issues, this report presents very deep two-stream ConvNets for action recognition, by adapting recent very deep architectures into video domain. However, this extension is not easy as the size of action recognition is quite small. We design several good practices for the training of very deep two-stream ConvNets, namely (i) pre-training for both spatial and temporal nets, (ii) smaller learning rates, (iii) more data augmentation techniques, (iv) high drop out ratio. Meanwhile, we extend the Caffe toolbox into Multi-GPU implementation with high computational efficiency and low memory consumption. We verify the performance of very deep two-stream ConvNets on the dataset of UCF101 and it achieves the recognition accuracy of $91.4\%$.

##### Abstract (translated by Google)
深卷积网络在静止图像中的物体识别上取得了巨大的成功。但是，对于视频中的动作识别来说，深度卷积网络的改进并不明显。我们认为有两个原因可以解释这个结果。首先，与图像域中的那些非常深的模型（例如VGGNet，GoogLeNet）相比，当前的网络体系结构（例如，双流ConvNet）相对较浅，并且因此其建模能力受其深度限制。其次，可能更重要的是，与ImageNet数据集相比，动作识别的训练数据集非常小，因此容易过度拟合训练数据集。为了解决这些问题，本报告通过将最近非常深入的体系结构调整到视频领域，提出了非常深入的行动识别双流ConvNets。然而，这种扩展并不容易，因为动作识别的尺寸很小。我们设计了一些非常深入的两流ConvNets的训练，即（i）空间和时间网络的预训练，（ii）较小的学习率，（iii）更多的数据增强技术，（iv）高的下降掉率。同时，我们将Caffe工具箱扩展到多GPU实现，计算效率高，内存消耗低。我们在UCF101的数据集上验证了非常深的两码流ConvNets的性能，达到了$ 91.4 \％$的识别精度。

##### URL
[https://arxiv.org/abs/1507.02159](https://arxiv.org/abs/1507.02159)

##### PDF
[https://arxiv.org/pdf/1507.02159](https://arxiv.org/pdf/1507.02159)

