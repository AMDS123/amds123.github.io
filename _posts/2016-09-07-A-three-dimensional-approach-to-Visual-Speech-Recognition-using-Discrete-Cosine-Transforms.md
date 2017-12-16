---
layout: post
title: "A three-dimensional approach to Visual Speech Recognition using Discrete Cosine Transforms"
date: 2016-09-07 10:59:19
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition Recognition
author: Toni Heidenreich, Michael W. Spratling
mathjax: true
---

* content
{:toc}

##### Abstract
Visual speech recognition aims to identify the sequence of phonemes from continuous speech. Unlike the traditional approach of using 2D image feature extraction methods to derive features of each video frame separately, this paper proposes a new approach using a 3D (spatio-temporal) Discrete Cosine Transform to extract features of each feasible sub-sequence of an input video which are subsequently classified individually using Support Vector Machines and combined to find the most likely phoneme sequence using a tailor-made Hidden Markov Model. The algorithm is trained and tested on the VidTimit database to recognise sequences of phonemes as well as visemes (visual speech units). Furthermore, the system is extended with the training on phoneme or viseme pairs (biphones) to counteract the human speech ambiguity of co-articulation. The test set accuracy for the recognition of phoneme sequences is 20%, and the accuracy of viseme sequences is 39%. Both results improve the best values reported in other papers by approximately 2%. The contribution of the result is three-fold: Firstly, this paper is the first to show that 3D feature extraction methods can be applied to continuous sequence recognition tasks despite the unknown start positions and durations of each phoneme. Secondly, the result confirms that 3D feature extraction methods improve the accuracy compared to 2D features extraction methods. Thirdly, the paper is the first to specifically compare an otherwise identical method with and without using biphones, verifying that the usage of biphones has a positive impact on the result.

##### Abstract (translated by Google)
视觉语音识别旨在识别连续语音中的音素序列。与传统的利用二维图像特征提取方法分别推导每个视频帧特征的方法不同，本文提出了一种利用三维（时空）离散余弦变换提取输入视频的每个可行子序列的特征的新方法随后使用支持向量机单独分类并结合使用定制的隐马尔可夫模型来找到最可能的音素序列。该算法在VidTimit数据库上进行训练和测试，以识别音素序列以及音位（可视语音单元）。此外，该系统通过对音素或视素对（biphones）的训练来扩展，以抵消共同发音的人类语音模糊性。音素序列识别的测试集精度为20％，视素序列的准确率为39％。这两个结果都使其他论文报告的最佳值提高了约2％。结果的贡献有三个方面：首先，本文首先证明，尽管每个音素的起始位置和持续时间未知，3D特征提取方法可以应用于连续序列识别任务。其次，结果证实，与2D特征提取方法相比，3D特征提取方法提高了准确性。第三，这篇论文是第一个比较相同方法和不使用双电子耳机的方法，验证双电子耳机的使用对结果有积极的影响。

##### URL
[https://arxiv.org/abs/1609.01932](https://arxiv.org/abs/1609.01932)

##### PDF
[https://arxiv.org/pdf/1609.01932](https://arxiv.org/pdf/1609.01932)

