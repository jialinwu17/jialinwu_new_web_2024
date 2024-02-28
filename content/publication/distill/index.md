---
title: Distilling vision-language models on millions of videos
publication_types: ['paper-conference']

authors:
  - Yue Zhao
  - Long Zhao
  - Xingyi Zhou
  - admin
  - Chun-Te Chu
  - Hui Miao
  - Florian Schroff
  - Hartwig Adam
  - Ting Liu
  - Boqing Gong
  - Philipp Krähenbühl
  - Liangzhe Yuan
publication_short: CVPR 2024
abstract: The recent advance in vision-language models is largely attributed to the abundance of image-text data. We aim to replicate this success for video-language models, but there simply is not enough human-curated video-text data available. We thus resort to fine-tuning a video-language model from a strong image-language baseline with synthesized instructional data. The resulting video-language model is then used to auto-label millions of videos to generate high-quality captions. We show the adapted video-language model performs well on a wide range of video-language benchmarks. For instance, it surpasses the best prior result on open-ended NExT-QA by 2.8%. Besides, our model generates detailed descriptions for previously unseen videos, which provide better textual supervision than existing methods. Experiments show that a video-language dual-encoder model contrastively trained on these auto-generated captions is 3.8% better than the strongest baseline that also leverages vision-language models. Our best model outperforms state-of-the-art methods on MSR-VTT zero-shot text-to-video retrieval by 6%.
draft: false
featured: false
date: 2024-01-23
---
