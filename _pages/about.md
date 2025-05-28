---
layout: about
title: About
permalink: /
subtitle: Fourth-year Ph.D student@Institute of Automation, Chinese Academy of Sciences

[//]: # (<a href="/assets/pdf/cv.pdf"><i class="ai ai-cv-square ai-2x"></i></a>)
[//]: # (<a href="https://www.linkedin.com/in/yu-changqian/"><i class="fa-brands fa-linkedin fa-2x"></i></a>)
[//]: # (<a href="https://x.com/ChangqianYu"><i class="fa-brands fa-square-x-twitter fa-2x"></i></a>)
[//]: # (<a href="https://www.zhihu.com/people/yu-chang-qian"><i class="fa-brands fa-zhihu fa-2x"></i></a>)
[//]: # (<a href="https://huggingface.co/jinzhuoran" style="font-size: 24px; text-decoration: none;">🤗</a>)

profile:
  align: left
  image: bio_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
      <a href="https://scholar.google.com/citations?user=Am8WsCkAAAAJ&hl=en"><i class="ai ai-google-scholar-square ai-2x"></i></a>
      <a href="https://github.com/jinzhuoran"><i class="fa-brands fa-square-github fa-2x"></i></a>
      <a href="https://www.semanticscholar.org/author/Zhuoran-Jin/2152843772"><i class="ai ai-semantic-scholar-square ai-2x"></i></a>
news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
awards: true
social: false # includes social icons at the bottom of the page
---


I am a 4th-year Ph.D student at the Natural Language Processing and Knowledge Engineering Group (NLPKE), [Institute of Automation, Chinese Academy of Sciences (CASIA)](http://www.ia.ac.cn/). I am fortunate to be advised by [Prof. Jun Zhao](https://zhaojun-nlpr.github.io/). Before that, I obtained my B.E. degree in Software Engineering from [Northeastern University (NEU)](https://www.neu.edu.cn/) in 2021. My research interests include **natural language processing**, **large language models**, and **knowledge engineering**.

My research is dedicated to bridging the gap between **large language models** and **human knowledge frameworks**, with a focus on **expanding knowledge boundaries**, **erasing harmful knowledge**, and **improving reasoning capabilities**.
Recently, I have also become increasingly interested in **multimodal large language models**, particularly in understanding and enhancing their ability to **automatically solve complex and meaningful real-world problems**. My primary research areas are:

- **Retrieval-Augmented Generation**: RAG can effectively expand the internal memory boundaries of LLMs by providing external context. My work focuses on: (1) leveraging feedback reward signals from LLMs to improve retrieval quality ([InstructoR, EMNLP 2023](https://aclanthology.org/2023.findings-emnlp.443.pdf)); (2) investigating the mechanisms underlying knowledge conflicts between internal memory and external context ([Tug-of-War Between Knowledge, COLING 2024](https://aclanthology.org/2024.lrec-main.1466.pdf) and [Cutting Off the Head Ends the Conflict, ACL 2024](https://aclanthology.org/2024.findings-acl.70.pdf)); and (3) aligning RAG model behavior with human preferences through reward modeling ([RAG-RewardBench, ACL 2025](https://arxiv.org/pdf/2412.13746)).
- **Machine Unlearning**: Machine unlearning enables the targeted removal of sensitive, harmful, or copyrighted knowledge from models. To better evaluate unlearning in the domain of LLMs, we propose a Real-World Knowledge Unlearning benchmark ([RWKU, NeurIPS 2024](https://openreview.net/forum?id=wOmtZ5FgMH)). Building on this, we reveal the vulnerability of existing unlearning algorithms to adversarial attacks and propose Latent Adversarial Unlearning for robust unlearning ([LAU, AAAI 2025](https://ojs.aaai.org/index.php/AAAI/article/view/34769)). Moreover, to improve the naturalness of model responses after unlearning, we introduce an on-policy reinforcement learning framework that performs refusal boundary optimization ([RULE](https://github.com/chenlong-clock/RULE-Unlearn)).
- **Multimodal Reasoning**: Multimodal reasoning is a core capability for AI systems to solve real-world tasks. However, the extent to which current models have truly advanced in this ability remains unclear. To address this gap, my research mainly involves: (1) exploring what multimodal CoT reasoning can and cannot do, and revealing the reasoning limitation known as "Look Shallow, Think Deep" ([Look Shallow, Think Deep](https://openreview.net/forum?id=wOmtZ5FgMH)); (2) proposing a benchmark for multimodal video reasoning that exposes the challenges current models face in conducting long-range, multi-frame inference ([MMR-V](https://openreview.net/forum?id=wOmtZ5FgMH)).
- **Reward Modeling**: Reward models serve as a critical proxy for human values, guiding optimization in RLHF. We explore reward modeling in the contexts of RAG ([RAG-RewardBench, ACL 2025](https://arxiv.org/pdf/2412.13746)), agent (Agent-RewardBench, ACL 2025), and omni-modal scenarios ([Omni-Reward](https://omnireward.github.io/)).




If you are interested in my work or want to collaborate, feel free to contact me via: zhuoran.jin[at]nlpr[dot]ia[dot]ac.cn.
