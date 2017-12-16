---
layout: post
title: "Target-Quality Image Compression with Recurrent, Convolutional Neural Networks"
date: 2017-05-18 16:44:31
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Michele Covell, Nick Johnston, David Minnen, Sung Jin Hwang, Joel Shor, Saurabh Singh, Damien Vincent, George Toderici
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a stop-code tolerant (SCT) approach to training recurrent convolutional neural networks for lossy image compression. Our methods introduce a multi-pass training method to combine the training goals of high-quality reconstructions in areas around stop-code masking as well as in highly-detailed areas. These methods lead to lower true bitrates for a given recursion count, both pre- and post-entropy coding, even using unstructured LZ77 code compression. The pre-LZ77 gains are achieved by trimming stop codes. The post-LZ77 gains are due to the highly unequal distributions of 0/1 codes from the SCT architectures. With these code compressions, the SCT architecture maintains or exceeds the image quality at all compression rates compared to JPEG and to RNN auto-encoders across the Kodak dataset. In addition, the SCT coding results in lower variance in image quality across the extent of the image, a characteristic that has been shown to be important in human ratings of image quality

##### Abstract (translated by Google)
我们引入了一种停止代码容忍（SCT）方法来训练用于有损图像压缩的递归卷积神经网络。我们的方法引入了一种多通道训练方法来结合停止代码遮蔽区域以及高度详细区域中高质量重建的训练目标。即使使用非结构化的LZ77代码压缩，这些方法导致对于给定的递归计数，熵编码之前和之后的真比特率都较低。 LZ77之前的增益是通过修整停止码来实现的。 LZ77之后的收益是由于SCT架构0/1代码的高度不均匀分布造成的。通过这些代码压缩，SCT体系结构在所有压缩率下都能保持或超过图像质量，而JPEG和整个柯达数据集的RNN自动编码器都能保持图像质量。另外，SCT编码导致图像质量在整个图像范围内变化较小，这一特性在图像质量的人类评级中已被证明是重要的

##### URL
[https://arxiv.org/abs/1705.06687](https://arxiv.org/abs/1705.06687)

##### PDF
[https://arxiv.org/pdf/1705.06687](https://arxiv.org/pdf/1705.06687)

