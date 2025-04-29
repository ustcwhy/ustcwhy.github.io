---
title: "BitNet v2: Native 4-bit Activations with Hadamard Transformation for 1-bit LLMs"
date: 2025-04-25
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2504.18415'
---
<b>Abstract</b>: Efficient deployment of 1-bit Large Language Models (LLMs) is hindered by activation outliers, which complicate quantization to low bit-widths. We introduce BitNet v2, a novel framework enabling native 4-bit activation quantization for 1-bit LLMs. To tackle outliers in attention and feed-forward network activations, we propose H-BitLinear, a module applying an online Hadamard transformation prior to activation quantization. This transformation smooths sharp activation distributions into more Gaussian-like forms, suitable for low-bit representation. Experiments show BitNet v2 trained from scratch with 8-bit activations matches BitNet b1.58 performance. Crucially, BitNet v2 achieves minimal performance degradation when trained with native 4-bit activations, significantly reducing memory footprint and computational cost for batched inference.

[Paper](https://arxiv.org/abs/2504.18415) 
