---
layout: post
title: "Accurate Scene Text Detection through Border Semantics Awareness and Bootstrapping"
date: 2018-07-10 09:26:07
categories: arXiv_CV
tags: arXiv_CV Detection
author: Chuhui Xue, Shijian Lu, Fangneng Zhan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a scene text detection technique that exploits bootstrapping and text border semantics for accurate localization of texts in scenes. A novel bootstrapping technique is designed which samples multiple 'subsections' of a word or text line and accordingly relieves the constraint of limited training data effectively. At the same time, the repeated sampling of text 'subsections' improves the consistency of the predicted text feature maps which is critical in predicting a single complete instead of multiple broken boxes for long words or text lines. In addition, a semantics-aware text border detection technique is designed which produces four types of text border segments for each scene text. With semantics-aware text borders, scene texts can be localized more accurately by regressing text pixels around the ends of words or text lines instead of all text pixels which often leads to inaccurate localization while dealing with long words or text lines. Extensive experiments demonstrate the effectiveness of the proposed techniques, and superior performance is obtained over several public datasets, e. g. 80.1 f-score for the MSRA-TD500, 67.1 f-score for the ICDAR2017-RCTW, etc.

##### Abstract (translated by Google)
本文提出了一种场景文本检测技术，该技术利用自举和文本边界语义来精确定位场景中的文本。设计了一种新颖的自举技术，该技术对单词或文本行的多个“子部分”进行采样，从而有效地减轻了有限训练数据的约束。同时，对文本“子部分”的重复采样提高了预测文本特征映射的一致性，这对于预测单个完整而不是长字或文本行的多个破碎框是至关重要的。此外，设计了一种语义识别文本边界检测技术，该技术为每个场景文本产生四种类型的文本边界段。通过语义识别文本边框，可以通过回归单词或文本行的末端周围的文本像素而不是所有文本像素来更准确地定位场景文本，这通常导致在处理长单词或文本行时不准确的本地化。大量实验证明了所提出技术的有效性，并且在几个公共数据集上获得了优越的性能，例如， G。 MSRA-TD500的f-score为80.1，ICDAR2017-RCTW的得分为67.1，等等。

##### URL
[http://arxiv.org/abs/1807.03547](http://arxiv.org/abs/1807.03547)

##### PDF
[http://arxiv.org/pdf/1807.03547](http://arxiv.org/pdf/1807.03547)

