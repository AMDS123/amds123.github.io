---
layout: post
title: "Modeling Multimodal Clues in a Hybrid Deep Learning Framework for Video Classification"
date: 2017-06-14 14:23:08
categories: arXiv_CV
tags: arXiv_CV CNN Video_Classification RNN Classification Deep_Learning Prediction Quantitative Relation Memory_Networks
author: Yu-Gang Jiang, Zuxuan Wu, Jinhui Tang, Zechao Li, Xiangyang Xue, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Videos are inherently multimodal. This paper studies the problem of how to fully exploit the abundant multimodal clues for improved video categorization. We introduce a hybrid deep learning framework that integrates useful clues from multiple modalities, including static spatial appearance information, motion patterns within a short time window, audio information as well as long-range temporal dynamics. More specifically, we utilize three Convolutional Neural Networks (CNNs) operating on appearance, motion and audio signals to extract their corresponding features. We then employ a feature fusion network to derive a unified representation with an aim to capture the relationships among features. Furthermore, to exploit the long-range temporal dynamics in videos, we apply two Long Short Term Memory networks with extracted appearance and motion features as inputs. Finally, we also propose to refine the prediction scores by leveraging contextual relationships among video semantics. The hybrid deep learning framework is able to exploit a comprehensive set of multimodal features for video classification. Through an extensive set of experiments, we demonstrate that (1) LSTM networks which model sequences in an explicitly recurrent manner are highly complementary with CNN models; (2) the feature fusion network which produces a fused representation through modeling feature relationships outperforms alternative fusion strategies; (3) the semantic context of video classes can help further refine the predictions for improved performance. Experimental results on two challenging benchmarks, the UCF-101 and the Columbia Consumer Videos (CCV), provide strong quantitative evidence that our framework achieves promising results: $93.1\%$ on the UCF-101 and $84.5\%$ on the CCV, outperforming competing methods with clear margins.

##### Abstract (translated by Google)
视频本质上是多模式的。本文研究了如何充分利用丰富的多模态线索来改进视频分类的问题。我们引入了一个混合的深度学习框架，整合了多种形式的有用线索，包括静态空间外观信息，短时间窗口内的动作模式，音频信息以及远程时间动态。更具体地说，我们利用三个对外观，运动和音频信号进行操作的卷积神经网络（CNN）来提取其相应的特征。然后我们采用特征融合网络来获得统一的表示，以捕捉特征之间的关系。此外，为了利用视频中的远程时间动态，我们应用两个长的短期记忆网络，提取外观和运动特征作为输入。最后，我们还提出通过利用视频语义之间的上下文关系来改进预测分数。混合深度学习框架能够利用一套综合的多模态特征来进行视频分类。通过一系列广泛的实验，我们证明：（1）以明确的循环方式建模序列的LSTM网络与CNN模型高度互补; （2）通过建模特征关系生成融合表示的特征融合网络优于其他融合策略; （3）视频类的语义上下文有助于进一步改进预测以提高性能。 UCF-101和哥伦比亚消费者视频（CCV）这两个具有挑战性的基准的实验结果提供了强有力的量化证据，表明我们的框架取得了令人鼓舞的结果：UCF-101上的$ 93.1 \％$和CCV上的$ 84.5 \％$表现优于竞争的方法有明显的利润空间。

##### URL
[https://arxiv.org/abs/1706.04508](https://arxiv.org/abs/1706.04508)

##### PDF
[https://arxiv.org/pdf/1706.04508](https://arxiv.org/pdf/1706.04508)

