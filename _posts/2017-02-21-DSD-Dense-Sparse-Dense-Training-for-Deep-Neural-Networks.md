---
layout: post
title: "DSD: Dense-Sparse-Dense Training for Deep Neural Networks"
date: 2017-02-21 20:51:05
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Caption RNN Recognition
author: Song Han, Jeff Pool, Sharan Narang, Huizi Mao, Enhao Gong, Shijian Tang, Erich Elsen, Peter Vajda, Manohar Paluri, John Tran, Bryan Catanzaro, William J. Dally
---

* content
{:toc}

##### Abstract
Modern deep neural networks have a large number of parameters, making them very hard to train. We propose DSD, a dense-sparse-dense training flow, for regularizing deep neural networks and achieving better optimization performance. In the first D (Dense) step, we train a dense network to learn connection weights and importance. In the S (Sparse) step, we regularize the network by pruning the unimportant connections with small weights and retraining the network given the sparsity constraint. In the final D (re-Dense) step, we increase the model capacity by removing the sparsity constraint, re-initialize the pruned parameters from zero and retrain the whole dense network. Experiments show that DSD training can improve the performance for a wide range of CNNs, RNNs and LSTMs on the tasks of image classification, caption generation and speech recognition. On ImageNet, DSD improved the Top1 accuracy of GoogLeNet by 1.1%, VGG-16 by 4.3%, ResNet-18 by 1.2% and ResNet-50 by 1.1%, respectively. On the WSJ'93 dataset, DSD improved DeepSpeech and DeepSpeech2 WER by 2.0% and 1.1%. On the Flickr-8K dataset, DSD improved the NeuralTalk BLEU score by over 1.7. DSD is easy to use in practice: at training time, DSD incurs only one extra hyper-parameter: the sparsity ratio in the S step. At testing time, DSD doesn't change the network architecture or incur any inference overhead. The consistent and significant performance gain of DSD experiments shows the inadequacy of the current training methods for finding the best local optimum, while DSD effectively achieves superior optimization performance for finding a better solution. DSD models are available to download at this https URL

##### Abstract (translated by Google)
现代的深度神经网络有大量的参数，使他们很难训练。我们提出了一个密集稀疏密集的训练流DSD，用于正则化深度神经网络并获得更好的优化性能。在第一个D（稠密）步骤中，我们训练密集的网络来学习连接权重和重要性。在S（稀疏）步骤中，我们通过修剪不重要的小权重连接来规范网络，并且在稀疏性约束条件下重新训练网络。在最后的D（重密）步骤中，我们通过去除稀疏约束来增加模型容量，从零重新初始化修剪的参数并重新训练整个稠密网络。实验表明，DSD训练可以提高CNN，RNN和LSTM在图像分类，字幕生成和语音识别等方面的性能。在ImageNet上，DSD分别将GoogLeNet的Top1精确度提高了1.1％，VGG-16提高了4.3％，ResNet-18提高了1.2％，ResNet-50提高了1.1％。在WSJ'93数据集中，DSD将DeepSpeech和DeepSpeech2 WER分别提高了2.0％和1.1％。在Flickr-8K数据集上，DSD将NeuralTalk BLEU得分提高了1.7倍以上。 DSD在实践中很容易使用：在训练时，DSD只会引入一个额外的超参数：S步中的稀疏比。在测试时间，DSD不会改变网络架构，也不会引发任何推理开销。 DSD实验的一致性和显着的性能增益表明了目前用于寻找最佳局部最优的训练方法的不足，而DSD有效地实现了优越的优化性能以找到更好的解决方案。 DSD型号可在此https网址下载

##### URL
[https://arxiv.org/abs/1607.04381](https://arxiv.org/abs/1607.04381)

