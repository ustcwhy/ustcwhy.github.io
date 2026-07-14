---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Hongyu Wang** is a Ph.D. candidate (expected to graduate in July 2027) at the Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS), and the University of Chinese Academy of Sciences (UCAS), advised by Professor [Xilin Chen](http://vipl.ict.ac.cn/people/_xlchen/). His research interests include LLM pre-training, efficient foundation models, and scalable neural network architectures. He received his B.Eng. in Computer Science and Technology from the University of Science and Technology of China (USTC) in 2022. From August 2021 to June 2025, he was a Research Intern with the General Artificial Intelligence Group at Microsoft Research Asia, where he worked under the supervision of Dr. [Furu Wei](https://thegenerality.com/) and [Shuming Ma](https://scholar.google.com/citations?user=J44tjDMAAAAJ). 

His research has been published in leading AI venues, including TPAMI, JMLR, and ICML. His publications have received more than 1,470 citations on Google Scholar, with his most cited paper receiving over 850 citations. He is the lead author of **DeepNet** and **Magneto**, the first methods to successfully scale Transformer models beyond 1,000 layers. These techniques have been adopted by several prominent open-source foundation models, including GLM-130B, MiniMax-Text-01, and the EVA-ViT series. The open-source implementations have accumulated more than 3.1k GitHub stars. 

He also led the **BitNet** project, which introduced the first 1-bit large language model architecture and pre-training methodology, significantly reducing LLM inference costs. The work has received extensive coverage from international and Chinese technology media, including *TechCrunch*, *VentureBeat*, *Forbes*, and has attracted broad attention from both academia and industry. His **BitNet 2B4T** model is the first large language model with native 1.58-bit weights. It surpassed 120,000 downloads on HuggingFace within its first month of release, while its inference engine, **bitnet.cpp**, has received more than 39,700 GitHub stars and was featured during Microsoft's FY2025 Q3 earnings conference call. More recently, he proposed **BitVLA**, a lightweight 1.58-bit post-training quantization method for ViTs, enabling the first fully 1.58-bit VLM and VLA model. This work was awarded RMB 1 million in computing resources through the MiraclePlus Computing Grant Program.

*I have great interest on the following topics*: 
1. *Scale efficiently! Efficient architecture for the large-scale foundation models*
2. *Multimodal reasoning, robotics*

Contact: why0711@mail.ustc.edu.cn

<span style="color:red;"><strong>I’m currently open to full-time opportunities starting in Summer 2027. If you believe my background could be a good fit for your team, I’d be glad to talk.</strong></span>

## News:
- **[06/2025]** [<b>BitNet</b>](https://jmlr.org/papers/v26/24-2050.html) is accepted as the regular paper by JMLR 2025!
- **[06/2025]** Introducing [<span style="color:red;"><strong>BitVLA</strong></span>](https://arxiv.org/abs/2506.07530), the first 1-bit VLA model for robotics manipulation and multimodal tasks! [Model weights](https://huggingface.co/collections/hongyuw/bitvla-68468fb1e3aae15dd8a4e36e) and [code](https://github.com/ustcwhy/BitVLA) are public!
- **[05/2025]** [<span style="color:red;"><strong>Wrote a slides to review our exploration in BitNet series </strong></span>](https://github.com/ustcwhy/ustcwhy.github.io/blob/master/files/bitnet-20250527.pdf). Feel free to send your questions through e-mail.
- **[04/2025]** [<span style="color:red;"><strong>BitNet v2</strong></span>](https://arxiv.org/abs/2504.18415), native 4-bit activations for 1-bit LLMs.
- **[04/2025]** Introducing [<span style="color:red;"><strong>BitNet b1.58 2B4T</strong></span>](https://arxiv.org/abs/2504.12285), the first native 1-bit LLM trained at scale! [Model weights](https://huggingface.co/collections/microsoft/bitnet-67fddfe39a03686367734550) and [technical report](https://arxiv.org/abs/2504.12285) are public! Cooking larger models now...
- **[11/2024]** [<b>BitNet a4.8</b>](https://arxiv.org/abs/2411.04965), enabling 4-bit activations for 1-bit LLMs. BitNet a4.8 has only 55% active parameters and further supports 3-bit KV cache without extra training.
- **[10/2024]** [<b>bitnet.cpp</b>](https://github.com/microsoft/bitnet), the official inference framework for BitNet b1.58! <b>Run a 100B BitNet b1.58 model on a single CPU at a human reading speed!</b>
- **[07/2024]** [<b>Q-Sparse</b>](https://arxiv.org/abs/2407.10969), the fully Sparsely-Activated LLM.
- **[04/2024]** <b>DeepNet</b> is accepted as the regular paper by TPAMI 2024.
- **[03/2024]** [<b>BitNet b1.58: Training Tips, Code and FAQ. </b>](https://github.com/microsoft/unilm/blob/master/bitnet/The-Era-of-1-bit-LLMs__Training_Tips_Code_FAQ.pdf)
- **[02/2024]** [<b>BitNet b1.58</b>](https://arxiv.org/pdf/2402.17764.pdf), the first ternary LLM that matches the performance of FP16 LLM with siginificant reduction of inference cost (latency, memory, throughput, and energy consumption)

