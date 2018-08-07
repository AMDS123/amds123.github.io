---
layout: post
title: "Joint Image Captioning and Question Answering"
date: 2018-05-22 04:41:37
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge QA Caption VQA
author: Jialin Wu, Zeyuan Hu, Raymond J. Mooney
mathjax: true
---

* content
{:toc}

##### Abstract
Answering visual questions need acquire daily common knowledge and model the semantic connection among different parts in images, which is too difficult for VQA systems to learn from images with the only supervision from answers. Meanwhile, image captioning systems with beam search strategy tend to generate similar captions and fail to diversely describe images. To address the aforementioned issues, we present a system to have these two tasks compensate with each other, which is capable of jointly producing image captions and answering visual questions. In particular, we utilize question and image features to generate question-related captions and use the generated captions as additional features to provide new knowledge to the VQA system. For image captioning, our system attains more informative results in term of the relative improvements on VQA tasks as well as competitive results using automated metrics. Applying our system to the VQA tasks, our results on VQA v2 dataset achieve 65.8% using generated captions and 69.1% using annotated captions in validation set and 68.4% in the test-standard set. Further, an ensemble of 10 models results in 69.7% in the test-standard split.

##### Abstract (translated by Google)
回答视觉问题需要获取日常的常识并对图像中不同部分之间的语义连接进行建模，这对于VQA系统来说很难通过唯一的答案监督来学习图像。同时，具有光束搜索策略的图像字幕系统倾向于生成类似的字幕并且不能不同地描述图像。为了解决上述问题，我们提出了一个系统，让这两个任务相互补偿，能够共同产生图像标题和回答视觉问题。特别是，我们利用问题和图像功能生成与问题相关的标题，并使用生成的标题作为附加功能，为VQA系统提供新知识。对于图像字幕，我们的系统在VQA任务的相对改进以及使用自动化指标的竞争结果方面获得了更多信息。将我们的系统应用于VQA任务，我们在VQA v2数据集上的结果使用生成的标题达到65.8％，在验证集中使用带注释的标题达到69.1％，在测试标准集中达到68.4％。此外，10个模型的集合导致测试标准分割中的69.7％。

##### URL
[https://arxiv.org/abs/1805.08389](https://arxiv.org/abs/1805.08389)

##### PDF
[https://arxiv.org/pdf/1805.08389](https://arxiv.org/pdf/1805.08389)

