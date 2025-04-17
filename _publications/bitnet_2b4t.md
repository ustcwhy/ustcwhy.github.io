---
title: "BitNet b1.58 2B4T Technical Report"
date: 2025-04-17
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2504.12285'
---
<b>Abstract</b>: We introduce BitNet b1.58 2B4T, the first open-source, native 1-bit Large Language Model (LLM) at the 2-billion parameter scale. Trained on a corpus of 4 trillion tokens, the model has been rigorously evaluated across benchmarks covering language understanding, mathematical reasoning, coding proficiency, and conversational ability. Our results demonstrate that BitNet b1.58 2B4T achieves performance on par with leading open-weight, full-precision LLMs of similar size, while offering significant advantages in computational efficiency, including substantially reduced memory footprint, energy consumption, and decoding latency. To facilitate further research and adoption, the model weights are released via Hugging Face along with open-source inference implementations for both GPU and CPU architectures.

[Paper](https://arxiv.org/abs/2504.12285) 
[Inference code](https://github.com/microsoft/BitNet)
[Inference weights](https://huggingface.co/microsoft/bitnet-b1.58-2B-4T)
[Training weights](https://huggingface.co/microsoft/bitnet-b1.58-2B-4T-bf16)

Related works:
  1. BitNet (b1): https://arxiv.org/abs/2310.11453
  2. BitNet b1.58: https://arxiv.org/abs/2402.17764
  3. BitNet b1.58 Training tips & Code: https://github.com/microsoft/unilm/blob/master/bitnet/The-Era-of-1-bit-LLMs__Training_Tips_Code_FAQ.pdf
  4. BitNet a4.8: https://arxiv.org/abs/2411.04965
