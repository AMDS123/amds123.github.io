---
layout: post
title: "Neural Baby Talk"
date: 2018-03-27 01:59:56
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption Detection
author: Jiasen Lu, Jianwei Yang, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel framework for image captioning that can produce natural language explicitly grounded in entities that object detectors find in the image. Our approach reconciles classical slot filling approaches (that are generally better grounded in images) with modern neural captioning approaches (that are generally more natural sounding and accurate). Our approach first generates a sentence `template' with slot locations explicitly tied to specific image regions. These slots are then filled in by visual concepts identified in the regions by object detectors. The entire architecture (sentence template generation and slot filling with object detectors) is end-to-end differentiable. We verify the effectiveness of our proposed model on different image captioning tasks. On standard image captioning and novel object captioning, our model reaches state-of-the-art on both COCO and Flickr30k datasets. We also demonstrate that our model has unique advantages when the train and test distributions of scene compositions -- and hence language priors of associated captions -- are different. Code has been made available at: this https URL

##### Abstract (translated by Google)
我们引入了一种新颖的图像字幕框架，它可以产生显然基于物体检测器在图像中找到的实体的自然语言。我们的方法将经典的槽填充方法（通常更好地基于图像）与现代神经字幕方法（通常更加自然的声音和准确）进行协调。我们的方法首先生成一个句子“模板”，其中插槽位置明确地与特定图像区域相关联。然后这些插槽由物体检测器在区域中标识的视觉概念填充。整个体系结构（语句模板生成和物体检测器插槽填充）是端到端可区分的。我们验证了我们提出的模型在不同图像字幕任务上的有效性。在标准图像字幕和新颖的对象字幕上，我们的模型在COCO和Flickr30k数据集上都达到了最新水平。我们还证明，当场景组合的训练和测试分布 - 因此语言先行的相关标题 - 不同时，我们的模型具有独特的优势。代码已在此https网址提供

##### URL
[https://arxiv.org/abs/1803.09845](https://arxiv.org/abs/1803.09845)

##### PDF
[https://arxiv.org/pdf/1803.09845](https://arxiv.org/pdf/1803.09845)

