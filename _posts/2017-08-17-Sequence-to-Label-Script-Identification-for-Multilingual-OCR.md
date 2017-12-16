---
layout: post
title: "Sequence-to-Label Script Identification for Multilingual OCR"
date: 2017-08-17 20:20:25
categories: arXiv_CV
tags: arXiv_CV OCR CNN
author: Yasuhisa Fujii, Karel Driesen, Jonathan Baccash, Ash Hurst, Ashok C. Popat
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a novel line-level script identification method. Previous work repurposed an OCR model generating per-character script codes, counted to obtain line-level script identification. This has two shortcomings. First, as a sequence-to-sequence model it is more complex than necessary for the sequence-to-label problem of line script identification. This makes it harder to train and inefficient to run. Second, the counting heuristic may be suboptimal compared to a learned model. Therefore we reframe line script identification as a sequence-to-label problem and solve it using two components, trained end-toend: Encoder and Summarizer. The encoder converts a line image into a feature sequence. The summarizer aggregates the sequence to classify the line. We test various summarizers with identical inception-style convolutional networks as encoders. Experiments on scanned books and photos containing 232 languages in 30 scripts show 16% reduction of script identification error rate compared to the baseline. This improved script identification reduces the character error rate attributable to script misidentification by 33%.

##### Abstract (translated by Google)
我们描述一种新的行级脚本识别方法。以前的工作改变了一个OCR模型生成每个字符的脚本代码，计数以获得行级脚本标识。这有两个缺点。首先，作为序列到序列的模型，它比线脚本识别的序列到标签问题更为复杂。这使得训练更加困难，运行效率低下。其次，与学习模型相比，计数启发式可能不是最佳的。因此，我们将行脚本标识重新构建为序列标签问题，并使用两个组件（经过训练的端到端：编码器和Summarizer）来解决此问题。编码器将线图像转换成特征序列。汇总器对序列进行汇总以对行进行分类。我们使用相同的初始式卷积网络作为编码器来测试各种总结器。扫描的书籍和包含232种语言的照片在30个脚本中的实验显示，与基线相比，脚本识别错误率降低了16％。这种改进的脚本识别将由脚本错误识别造成的字符错误率降低了33％。

##### URL
[https://arxiv.org/abs/1708.04671](https://arxiv.org/abs/1708.04671)

##### PDF
[https://arxiv.org/pdf/1708.04671](https://arxiv.org/pdf/1708.04671)

