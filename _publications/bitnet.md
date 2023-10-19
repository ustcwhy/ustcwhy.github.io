---
title: "BitNet: Scaling 1-bit Transformers for Large Language Models"
date: 2023-10-18
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2310.11453'
---
<b>Abstract</b>: The increasing size of large language models has posed challenges for deployment and raised concerns about environmental impact due to high energy consumption. In this work, we introduce BitNet, a scalable and stable 1-bit Transformer architecture designed for large language models. Specifically, we introduce BitLinear as a drop-in replacement of the nn.Linear layer in order to train 1-bit weights from scratch. Experimental results on language modeling show that BitNet achieves competitive performance while substantially reducing memory footprint and energy consumption, compared to state-of-the-art 8-bit quantization methods and FP16 Transformer baselines. Furthermore, BitNet exhibits a scaling law akin to full-precision Transformers, suggesting its potential for effective scaling to even larger language models while maintaining efficiency and performance benefits.

[pdf](https://arxiv.org/pdf/2310.11453.pdf)
