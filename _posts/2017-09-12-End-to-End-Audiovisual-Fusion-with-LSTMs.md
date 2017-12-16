---
layout: post
title: "End-to-End Audiovisual Fusion with LSTMs"
date: 2017-09-12 15:23:55
categories: arXiv_CV
tags: arXiv_CV Knowledge Speech_Recognition RNN Classification Deep_Learning Recognition
author: Stavros Petridis, Yujiang Wang, Zuwei Li, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Several end-to-end deep learning approaches have been recently presented which simultaneously extract visual features from the input images and perform visual speech classification. However, research on jointly extracting audio and visual features and performing classification is very limited. In this work, we present an end-to-end audiovisual model based on Bidirectional Long Short-Term Memory (BLSTM) networks. To the best of our knowledge, this is the first audiovisual fusion model which simultaneously learns to extract features directly from the pixels and spectrograms and perform classification of speech and nonlinguistic vocalisations. The model consists of multiple identical streams, one for each modality, which extract features directly from mouth regions and spectrograms. The temporal dynamics in each stream/modality are modeled by a BLSTM and the fusion of multiple streams/modalities takes place via another BLSTM. An absolute improvement of 1.9% in the mean F1 of 4 nonlingusitic vocalisations over audio-only classification is reported on the AVIC database. At the same time, the proposed end-to-end audiovisual fusion system improves the state-of-the-art performance on the AVIC database leading to a 9.7% absolute increase in the mean F1 measure. We also perform audiovisual speech recognition experiments on the OuluVS2 database using different views of the mouth, frontal to profile. The proposed audiovisual system significantly outperforms the audio-only model for all views when the acoustic noise is high.

##### Abstract (translated by Google)
近来已经提出了几种端到端的深度学习方法，它们同时从输入图像中提取视觉特征并执行视觉语音分类。然而，联合提取音频和视频特征以及执行分类的研究是非常有限的。在这项工作中，我们提出了一个基于双向长期短期记忆（BLSTM）网络的端到端视听模型。据我们所知，这是第一个视听融合模型，它同时学习直接从像素和光谱图中提取特征，并对语音和非语言发音进行分类。该模型由多个相同的流组成，每个模态一个，直接从口区域和频谱图中提取特征。每个流/模态的时间动态是由BLSTM建模的，而多个流/模态的融合是通过另一个BLSTM进行的。在AVIC数据库上报告，4个非音频发声的平均F1绝对提高了1.9％，而不是纯音频分类。与此同时，提出的端到端视听融合系统改善了AVIC数据库的最新性能，从而使平均F1测量的绝对增长率提高了9.7％。我们还在OuluVS2数据库上进行视听语音识别实验，使用不同的嘴巴视图，正面和侧面。当声学噪声较高时，所提出的视听系统在所有视图方面明显优于纯音频模型。

##### URL
[https://arxiv.org/abs/1709.04343](https://arxiv.org/abs/1709.04343)

##### PDF
[https://arxiv.org/pdf/1709.04343](https://arxiv.org/pdf/1709.04343)

