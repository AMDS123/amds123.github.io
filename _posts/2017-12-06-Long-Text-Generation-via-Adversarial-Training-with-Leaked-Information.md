---
layout: post
title: 'Long Text Generation via Adversarial Training with Leaked Information'
date: 2017-12-06 03:33:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN Reinforcement_Learning Caption
author: Jiaxian Guo, Sidi Lu, Han Cai, Weinan Zhang, Yong Yu, Jun Wang
---

* content
{:toc}

##### Abstract
Automatically generating coherent and semantically meaningful text has many applications in machine translation, dialogue systems, image captioning, etc. Recently, by combining with policy gradient, Generative Adversarial Nets (GAN) that use a discriminative model to guide the training of the generative model as a reinforcement learning policy has shown promising results in text generation. However, the scalar guiding signal is only available after the entire text has been generated and lacks intermediate information about text structure during the generative process. As such, it limits its success when the length of the generated text samples is long (more than 20 words). In this paper, we propose a new framework, called LeakGAN, to address the problem for long text generation. We allow the discriminative net to leak its own high-level extracted features to the generative net to further help the guidance. The generator incorporates such informative signals into all generation steps through an additional Manager module, which takes the extracted features of current generated words and outputs a latent vector to guide the Worker module for next-word generation. Our extensive experiments on synthetic data and various real-world tasks with Turing test demonstrate that LeakGAN is highly effective in long text generation and also improves the performance in short text generation scenarios. More importantly, without any supervision, LeakGAN would be able to implicitly learn sentence structures only through the interaction between Manager and Worker.

##### Abstract (translated by Google)
最近，与策略梯度相结合的生成对抗网（GAN）使用判别模型来指导生成模型的训练为强化学习政策已经在文本生成中显示出有希望的结果。然而，标引导信号只有在生成完整的文本之后才可用，并且在生成过程中缺少关于文本结构的中间信息。因此，当生成的文本样本的长度很长（超过20个字）时，限制了它的成功。在本文中，我们提出了一个名为LeakGAN的新框架来解决长文本生成的问题。我们允许判别网将自己的高层提取的特征泄露给生成网络，以进一步帮助指导。生成器通过一个额外的管理器模块将这些信息信号合并到所有生成步骤中，该模块将当前生成的字的提取特征提取出来，并输出一个潜在向量来指导工作者模块进行下一个字的生成。我们通过图灵测试对合成数据和各种实际任务进行了广泛的实验，证明了LeakGAN在长文本生成中非常有效，同时也提高了短文本生成场景中的性能。更重要的是，在没有任何监督的情况下，LeakGAN只能通过管理者和工作者之间的交互来隐含地学习句子结构。

##### URL
[https://arxiv.org/abs/1709.08624](https://arxiv.org/abs/1709.08624)

