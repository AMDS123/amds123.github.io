---
layout: post
title: "Adversarial Generation of Training Examples: Applications to Moving Vehicle License Plate Recognition"
date: 2017-11-10 23:33:46
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN CNN RNN Classification Recognition
author: Xinlong Wang, Zhipeng Man, Mingyu You, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GAN) have attracted much research attention recently, leading to impressive results for natural image generation. However, to date little success was observed in using GAN generated images for improving classification tasks. Here we attempt to explore, in the context of car license plate recognition, whether it is possible to generate synthetic training data using GAN to improve recognition accuracy. With a carefully-designed pipeline, we show that the answer is affirmative. First, a large-scale image set is generated using the generator of GAN, without manual annotation. Then, these images are fed to a deep convolutional neural network (DCNN) followed by a bidirectional recurrent neural network (BRNN) with long short-term memory (LSTM), which performs the feature learning and sequence labelling. Finally, the pre-trained model is fine-tuned on real images. Our experimental results on a few data sets demonstrate the effectiveness of using GAN images: an improvement of 7.5% over a strong baseline with moderate-sized real data being available. We show that the proposed framework achieves competitive recognition accuracy on challenging test datasets. We also leverage the depthwise separate convolution to construct a lightweight convolutional RNN, which is about half size and 2x faster on CPU. Combining this framework and the proposed pipeline, we make progress in performing accurate recognition on mobile and embedded devices.

##### Abstract (translated by Google)
生成对抗网络（GAN）最近引起了很多研究的关注，为自然图像生成带来了令人印象深刻的结果。然而，到目前为止，在使用GAN生成的图像来改善分类任务方面没有观察到成功。在此，我们试图在车牌识别的背景下探索使用GAN生成合成训练数据是否可能，以提高识别的准确性。通过精心设计的流水线，我们证明答案是肯定的。首先，使用GAN的生成器生成大规模图像集，而无需手动注释。然后，将这些图像输入深度卷积神经网络（DCNN），然后输入具有长期短期记忆（LSTM）的双向递归神经网络（BRNN），进行特征学习和序列标记。最后，预先训练好的模型在实际图像上进行微调。我们在一些数据集上的实验结果证明了使用GAN图像的有效性：在具有中等实际数据的强基线上，提高了7.5％。我们表明，提出的框架实现具有挑战性的测试数据集的竞争性识别准确性。我们还利用深度分离卷积来构造一个轻量级的卷积RNN，它在CPU上大约是一半大小的两倍。结合这个框架和提出的流水线，我们在移动和嵌入式设备上进行精确识别方面取得了进展。

##### URL
[https://arxiv.org/abs/1707.03124](https://arxiv.org/abs/1707.03124)

##### PDF
[https://arxiv.org/pdf/1707.03124](https://arxiv.org/pdf/1707.03124)

