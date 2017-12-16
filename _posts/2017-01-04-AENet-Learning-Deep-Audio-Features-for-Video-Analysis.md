---
layout: post
title: "AENet: Learning Deep Audio Features for Video Analysis"
date: 2017-01-04 04:07:11
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Transfer_Learning Detection Recognition
author: Naoya Takahashi, Michael Gygli, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new deep network for audio event recognition, called AENet. In contrast to speech, sounds coming from audio events may be produced by a wide variety of sources. Furthermore, distinguishing them often requires analyzing an extended time period due to the lack of clear sub-word units that are present in speech. In order to incorporate this long-time frequency structure of audio events, we introduce a convolutional neural network (CNN) operating on a large temporal input. In contrast to previous works this allows us to train an audio event detection system end-to-end. The combination of our network architecture and a novel data augmentation outperforms previous methods for audio event detection by 16%. Furthermore, we perform transfer learning and show that our model learnt generic audio features, similar to the way CNNs learn generic features on vision tasks. In video analysis, combining visual features and traditional audio features such as MFCC typically only leads to marginal improvements. Instead, combining visual features with our AENet features, which can be computed efficiently on a GPU, leads to significant performance improvements on action recognition and video highlight detection. In video highlight detection, our audio features improve the performance by more than 8% over visual features alone.

##### Abstract (translated by Google)
我们提出了一个新的音频事件识别深度网络，称为AENet。与言语不同，来自音频事件的声音可能由各种各样的来源产生。此外，区分它们通常需要分析延长的时间段，因为缺少语音中存在的明确的子字单元。为了结合音频事件的这种长时间频率结构，我们引入了在大的时间输入上操作的卷积神经网络（CNN）。与之前的作品相比，这使我们能够端到端地训练音频事件检测系统。我们的网络架构和新颖的数据增强技术相结合，比之前的音频事件检测方法要好16％。此外，我们执行转移学习，并显示我们的模型学习了通用音频功能，类似于CNN学习视觉任务的通用功能。在视频分析中，结合视觉特性和传统音频特性（如MFCC）通常只会导致边缘改进。相反，将视觉特征与我们的AENet特性（可在GPU上高效计算）相结合，可显着提高动作识别和视频高光检测的性能。在视频突出显示检测中，我们的音频功能比单独的视觉功能提高了8％以上的性能。

##### URL
[https://arxiv.org/abs/1701.00599](https://arxiv.org/abs/1701.00599)

##### PDF
[https://arxiv.org/pdf/1701.00599](https://arxiv.org/pdf/1701.00599)

