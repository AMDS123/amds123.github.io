---
layout: post
title: "Learnable Visual Markers"
date: 2016-10-28 14:31:02
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Oleg Grinchuk, Vadim Lebedev, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new approach to designing visual markers (analogous to QR-codes, markers for augmented reality, and robotic fiducial tags) based on the advances in deep generative networks. In our approach, the markers are obtained as color images synthesized by a deep network from input bit strings, whereas another deep network is trained to recover the bit strings back from the photos of these markers. The two networks are trained simultaneously in a joint backpropagation process that takes characteristic photometric and geometric distortions associated with marker fabrication and marker scanning into account. Additionally, a stylization loss based on statistics of activations in a pretrained classification network can be inserted into the learning in order to shift the marker appearance towards some texture prototype. In the experiments, we demonstrate that the markers obtained using our approach are capable of retaining bit strings that are long enough to be practical. The ability to automatically adapt markers according to the usage scenario and the desired capacity as well as the ability to combine information encoding with artistic stylization are the unique properties of our approach. As a byproduct, our approach provides an insight on the structure of patterns that are most suitable for recognition by ConvNets and on their ability to distinguish composite patterns.

##### Abstract (translated by Google)
基于深度生成网络的发展，我们提出了一种设计视觉标记的新方法（类似于QR码，增强现实的标记和机器人基准标签）。在我们的方法中，标记是通过深度网络从输入比特串合成的彩色图像获得的，而另一个深度网络被训练以从这些标记的照片中恢复比特串。这两个网络在联合反向传播过程中同时受到训练，该过程需要考虑与标记制作和标记扫描相关的特征光度和几何失真。此外，基于预训练分类网络中的激活统计的程式化损失可以被插入到学习中，以便将标记外观转向一些纹理原型。在实验中，我们证明使用我们的方法获得的标记能够保留足够长的位串以实用。根据使用场景和所需容量自动调整标记的能力以及将信息编码与艺术风格相结合的能力是我们方法的独特属性。作为副产品，我们的方法提供了最适合ConvNets识别的模式结构以及区分复合模式的能力。

##### URL
[https://arxiv.org/abs/1610.09237](https://arxiv.org/abs/1610.09237)

##### PDF
[https://arxiv.org/pdf/1610.09237](https://arxiv.org/pdf/1610.09237)

