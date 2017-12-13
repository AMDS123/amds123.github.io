---
layout: post
title: "De-identification of medical records using conditional random fields and long short-term memory networks"
date: 2017-09-29 12:03:57
categories: arXiv_CV
tags: arXiv_CV RNN Detection Memory_Networks
author: Zhipeng Jiang, Chao Zhao, Bin He, Yi Guan, Jingchi Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
The CEGS N-GRID 2016 Shared Task 1 in Clinical Natural Language Processing focuses on the de-identification of psychiatric evaluation records. This paper describes two participating systems of our team, based on conditional random fields (CRFs) and long short-term memory networks (LSTMs). A pre-processing module was introduced for sentence detection and tokenization before de-identification. For CRFs, manually extracted rich features were utilized to train the model. For LSTMs, a character-level bi-directional LSTM network was applied to represent tokens and classify tags for each token, following which a decoding layer was stacked to decode the most probable protected health information (PHI) terms. The LSTM-based system attained an i2b2 strict micro-F_1 measure of 89.86%, which was higher than that of the CRF-based system.

##### Abstract (translated by Google)
临床自然语言处理中的CEGS N-GRID 2016共享任务1侧重于精神病评估记录的去识别。本文介绍了我们团队的两个参与系统，基于条件随机场（CRF）和长期短期记忆网络（LSTM）。在解除识别之前，引入了预处理模块进行句子检测和标记。对于CRF，利用手动提取的丰富特征来训练模型。对于LSTM，一个字符级的双向LSTM网络被用来表示令牌并为每个令牌分类标签，随后解码层被堆叠以解码最可能的受保护的健康信息（PHI）术语。基于LSTM的系统达到了89.86％的i2b2严格的微F_1度量，高于CRF系统。

##### URL
[https://arxiv.org/abs/1709.06901](https://arxiv.org/abs/1709.06901)

##### PDF
[https://arxiv.org/pdf/1709.06901](https://arxiv.org/pdf/1709.06901)

