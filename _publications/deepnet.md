---
title: "DeepNet: Scaling Transformers to 1,000 Layers"
date: 2022-03-01
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence'
paperurl: 'https://arxiv.org/abs/2203.00555'
---
<b>Abstract</b>: In this paper, we propose a simple yet effective method to stabilize extremely deep Transformers. Specifically, we introduce a new normalization function (DeepNorm) to modify the residual connection in Transformer, accompanying with theoretically derived initialization. In-depth theoretical analysis shows that model updates can be bounded in a stable way. The proposed method combines the best of two worlds, i.e., good performance of Post-LN and stable training of Pre-LN, making DeepNorm a preferred alternative. We successfully scale Transformers up to 1,000 layers (i.e., 2,500 attention and feed-forward network sublayers) without difficulty, which is one order of magnitude deeper than previous deep Transformers. Remarkably, on a multilingual benchmark with 7,482 translation directions, our 200-layer model with 3.2B parameters significantly outperforms the 48-layer state-of-the-art model with 12B parameters by 5 BLEU points, which indicates a promising scaling direction.

[PDF](https://arxiv.org/abs/2203.00555) [Codes](https://github.com/microsoft/torchscale)
