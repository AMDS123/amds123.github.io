---
layout: post
title: "Quality-Gated Convolutional LSTM for Enhancing Compressed Video"
date: 2019-03-28 16:26:59
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Relation
author: Ren Yang, Xiaoyan Sun, Mai Xu, Wenjun Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
The past decade has witnessed great success in applying deep learning to enhance the quality of compressed video. However, the existing approaches aim at quality enhancement on a single frame, or only using fixed neighboring frames. Thus they fail to take full advantage of the inter-frame correlation in the video. This paper proposes the Quality-Gated Convolutional Long Short-Term Memory (QG-ConvLSTM) network with bi-directional recurrent structure to fully exploit the advantageous information in a large range of frames. More importantly, due to the obvious quality fluctuation among compressed frames, higher quality frames can provide more useful information for other frames to enhance quality. Therefore, we propose learning the "forget" and "input" gates in the ConvLSTM cell from quality-related features. As such, the frames with various quality contribute to the memory in ConvLSTM with different importance, making the information of each frame reasonably and adequately used. Finally, the experiments validate the effectiveness of our QG-ConvLSTM approach in advancing the state-of-the-art quality enhancement of compressed video, and the ablation study shows that our QG-ConvLSTM approach is learnt to make a trade-off between quality and correlation when leveraging multi-frame information.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04596](http://arxiv.org/abs/1903.04596)

##### PDF
[http://arxiv.org/pdf/1903.04596](http://arxiv.org/pdf/1903.04596)

