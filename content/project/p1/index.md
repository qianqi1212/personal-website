---
url_pdf: "https://github.com/qianqi1212/Gender-Debiasing-in-BERT-Model/blob/f170a73f4eb9dcfa4f05804a0fbb1a111c7521c6/EECS487_Final_Report.pdf"
summary: EECS 487 Natural Language Processing Final Project
url_video: ""
date: 2021-11-26T01:00:00.000Z
external_link: ""
url_slides: ""
title: Gender Debiasing in BERT Model
tags:
  - Natural Language Processing
  - Deep Learning
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/qianqi1212/Gender-Debiasing-in-BERT-Model.git
image:
  caption: ""
  focal_point: Smart
url_code: ""
---
Contextual language models (CLM) such as BERT has been proven to be powerful in many NLP tasks during recent years. However, the blind application of these models can possibly lead to amplification of the biases intrinsic within the original dataset used to train the model. It is shown in [previous work](https://arxiv.org/abs/2009.05021) that even for models like BERT, there exists some gender bias exhibited to an annoying extent.

In this project, we focus on detecting and reducing existing stereotypical conditions across gender while also ensuring the debiasing techniques do not go too far to affect underlying model performance by filtering a group of natural-gendered tokens and excluding them out during the debiasing process. We append an extra gender-debiasing layer after the word-embedding generation layer of BERT and implement two methods to reduce gender bias in word tokens:
* Use Iterative Nullspace Projection (INLP)
<img src="INLP_tSNE.png" alt="result" width="60%"/>
* Build a generative adversarial network (GAN)
<img src="GAN_tSNE.png" alt="result" width="60%"/>
