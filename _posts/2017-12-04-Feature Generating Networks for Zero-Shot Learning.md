---
layout: post
title:  'Feature Generating Networks for Zero-Shot Learning'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Yongqin Xian, Tobias Lorenz, Bernt Schiele, Zeynep Akata
---

* content
{:toc}

##### Abstract
Suffering from the extreme training data imbalance between seen and unseen classes, most of existing state-of-the-art approaches fail to achieve satisfactory results for the challenging generalized zero-shot learning task. To circumvent the need for labeled examples of unseen classes, we propose a novel generative adversarial network (GAN) that synthesizes CNN features conditioned on class-level semantic information, offering a shortcut directly from a semantic descriptor of a class to a class-conditional feature distribution. Our proposed approach, pairing a Wasserstein GAN with a classification loss, is able to generate sufficiently discriminative CNN features to train softmax classifiers or any multimodal embedding method. Our experimental results demonstrate a significant boost in accuracy over the state of the art on five challenging datasets -- CUB, FLO, SUN, AWA and ImageNet -- in both the zero-shot learning and generalized zero-shot learning settings.

##### Abstract (translated by Google)
由于看到的和看不见的类别之间极端的训练数据不平衡，现有的大多数现有技术方法对于具有挑战性的广义零点学习任务没有取得令人满意的结果。为了避免需要标签的例子看不见的类，我们提出了一种新的生成对抗网络（GAN）合成CNN功能的条件下的类级别的语义信息，提供了一个直接从一个类的语义描述符的快捷方式到一个类的条件功能分配。我们提出的方法，使Wasserstein GAN与分类损失相匹配，能够生成充分区分的CNN特征来训练softmax分类器或任何多模式嵌入方法。我们的实验结果表明，对于五个具有挑战性的数据集（CUB，FLO，SUN，AWA和ImageNet），在零射击学习和广义零射击学习设置中，相比现有技术的精确度显着提高。

