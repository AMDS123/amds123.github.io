---
layout: post
title: "Combining Multiple Views for Visual Speech Recognition"
date: 2017-10-19 14:52:34
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition CNN RNN Recognition
author: Marina Zimmermann, Mostafa Mehdipour Ghazi, Hazım Kemal Ekenel, Jean-Philippe Thiran
mathjax: true
---

* content
{:toc}

##### Abstract
Visual speech recognition is a challenging research problem with a particular practical application of aiding audio speech recognition in noisy scenarios. Multiple camera setups can be beneficial for the visual speech recognition systems in terms of improved performance and robustness. In this paper, we explore this aspect and provide a comprehensive study on combining multiple views for visual speech recognition. The thorough analysis covers fusion of all possible view angle combinations both at feature level and decision level. The employed visual speech recognition system in this study extracts features through a PCA-based convolutional neural network, followed by an LSTM network. Finally, these features are processed in a tandem system, being fed into a GMM-HMM scheme. The decision fusion acts after this point by combining the Viterbi path log-likelihoods. The results show that the complementary information contained in recordings from different view angles improves the results significantly. For example, the sentence correctness on the test set is increased from 76% for the highest performing single view ($30^\circ$) to up to 83% when combining this view with the frontal and $60^\circ$ view angles.

##### Abstract (translated by Google)
视觉语音识别是一个具有挑战性的研究问题，在嘈杂的场景中辅助音频语音识别的实际应用。就改进的性能和鲁棒性而言，多个相机设置对于视觉语音识别系统可能是有益的。在本文中，我们探讨这个方面，并提供了一个综合研究，结合多个视角的视觉语音识别。透彻的分析涵盖了所有可能的视角组合在功能层面和决策层面的融合。本研究中所采用的视觉语音识别系统通过基于PCA的卷积神经网络提取特征，然后是LSTM网络。最后，这些特征在串联系统中被处理，被馈送到GMM-HMM方案中。决策融合在这一点之后通过组合维特比路径对数似然性而起作用。结果显示，从不同视角录制的补充信息显着改善了结果。例如，将测试集的句子正确性从最高表现单视图（$ 30 ^ \ \ circ $）的76％提高到将该视图与正视图和$ 60 ^ \ circ $视角合并时的高达83％。

##### URL
[https://arxiv.org/abs/1710.07168](https://arxiv.org/abs/1710.07168)

##### PDF
[https://arxiv.org/pdf/1710.07168](https://arxiv.org/pdf/1710.07168)

