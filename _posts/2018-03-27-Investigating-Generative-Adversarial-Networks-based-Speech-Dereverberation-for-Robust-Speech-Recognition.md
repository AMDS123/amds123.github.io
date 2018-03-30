---
layout: post
title: "Investigating Generative Adversarial Networks based Speech Dereverberation for Robust Speech Recognition"
date: 2018-03-27 15:23:12
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Speech_Recognition RNN Recognition
author: Ke Wang, Junbo Zhang, Sining Sun, Yujun Wang, Fei Xiang, Lei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the use of generative adversarial networks (GANs) in speech dereverberation for robust speech recognition. GANs have been recently studied for speech enhancement to remove additive noises, but there still lacks of a work to examine their ability in speech dereverberation and the advantages of using GANs have not been fully established. In this paper, we provide deep investigations in the use of GAN-based dereverberation front-end in ASR. First, we study the effectiveness of different dereverberation networks (the generator in GAN) and find that LSTM leads a significant improvement as compared with feed-forward DNN and CNN in our dataset. Second, further adding residual connections in the deep LSTMs can boost the performance as well. Finally, we find that, for the success of GAN, it is important to update the generator and the discriminator using the same mini-batch data during training. Moreover, using reverberant spectrogram as a condition to discriminator, as suggested in previous studies, may degrade the performance. In summary, our GAN-based dereverberation front-end achieves 14%-19% relative CER reduction as compared to the baseline DNN dereverberation network when tested on a strong multi-condition training acoustic model.

##### Abstract (translated by Google)
我们研究了生成对抗网络（GAN）在语音去混响中用于鲁棒语音识别。最近已经对GAN进行了语音增强研究，以消除加性噪声，但是仍然缺乏研究语音去混响能力的工作，并且使用GAN的优势还没有完全建立。在本文中，我们对在ASR中使用基于GAN的去混响前端进行了深入的研究。首先，我们研究不同去混响网络（GAN中的发生器）的有效性，并发现与我们的数据集中的前馈DNN和CNN相比，LSTM有显着的改进。其次，在深层LSTM中进一步增加剩余连接也可以提高性能。最后，我们发现，为了GAN的成功，在训练期间使用相同的小批量数据来更新生成器和鉴别器是非常重要的。此外，使用混响频谱图作为鉴别器的条件，正如以前的研究所建议的那样，可能会降低性能。总之，我们的基于GAN的去混响前端在强大的多状态训练声学模型上测试时，与基准DNN去混响网络相比，相对CER减少了14％-19％。

##### URL
[https://arxiv.org/abs/1803.10132](https://arxiv.org/abs/1803.10132)

##### PDF
[https://arxiv.org/pdf/1803.10132](https://arxiv.org/pdf/1803.10132)

