---
layout: post
title: 'Improving Image Captioning by Concept-based Sentence Reranking'
date: 2017-12-06 08:49:46
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Detection
author: Xirong Li, Qin Jin
---

* content
{:toc}

##### Abstract
This paper describes our winning entry in the ImageCLEF 2015 image sentence generation task. We improve Google's CNN-LSTM model by introducing concept-based sentence reranking, a data-driven approach which exploits the large amounts of concept-level annotations on Flickr. Different from previous usage of concept detection that is tailored to specific image captioning models, the propose approach reranks predicted sentences in terms of their matches with detected concepts, essentially treating the underlying model as a black box. This property makes the approach applicable to a number of existing solutions. We also experiment with fine tuning on the deep language model, which improves the performance further. Scoring METEOR of 0.1875 on the ImageCLEF 2015 test set, our system outperforms the runner-up (METEOR of 0.1687) with a clear margin.

##### Abstract (translated by Google)
本文描述了我们在ImageCLEF 2015图像句子生成任务中的获奖条目。我们通过引入基于概念的句子重新排序来改进Google的CNN-LSTM模型，这是一种利用Flickr上的大量概念级注释的数据驱动方法。与之前使用的针对特定图像字幕模型的概念检测不同，该建议方法根据与检测到的概念匹配来重新排列预测句子，基本上将底层模型视为黑盒子。该属性使该方法适用于一些现有的解决方案。我们还在深度语言模型上进行了微调，进一步提高了性能。我们的系统在ImageCLEF 2015测试集上得分为0.1875的METEOR，表现优于亚军（METEOR为0.1687）。

##### URL
[https://arxiv.org/abs/1605.00855](https://arxiv.org/abs/1605.00855)

