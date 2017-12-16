---
layout: post
title: "Binary-decomposed DCNN for accelerating computation and compressing model without retraining"
date: 2017-09-14 12:30:41
categories: arXiv_CV
tags: arXiv_CV CNN Inference Classification Recognition
author: Ryuji Kamiya, Takayoshi Yamashita, Mitsuru Ambai, Ikuro Sato, Yuji Yamauchi, Hironobu Fujiyoshi
mathjax: true
---

* content
{:toc}

##### Abstract
Recent trends show recognition accuracy increasing even more profoundly. Inference process of Deep Convolutional Neural Networks (DCNN) has a large number of parameters, requires a large amount of computation, and can be very slow. The large number of parameters also require large amounts of memory. This is resulting in increasingly long computation times and large model sizes. To implement mobile and other low performance devices incorporating DCNN, model sizes must be compressed and computation must be accelerated. To that end, this paper proposes Binary-decomposed DCNN, which resolves these issues without the need for retraining. Our method replaces real-valued inner-product computations with binary inner-product computations in existing network models to accelerate computation of inference and decrease model size without the need for retraining. Binary computations can be done at high speed using logical operators such as XOR and AND, together with bit counting. In tests using AlexNet with the ImageNet classification task, speed increased by a factor of 1.79, models were compressed by approximately 80%, and increase in error rate was limited to 1.20%. With VGG-16, speed increased by a factor of 2.07, model sizes decreased by 81%, and error increased by only 2.16%.

##### Abstract (translated by Google)
最近的趋势显示，识别精度的提高更为深刻。深度卷积神经网络（DCNN）的推理过程有大量的参数，需要大量的计算，而且速度很慢。大量的参数也需要大量的内存。这导致计算时间越来越长，模型尺寸越来越大。为了实现包含DCNN的移动设备和其他低性能设备，必须压缩模型大小并加速计算。为此，本文提出了二进制分解DCNN，可以解决这些问题，而不需要再培训。我们的方法用现有网络模型中的二进制内积计算代替实值内积计算，以加速推理的计算并减少模型大小，而不需要重新训练。二进制计算可以使用逻辑运算符（如XOR和AND）以及位计数来高速完成。在使用AlexNet进行ImageNet分类任务的测试中，速度提高了1.79倍，模型压缩了大约80％，错误率提高了1.20％。使用VGG-16，速度提高了2.07倍，模型尺寸减少了81％，误差仅增加了2.16％。

##### URL
[https://arxiv.org/abs/1709.04731](https://arxiv.org/abs/1709.04731)

##### PDF
[https://arxiv.org/pdf/1709.04731](https://arxiv.org/pdf/1709.04731)

