---
layout: post
title: "A human-inspired recognition system for premodern Japanese historical documents"
date: 2019-05-14 03:26:25
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Recognition
author: Anh Duc Le, Tarin Clanuwat, Asanobu Kitamoto
mathjax: true
---

* content
{:toc}

##### Abstract
Recognition of historical documents is a challenging problem due to the noised, damaged characters and background. However, in Japanese historical documents, not only contains the mentioned problems, pre-modern Japanese characters were written in cursive and are connected. Therefore, character segmentation based methods do not work well. This leads to the idea of creating a new recognition system. In this paper, we propose a human-inspired document reading system to recognize multiple lines of premodern Japanese historical documents. During the reading, people employ eyes movement to determine the start of a text line. Then, they move the eyes from the current character/word to the next character/word. They can also determine the end of a line or skip a figure to move to the next line. The eyes movement integrates with visual processing to operate the reading process in the brain. We employ attention-based encoder-decoder to implement this recognition system. First, the recognition system detects where to start a text line. Second, the system scans and recognize character by character until the text line is completed. Then, the system continues to detect the start of the next text line. This process is repeated until reading the whole document. We tested our human-inspired recognition system on the pre-modern Japanese historical document provide by the PRMU Kuzushiji competition. The results of the experiments demonstrate the superiority and effectiveness of our proposed system by achieving Sequence Error Rate of 9.87% and 53.81% on level 2 and level 3 of the dataset, respectively. These results outperform to any other systems participated in the PRMU Kuzushiji competition.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05377](https://arxiv.org/abs/1905.05377)

##### PDF
[https://arxiv.org/pdf/1905.05377](https://arxiv.org/pdf/1905.05377)

