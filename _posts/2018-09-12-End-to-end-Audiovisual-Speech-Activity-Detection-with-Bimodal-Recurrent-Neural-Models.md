---
layout: post
title: "End-to-end Audiovisual Speech Activity Detection with Bimodal Recurrent Neural Models"
date: 2018-09-12 16:44:46
categories: arXiv_CV
tags: arXiv_CV Speech_Recognition RNN Deep_Learning Detection Relation Recognition
author: Fei Tao, Carlos Busso
mathjax: true
---

* content
{:toc}

##### Abstract
Speech activity detection (SAD) plays an important role in current speech processing systems, including automatic speech recognition (ASR). SAD is particularly difficult in environments with acoustic noise. A practical solution is to incorporate visual information, increasing the robustness of the SAD approach. An audiovisual system has the advantage of being robust to different speech modes (e.g., whisper speech) or background noise. Recent advances in audiovisual speech processing using deep learning have opened opportunities to capture in a principled way the temporal relationships between acoustic and visual features. This study explores this idea proposing a \emph{bimodal recurrent neural network} (BRNN) framework for SAD. The approach models the temporal dynamic of the sequential audiovisual data, improving the accuracy and robustness of the proposed SAD system. Instead of estimating hand-crafted features, the study investigates an end-to-end training approach, where acoustic and visual features are directly learned from the raw data during training. The experimental evaluation considers a large audiovisual corpus with over 60.8 hours of recordings, collected from 105 speakers. The results demonstrate that the proposed framework leads to absolute improvements up to 1.2% under practical scenarios over a VAD baseline using only audio implemented with deep neural network (DNN). The proposed approach achieves 92.7% F1-score when it is evaluated using the sensors from a portable tablet under noisy acoustic environment, which is only 1.0% lower than the performance obtained under ideal conditions (e.g., clean speech obtained with a high definition camera and a close-talking microphone).

##### Abstract (translated by Google)
语音活动检测（SAD）在当前语音处理系统中起重要作用，包括自动语音识别（ASR）。在具有声学噪声的环境中，SAD特别困难。实际的解决方案是结合视觉信息，增加SAD方法的稳健性。视听系统具有对不同语音模式（例如，低语音）或背景噪声稳健的优点。使用深度学习的视听语音处理的最新进展已经开启了以原则方式捕获声学和视觉特征之间的时间关系的机会。本研究探讨了这一想法，提出了一种针对SAD的\ emph {双峰递归神经网络}（BRNN）框架。该方法模拟连续视听数据的时间动态，提高了所提出的SAD系统的准确性和鲁棒性。该研究不是评估手工制作的特征，而是研究端到端的训练方法，在训练过程中直接从原始数据中学习声学和视觉特征。实验评估考虑了一个大型视听语料库，其中有超过60.8小时的录音，从105名演讲者收集。结果表明，在仅使用采用深度神经网络（DNN）实现的音频的VAD基线的实际场景下，所提出的框架导致绝对改进高达1.2％。当在嘈杂的声学环境下使用来自便携式平板电脑的传感器评估时，所提出的方法实现了92.7％的F1得分，其仅比在理想条件下获得的性能低1.0％（例如，用高清晰度相机获得的清晰语音和一个近距离的麦克风）。

##### URL
[http://arxiv.org/abs/1809.04553](http://arxiv.org/abs/1809.04553)

##### PDF
[http://arxiv.org/pdf/1809.04553](http://arxiv.org/pdf/1809.04553)

