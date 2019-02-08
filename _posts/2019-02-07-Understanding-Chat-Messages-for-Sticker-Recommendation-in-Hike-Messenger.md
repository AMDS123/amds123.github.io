---
layout: post
title: "Understanding Chat Messages for Sticker Recommendation in Hike Messenger"
date: 2019-02-07 16:01:43
categories: arXiv_CL
tags: arXiv_CL Embedding Prediction Recommendation
author: Abhishek Laddha, Mohamed Hanoosh, Debdoot Mukherjee
mathjax: true
---

* content
{:toc}

##### Abstract
Stickers are popularly used in messaging apps such as Hike to visually express a nuanced range of thoughts and utterances and convey exaggerated emotions. However, discovering the right sticker at the right time in a chat from a large and ever expanding pool of stickers can be cumbersome. In this paper, we describe a system for recommending stickers as users chat based on what the user is typing and the conversational context. We decompose the sticker recommendation problem into two steps. First, we predict the next message that the user is likely to send in the chat. Second, we substitute the predicted message with an appropriate sticker. Majority of Hike's users transliterate messages from their native language to English. This leads to numerous orthographic variations of the same message and thus complicates message prediction. To address this issue, we cluster the messages that have the same meaning and predict the message cluster instead of the message. We experiment with different approaches to train embedding for chat messages and study their efficacy in learning similar dense representations for messages that have the same intent. We propose a novel hybrid message prediction model, which can run with low latency on low end phones that have severe computational limitations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02704](http://arxiv.org/abs/1902.02704)

##### PDF
[http://arxiv.org/pdf/1902.02704](http://arxiv.org/pdf/1902.02704)

