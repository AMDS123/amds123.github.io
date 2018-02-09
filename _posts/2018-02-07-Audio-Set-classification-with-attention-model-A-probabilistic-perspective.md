---
layout: post
title: "Audio Set classification with attention model: A probabilistic perspective"
date: 2018-02-07 22:02:38
categories: arXiv_SD
tags: arXiv_SD Attention Classification
author: Qiuqiang Kong, Yong Xu, Wenwu Wang, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates the classification of the Audio Set dataset. Audio Set is a large scale weakly labelled dataset of sound clips. Previous work used multiple instance learning (MIL) to classify weakly labelled data. In MIL, a bag consists of several instances, and a bag is labelled positive if at least one instances in the audio clip is positive. A bag is labelled negative if all the instances in the bag are negative. We propose an attention model to tackle the MIL problem and explain this attention model from a novel probabilistic perspective. We define a probability space on each bag, where each instance in the bag has a trainable probability measure for each class. Then the classification of a bag is the expectation of the classification output of the instances in the bag with respect to the learned probability measure. Experimental results show that our proposed attention model modeled by fully connected deep neural network obtains mAP of 0.327 on Audio Set dataset, outperforming the Google's baseline of 0.314 and recurrent neural network of 0.325.

##### Abstract (translated by Google)
本文研究了音频集数据集的分类。音频集是声音剪辑的大规模弱标记数据集。以前的工作使用多实例学习（MIL）对弱标记的数据进行分类。在MIL中，一个包由多个实例组成，并且如果音频片段中至少有一个实例是肯定的，则包被标记为正。如果袋子中的所有实例均为负数，则袋子被标记为否定的。我们提出了一个解决MIL问题的注意模型，并从一个新颖的概率角度来解释这个注意模型。我们在每个袋子上定义一个概率空间，每个袋子中的每个实例都有一个可训练的概率测度。然后，袋子的分类是对袋子中的实例的分类输出关于学习概率测量的期望。实验结果表明，我们提出的全连通深度神经网络建模的注意模型在Audio Set数据集上获得了0.327的mAP，优于谷歌0.314的基线和0.325的递归神经网络。

##### URL
[http://arxiv.org/abs/1711.00927](http://arxiv.org/abs/1711.00927)

##### PDF
[http://arxiv.org/pdf/1711.00927](http://arxiv.org/pdf/1711.00927)

