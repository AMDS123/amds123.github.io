---
layout: post
title: "Efficient Neural Audio Synthesis"
date: 2018-02-23 08:20:23
categories: arXiv_SD
tags: arXiv_SD Sparse RNN Relation
author: Nal Kalchbrenner, Erich Elsen, Karen Simonyan, Seb Noury, Norman Casagrande, Edward Lockhart, Florian Stimberg, Aaron van den Oord, Sander Dieleman, Koray Kavukcuoglu
mathjax: true
---

* content
{:toc}

##### Abstract
Sequential models achieve state-of-the-art results in audio, visual and textual domains with respect to both estimating the data distribution and generating high-quality samples. Efficient sampling for this class of models has however remained an elusive problem. With a focus on text-to-speech synthesis, we describe a set of general techniques for reducing sampling time while maintaining high output quality. We first describe a single-layer recurrent neural network, the WaveRNN, with a dual softmax layer that matches the quality of the state-of-the-art WaveNet model. The compact form of the network makes it possible to generate 24kHz 16-bit audio 4x faster than real time on a GPU. Second, we apply a weight pruning technique to reduce the number of weights in the WaveRNN. We find that, for a constant number of parameters, large sparse networks perform better than small dense networks and this relationship holds for sparsity levels beyond 96%. The small number of weights in a Sparse WaveRNN makes it possible to sample high-fidelity audio on a mobile CPU in real time. Finally, we propose a new generation scheme based on subscaling that folds a long sequence into a batch of shorter sequences and allows one to generate multiple samples at once. The Subscale WaveRNN produces 16 samples per step without loss of quality and offers an orthogonal method for increasing sampling efficiency.

##### Abstract (translated by Google)
Sequential模型在估计数据分布和生成高质量样本方面，在音频，视觉和文本领域都取得了最先进的成果。然而，这类模型的有效采样仍然是一个难以捉摸的问题。专注于文本到语音的合成，我们描述了一组缩短采样时间，同时保持高输出质量的通用技术。我们首先描述一个单层递归神经网络WaveRNN，它具有与最先进的WaveNet模型质量相匹配的双softmax层。网络的紧凑形式使得可以在GPU上产生比实时快4倍的24kHz 16位音频。其次，我们应用减重技术来减少WaveRNN中的权重数量。我们发现，对于恒定数量的参数，大型稀疏网络比小型密集型网络表现更好，并且这种关系适用于超过96％的稀疏水平。稀疏WaveRNN中的少量权重使得可以实时在移动CPU上采样高保真音频。最后，我们提出了一种基于子尺度的新一代方案，将长序列折成一批较短的序列，并允许一次产生多个样本。子标尺WaveRNN每步产生16个样本，没有质量损失，并提供了一个提高采样效率的正交方法。

##### URL
[https://arxiv.org/abs/1802.08435](https://arxiv.org/abs/1802.08435)

##### PDF
[https://arxiv.org/pdf/1802.08435](https://arxiv.org/pdf/1802.08435)

