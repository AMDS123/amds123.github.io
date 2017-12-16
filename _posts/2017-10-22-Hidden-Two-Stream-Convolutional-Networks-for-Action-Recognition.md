---
layout: post
title: "Hidden Two-Stream Convolutional Networks for Action Recognition"
date: 2017-10-22 03:53:21
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Relation Recognition
author: Yi Zhu, Zhenzhong Lan, Shawn Newsam, Alexander G. Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
Analyzing videos of human actions involves understanding the temporal relationships among video frames. CNNs are the current state-of-the-art methods for action recognition in videos. However, the CNN architectures currently being used have difficulty in capturing these relationships. State-of-the-art action recognition approaches rely on traditional local optical flow estimation methods to pre-compute motion information for CNNs. Such a two-stage approach is computationally expensive, storage demanding, and not end-to-end trainable. In this paper, we present a novel CNN architecture that implicitly captures motion information between adjacent frames. We then plug it into a state-of-the-art action recognition framework called two-stream CNNs. We name our approach hidden two-stream CNNs because it only takes raw video frames as input and directly predicts action classes without explicitly computing optical flow. Our end-to-end approach is 10x faster than a two-stage one and maintains similar accuracy. Experimental results on UCF101 and HMDB51 datasets show that our approach significantly outperforms previous best real-time approaches.

##### Abstract (translated by Google)
分析人类行为的视频涉及了解视频帧之间的时间关系。有线电视新闻网是当前最先进的视频行动识别方法。但是，目前正在使用的CNN体​​系结构很难捕捉到这些关系。最先进的动作识别方法依靠传统的局部光流估计方法来预先计算CNN的运动信息。这种两阶段的方法在计算上是昂贵的，需要存储，而不是端到端的可训练。在本文中，我们提出了一种新颖的CNN架构，隐式捕获相邻帧之间的运动信息。然后，我们将其插入到一个称为双流CNN的最先进的动作识别框架中。我们将隐藏双流CNN的方法命名为，因为它只将原始视频帧作为输入并直接预测动作类别，而不明确计算光流。我们的端到端方法比两阶段方法快10倍，并保持相似的精度。 UCF101和HMDB51数据集上的实验结果表明，我们的方法明显优于以前的最佳实时方法。

##### URL
[https://arxiv.org/abs/1704.00389](https://arxiv.org/abs/1704.00389)

##### PDF
[https://arxiv.org/pdf/1704.00389](https://arxiv.org/pdf/1704.00389)

