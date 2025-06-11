---
title: "BitVLA: 1-bit Vision-Language-Action Models for Robotics Manipulation"
date: 2025-06-10
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2506.07530'
---
<b>Abstract</b>: Vision-Language-Action (VLA) models have shown impressive capabilities across a wide range of robotics manipulation tasks. However, their growing model size poses significant challenges for deployment on resource-constrained robotic systems. While 1-bit pretraining has proven effective for enhancing the inference efficiency of large language models with minimal performance loss, its application to VLA models remains underexplored. In this work, we present BitVLA, the first 1-bit VLA model for robotics manipulation, in which every parameter is ternary, i.e., {-1, 0, 1}. To further reduce the memory footprint of the vision encoder, we propose the distillation-aware training strategy that compresses the full-precision encoder to 1.58-bit weights. During this process, a full-precision encoder serves as a teacher model to better align latent representations. Despite the lack of large-scale robotics pretraining, BitVLA achieves performance comparable to the state-of-the-art model OpenVLA-OFT with 4-bit post-training quantization on the LIBERO benchmark, while consuming only 29.8% of the memory. These results highlight BitVLA's promise for deployment on memory-constrained edge devices. We release the code and model weights in [this https URL](https://github.com/ustcwhy/BitVLA).

[Paper](https://arxiv.org/abs/2506.07530) [Code](https://github.com/ustcwhy/BitVLA) [Model](https://huggingface.co/collections/hongyuw/bitvla-68468fb1e3aae15dd8a4e36e) 
