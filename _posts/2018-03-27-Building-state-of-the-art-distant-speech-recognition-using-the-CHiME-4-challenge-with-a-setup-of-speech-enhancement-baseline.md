---
layout: post
title: "Building state-of-the-art distant speech recognition using the CHiME-4 challenge with a setup of speech enhancement baseline"
date: 2018-03-27 14:33:53
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition RNN Language_Model Recognition
author: Szu-Jui Chen, Aswin Shanmugam Subramanian, Hainan Xu, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a new baseline system for automatic speech recognition (ASR) in the CHiME-4 challenge to promote the development of noisy ASR in speech processing communities by providing 1) state-of-the-art system with a simplified single system comparable to the complicated top systems in the challenge, 2) publicly available and reproducible recipe through the main repository in the Kaldi speech recognition toolkit. The proposed system adopts generalized eigenvalue beamforming with bidirectional long short-term memory (LSTM) mask estimation. We also propose to use a time delay neural network (TDNN) based on the lattice-free version of the maximum mutual information (LF-MMI) trained with augmented all six microphones plus the enhanced data after beamforming. Finally, we use a LSTM language model for lattice and n-best re-scoring. The final system achieved 2.74\% WER for the real test set in the 6-channel track, which corresponds to the 2nd place in the challenge. In addition, the proposed baseline recipe includes four different speech enhancement measures, short-time objective intelligibility measure (STOI), extended STOI (eSTOI), perceptual evaluation of speech quality (PESQ) and speech distortion ratio (SDR) for the simulation test set. Thus, the recipe also provides an experimental platform for speech enhancement studies with these performance measures.

##### Abstract (translated by Google)
本文描述了CHiME-4挑战中用于自动语音识别（ASR）的新基准系统，以促进语音处理社区中噪声ASR的发展，方法是提供1）最先进的系统和简化的单一系统，挑战中复杂的顶级系统，2）通过Kaldi语音识别工具箱中的主要存储库公开可用且可重现的配方。所提出的系统采用广义特征值波束形成和双向长期短期记忆（LSTM）掩模估计。我们还建议使用基于最大互信息（LF-MMI）的无格式版本的时间延迟神经网络（TDNN），其使用增强的所有六个麦克风以及波束成形后的增强数据进行训练。最后，我们使用LSTM语言模型进行格子和n最佳重新评分。最终系统在6通道赛道上获得了2.74％的真实测试组合，相当于挑战赛中的第二名。此外，所提出的基线配方包括用于模拟测试集的四种不同语音增强测量，短时目标可懂度测量（STOI），扩展STOI（eSTOI），语音质量感知评估（PESQ）和语音失真比（SDR） 。因此，该配方还为这些性能测量提供了用于语音增强研究的实验平台。

##### URL
[https://arxiv.org/abs/1803.10109](https://arxiv.org/abs/1803.10109)

##### PDF
[https://arxiv.org/pdf/1803.10109](https://arxiv.org/pdf/1803.10109)

