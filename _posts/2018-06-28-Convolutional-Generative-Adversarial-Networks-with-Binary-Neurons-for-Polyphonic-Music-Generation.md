---
layout: post
title: "Convolutional Generative Adversarial Networks with Binary Neurons for Polyphonic Music Generation"
date: 2018-06-28 16:13:12
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN CNN
author: Hao-Wen Dong, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
It has been shown recently that deep convolutional generative adversarial networks (GANs) can learn to generate music in the form of piano-rolls, which represent music by binary-valued time-pitch matrices. However, existing models can only generate real-valued piano-rolls and require further post-processing, such as hard thresholding (HT) or Bernoulli sampling (BS), to obtain the final binary-valued results. In this paper, we study whether we can have a convolutional GAN model that directly creates binary-valued piano-rolls by using binary neurons. Specifically, we propose to append to the generator an additional refiner network, which uses binary neurons at the output layer. The whole network is trained in two stages. Firstly, the generator and the discriminator are pretrained. Then, the refiner network is trained along with the discriminator to learn to binarize the real-valued piano-rolls the pretrained generator creates. Experimental results show that using binary neurons instead of HT or BS indeed leads to better results in a number of objective measures. Moreover, deterministic binary neurons perform better than stochastic ones in both objective measures and a subjective test. The source code, training data and audio examples of the generated results can be found at https://salu133445.github.io/bmusegan/ .

##### Abstract (translated by Google)
近来已经表明，深卷积生成对抗网络（GAN）可以学习以钢琴卷的形式生成音乐，所述音乐通过二值时间间距矩阵表示音乐。然而，现有模型只能生成实值钢琴曲，并需要进一步的后处理，如硬阈值（HT）或伯努利（Bernoulli）采样（BS）才能获得最终的二值结果。在本文中，我们研究是否可以使用二元神经元直接创建二值的钢琴卷的卷积GAN模型。具体来说，我们建议在发生器附加一个额外的磨浆机网络，该网络在输出层使用二元神经元。整个网络分两个阶段进行培训。首先，对发生器和鉴别器进行预训练。然后，炼油厂网络与鉴别器一起训练，以学习对预训练发电机创建的实值钢琴卷进行二值化。实验结果表明，使用二元神经元而不是HT或BS可以在许多客观测量中获得更好的结果。而且，在客观测量和主观测试中，确定性二元神经元的表现都比随机性好。生成结果的源代码，培训数据和音频示例可在https://salu133445.github.io/bmusegan/找到。

##### URL
[http://arxiv.org/abs/1804.09399](http://arxiv.org/abs/1804.09399)

##### PDF
[http://arxiv.org/pdf/1804.09399](http://arxiv.org/pdf/1804.09399)

