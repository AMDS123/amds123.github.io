---
layout: post
title: "Learning from Between-class Examples for Deep Sound Recognition"
date: 2018-02-28 12:41:50
categories: arXiv_SD
tags: arXiv_SD Regularization Deep_Learning Relation Recognition
author: Yuji Tokozume, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods have achieved high performance in sound recognition tasks. Deciding how to feed the training data is important for further performance improvement. We propose a novel learning method for deep sound recognition: Between-Class learning (BC learning). Our strategy is to learn a discriminative feature space by recognizing the between-class sounds as between-class sounds. We generate between-class sounds by mixing two sounds belonging to different classes with a random ratio. We then input the mixed sound to the model and train the model to output the mixing ratio. The advantages of BC learning are not limited only to the increase in variation of the training data; BC learning leads to an enlargement of Fisher's criterion in the feature space and a regularization of the positional relationship among the feature distributions of the classes. The experimental results show that BC learning improves the performance on various sound recognition networks, datasets, and data augmentation schemes, in which BC learning proves to be always beneficial. Furthermore, we construct a new deep sound recognition network (EnvNet-v2) and train it with BC learning. As a result, we achieved a performance surpasses the human level.

##### Abstract (translated by Google)
深度学习方法在声音识别任务中取得了很高的性能。决定如何提供培训数据对于进一步提高绩效非常重要。我们提出了一种深度声音识别的新颖学习方法：课间学习（BC学习）。我们的策略是通过将类间声音识别为类间声音来学习识别性特征空间。我们通过以随机比率混合属于不同类别的两个声音来产生课间声音。然后我们将混合声音输入到模型中，并训练模型输出混合比率。 BC学习的优势不仅仅限于训练数据变化的增加， BC学习导致特征空间中Fisher准则的扩大和类别特征分布之间位置关系的正则化。实验结果表明，BC学习提高了各种声音识别网络，数据集和数据增强方案的性能，BC学习证明总是有益的。此外，我们构建了一个新的深度声音识别网络（EnvNet-v2）并使用BC学习进行训练。结果，我们取得了超越人类水平的表现。

##### URL
[http://arxiv.org/abs/1711.10282](http://arxiv.org/abs/1711.10282)

##### PDF
[http://arxiv.org/pdf/1711.10282](http://arxiv.org/pdf/1711.10282)

