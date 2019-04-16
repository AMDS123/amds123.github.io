---
layout: post
title: "Partially-Supervised Image Captioning"
date: 2018-11-28 15:29:42
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption RNN Detection
author: Peter Anderson, Stephen Gould, Mark Johnson
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning models are becoming increasingly successful at describing the content of images in restricted domains. However, if these models are to function in the wild - for example, as assistants for people with impaired vision - a much larger number and variety of visual concepts must be understood. To address this problem, we teach image captioning models new visual concepts from labeled images and object detection datasets. Since image labels and object classes can be interpreted as partial captions, we formulate this problem as learning from partially-specified sequence data. We then propose a novel algorithm for training sequence models, such as recurrent neural networks, on partially-specified sequences which we represent using finite state automata. In the context of image captioning, our method lifts the restriction that previously required image captioning models to be trained on paired image-sentence corpora only, or otherwise required specialized model architectures to take advantage of alternative data modalities. Applying our approach to an existing neural captioning model, we achieve state of the art results on the novel object captioning task using the COCO dataset. We further show that we can train a captioning model to describe new visual concepts from the Open Images dataset while maintaining competitive COCO evaluation scores.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.06004](https://arxiv.org/abs/1806.06004)

##### PDF
[https://arxiv.org/pdf/1806.06004](https://arxiv.org/pdf/1806.06004)

