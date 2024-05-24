## Awesome AGI Survey<br><sub>Must-read papers on Artificial General Intelligence</sub>
[![Arxiv Paper](https://img.shields.io/badge/Arxiv-Paper-brightred)](https://arxiv.org/pdf/2405.10313)
[![Workshop Link](https://img.shields.io/badge/Workshop-link-darkyellow)](https://agiworkshop.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/badge/PRs-welcome-brightgreen) ![](https://img.shields.io/github/stars/ulab-uiuc/AGI-survey?style=social) 

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/abstract.png" alt="Abstract Image">
</p>

## 🔔 News

- **[2024-05]** 🎉 We released our paper in arxiv: "[How Far Are We From AGI?](https://arxiv.org/pdf/2405.10313)".
- **[2024-05]** 🥳 We organized an ICLR 2024 Workshop on "How Far Are We From AGI". [Learn more about the workshop](https://agiworkshop.github.io).

🔥 Our project is an ongoing, open initiative that will evolve in parallel with advancements in AGI. We plan to add more work soon, and we highly welcome pull requests!

BibTex citation if you find our work/resources useful:

```bibtex
@article{feng2024far,
  title={How Far Are We From AGI},
  author={Feng, Tao and Jin, Chuanyang and Liu, Jingyu and Zhu, Kunlun and Tu, Haoqin and Cheng, Zirui and Lin, Guanyu and You, Jiaxuan},
  journal={arXiv preprint arXiv:2405.10313},
  year={2024}
}
```

# 📜Content

- [📜Content](#content)
  - [1. Introduction](#1-introduction)
  - [2. AGI Internal: Unveiling the Mind of AGI](#2-agi-internal-unveiling-the-mind-of-agi)
    - [2.1 AI Perception](#21-ai-perception)
    - [2.2 AI Reasoning](#22-ai-reasoning)
    - [2.3 AI Memory](#23-ai-memory)
    - [2.4 AI Metacognition](#24-ai-metacognition)
  - [3. AGI Interface: Connecting the World with AGI](#3-agi-interface-connecting-the-world-with-agi)
    - [3.1 AI Interfaces to Digital World](#31-ai-interfaces-to-digital-world)
    - [3.2 AI Interfaces to Physical World](#32-ai-interfaces-to-physical-world)
    - [3.3 AI Interfaces to Intelligence](#33-ai-interfaces-to-intelligence)
      - [3.3.1 AI Interfaces to AI Agents](#331-ai-interfaces-to-ai-agents)
      - [3.3.2 AI Interfaces to Human](#332-ai-interfaces-to-human)
  - [4. AGI Systems: Implementing the Mechanism of AGI](#4-agi-systems-implementing-the-mechanism-of-agi)
    - [4.2 Scalable Model Architectures](#42-scalable-model-architectures)
    - [4.3 Large-scale Training](#43-large-scale-training)
    - [4.4 Inference Techniques](#44-inference-techniques)
    - [4.5 Cost and Efficiency](#45-cost-and-efficiency)
    - [4.6 Computing Platforms](#46-computing-platforms)
  - [5. AGI Alignment: Ensuring AGI Meets Various Needs](#5-agi-alignment-ensuring-agi-meets-various-needs)
    - [5.1 Expectations of AGI Alignment](#51-expectations-of-agi-alignment)
    - [5.2 Current Alignment Techniques](#52-current-alignment-techniques)
    - [5.3 How to approach AGI Alignments](#53-how-to-approach-agi-alignments)
  - [6. AGI Roadmap: Responsibly Approaching AGI](#6-agi-roadmap-responsibly-approaching-agi)
    - [6.1 AI Levels: Charting the Evolution of Artificial Intelligence](#61-ai-levels-charting-the-evolution-of-artificial-intelligence)
    - [6.2 AGI Evaluation](#62-agi-evaluation)
      - [6.2.1 Expectations for AGI Evaluation](#621-expectations-for-agi-evaluation)
      - [6.2.2 Current Evaluations and Their Limitations](#622-current-evaluations-and-their-limitations)
    - [6.5 Further Considerations during AGI Development](#65-further-considerations-during-agi-development)
  - [7. Case Studies](#7-case-studies)
    - [7.1 AI for Science Discovery and Research](#71-ai-for-science-discovery-and-research)
    - [7.2 Generative Visual Intelligence](#72-generative-visual-intelligence)
    - [7.3 World Models](#73-world-models)
    - [7.4 Decentralized LLM](#74-decentralized-llm)
    - [7.5 AI for Coding](#75-ai-for-coding)
    - [7.6 AI for Robotics in Real World Applications](#76-ai-for-robotics-in-real-world-applications)
    - [7.7 Human-AI Collaboration](#77-human-ai-collaboration)

<p align="center">
  <figure>
    <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/intro.jpg" alt="intro">
  </figure>
</p>

-> **The framework design of our paper.** <-


## 1. Introduction

<p align="center">
  <figure>
    <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/f2-1.png" width="600">
  </figure>
</p>

-> **Proportion of Human Activities Surpassed by AI.** <-


## 2. AGI Internal: Unveiling the Mind of AGI

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/2a-1.png" width="600">
</p>

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/2b-1.png" width="600">
</p>

### 2.1 AI Perception

1. **Flamingo: a Visual Language Model for Few-Shot Learning**. *Jean-Baptiste Alayrac* et al. NeurIPS 2022. [[paper](https://arxiv.org/abs/2204.14198)]
2. **BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models**. *Junnan Li* et al. ICML 2023. [[paper](https://arxiv.org/abs/2301.12597)]
3. **SPHINX: The Joint Mixing of Weights, Tasks, and Visual Embeddings for Multi-modal Large Language Models**. *Ziyi Lin* et al. EMNLP 2023. [[paper](https://arxiv.org/abs/2311.07575)]
4. **Visual Instruction Tuning**. *Haotian Liu* et al. NeurIPS 2023. [[paper](https://arxiv.org/abs/2304.08485)]
5. **GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**. *Rui Yang* et al. NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.18752)]
6. **Otter: A Multi-Modal Model with In-Context Instruction Tuning**. *Bo Li* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.03726)]
7. **VideoChat: Chat-Centric Video Understanding**. *KunChang Li* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.06355)]
8. **mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality**. *Qinghao Ye* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2304.14178)]
9. **A Survey on Multimodal Large Language Models**. *Shukang Yin* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.13549)]
10. **PandaGPT: One Model To Instruction-Follow Them All**. *Yixuan Su* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.16355)]
11. **LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention**. *Renrui Zhang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2303.16199)]
12. **Gemini: A Family of Highly Capable Multimodal Models**. *Rohan Anil* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.11805)]
13. **Shikra: Unleashing Multimodal LLM's Referential Dialogue Magic**. *Keqin Chen* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.15195)]
14. **ImageBind: One Embedding Space To Bind Them All**. *Rohit Girdhar* et al. CVPR 2023. [[paper](https://arxiv.org/abs/2305.05665)]
15. **MobileVLM : A Fast, Strong and Open Vision Language Assistant for Mobile Devices**. *Xiangxiang Chu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.16886)]
16. **What Makes for Good Visual Tokenizers for Large Language Models?**. *Guangzhi Wang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.12223)]
17. **MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models**. *Deyao Zhu* et al. ICLR 2024. [[paper](https://arxiv.org/abs/2304.10592)]
18. **LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment**. *Bin Zhu* et al. ICLR 2024. [[paper](https://arxiv.org/abs/2310.01852)]

### 2.2 AI Reasoning

1. **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**. *Jason Wei* et al. NeurIPS 2022. [[paper](https://arxiv.org/abs/2201.11903)]
2. **Neural Theory-of-Mind? On the Limits of Social Intelligence in Large LMs**. *Maarten Sap* et al. EMNLP 2022. [[paper](https://arxiv.org/abs/2210.13312)]
3. **Inner Monologue: Embodied Reasoning through Planning with Language Models**. *Wenlong Huang* et al. CoRL 2022. [[paper](https://arxiv.org/abs/2207.05608)]
4. **Survey of Hallucination in Natural Language Generation**. *Ziwei Ji* et al. ACM Computing Surveys 2022. [[paper](https://arxiv.org/abs/2202.03629)]
5. **ReAct: Synergizing Reasoning and Acting in Language Models**. *Shunyu Yao* et al. ICLR 2023. [[paper](https://arxiv.org/abs/2210.03629)]
6. **Decomposed Prompting: A Modular Approach for Solving Complex Tasks**. *Tushar Khot* et al. ICLR 2023. [[paper](https://arxiv.org/abs/2210.02406)]
7. **Complexity-Based Prompting for Multi-Step Reasoning**. *Yao Fu* et al. ICLR 2023. [[paper](https://arxiv.org/abs/2210.00720)]
8. **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models**. *Denny Zhou* et al. ICLR 2023. [[paper](https://arxiv.org/abs/2205.10625)]
9. **Towards Reasoning in Large Language Models: A Survey**. *Jie Huang* et al. ACL Findings 2023. [[paper](https://arxiv.org/abs/2212.10403)]
10. **ProgPrompt: Generating Situated Robot Task Plans using Large Language Models**. *Ishika Singh* et al. ICRA 2023. [[paper](https://arxiv.org/abs/2209.11302)]
11. **Reasoning with Language Model is Planning with World Model**. *Shibo Hao* et al. EMNLP 2023. [[paper](https://arxiv.org/abs/2305.14992)]
12. **Evaluating Object Hallucination in Large Vision-Language Models**. *Yifan Li* et al. EMNLP 2023. [[paper](https://arxiv.org/abs/2305.10355)]
13. **Tree of Thoughts: Deliberate Problem Solving with Large Language Models**. *Shunyu Yao* et al. NeurIPS 2023. [[paper](https://arxiv.org/abs/2305.10601)]
14. **Self-Refine: Iterative Refinement with Self-Feedback**. *Aman Madaan* et al. NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.17651)]
15. **Reflexion: Language Agents with Verbal Reinforcement Learning**. *Noah Shinn* et al. NeurIPS 2023. [[paper](https://arxiv.org/abs/2303.11366)]
16. **Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents**. *Zihao Wang* et al. NeurIPS 2023. [[paper](https://arxiv.org/abs/2302.01560)]
17. **LLM+P: Empowering Large Language Models with Optimal Planning Proficiency**. *Bo Liu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2304.11477)]
18. **Language Models, Agent Models, and World Models: The LAW for Machine Reasoning and Planning**. *Zhiting Hu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.05230)]
19. **MMToM-QA: Multimodal Theory of Mind Question Answering**. *Chuanyang Jin* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2401.08743)]
20. **Graph of Thoughts: Solving Elaborate Problems with Large Language Models**. *Maciej Besta* et al. AAAI 2024. [[paper](https://arxiv.org/abs/2308.09687)]
21. **Achieving >97% on GSM8K: Deeply Understanding the Problems Makes LLMs Perfect Reasoners**. *Qihuang Zhong* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2404.14963)] **pending**

### 2.3 AI Memory

1. **Dense Passage Retrieval for Open-Domain Question Answering**. *Vladimir Karpukhin* et al. EMNLP 2020. [[paper](https://arxiv.org/abs/2004.04906)]
2. **Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks**. *Patrick Lewis* et al. NeurIPS 2020. [[paper](https://arxiv.org/abs/2005.11401)]
3. **REALM: Retrieval-Augmented Language Model Pre-Training**. *Kelvin Guu* et al. ICML 2020. [[paper](https://arxiv.org/abs/2002.08909)]
4. **Retrieval Augmentation Reduces Hallucination in Conversation**. *Kurt Shuster* et al. EMNLP Findings 2021. [[paper](https://arxiv.org/abs/2104.07567)]
5. **Improving Language Models by Retrieving from Trillions of Tokens**. *Sebastian Borgeaud* et al. ICML 2022. [[paper](https://arxiv.org/abs/2112.04426)]
6. **Generative Agents: Interactive Simulacra of Human Behavior**. *Joon Sung Park* et al. UIST 2023. [[paper](https://arxiv.org/abs/2304.03442)]
7. **Cognitive Architectures for Language Agents**. *Theodore R. Sumers* et al. TMLR 2024. [[paper](https://arxiv.org/abs/2309.02427)]
8. **Voyager: An Open-Ended Embodied Agent with Large Language Models**. *Guanzhi Wang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.16291)]
9. **A Survey on the Memory Mechanism of Large Language Model based Agents**. *Zeyu Zhang* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2404.13501)]
10. **Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models**. *Qingyue Wang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2308.15022)] **pending**

### 2.4 AI Metacognition

1. **The Consideration of Meta-Abilities in Tacit Knowledge Externalization and Organizational Learning**. *Jyoti Choudrie* et al. HICSS 2006. [[paper](https://uhra.herts.ac.uk/bitstream/handle/2299/8839/901794.pdf?sequence=1&isAllowed=y)]
2. **Evolving Self-supervised Neural Networks Autonomous Intelligence from Evolved Self-teaching**. *Nam Le*. arXiv 2019. [[paper](https://arxiv.org/abs/1906.08865)]
3. **Making pre-trained language models better few-shot learners**. *Tianyu Gao* et al. ACL 2021. [[paper](https://arxiv.org/abs/2012.15723)]
4. **Identifying and Manipulating the Personality Traits of Language Models**. *Graham Caron* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2212.10276)]
5. **Brainish: Formalizing A Multimodal Language for Intelligence and Consciousness**. *Paul Liang* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2205.00001)]
6. **A theory of consciousness from a theoretical computer science perspective: Insights from the Conscious Turing Machine**. *Lenore Blum* et al. PNAS 2022. [[paper](https://www.pnas.org/doi/full/10.1073/pnas.2115934119)]
7. **WizardLM: Empowering Large Language Models to Follow Complex Instructions**. *Can Xu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2304.12244)]
8. **Self-Instruct: Aligning Language Models with Self-Generated Instructions**. *Yizhong Wang* et al. ACL 2023. [[paper](https://arxiv.org/abs/2212.10560)]
9. **ReST meets ReAct: Self-Improvement for Multi-Step Reasoning LLM Agent**. *Renat Aksitov* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.10003)]
10. **The Cultural Psychology of Large Language Models: Is ChatGPT a Holistic or Analytic Thinker?**. *Chuanyang Jin* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2308.14242)]
11. **Consciousness in Artificial Intelligence: Insights from the Science of Consciousness**. *Patrick Butlin* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2308.08708)]
12. **Revisiting the Reliability of Psychological Scales on Large Language Models**. *Jen-tse Huang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.19926)]
13. **Evaluating and Inducing Personality in Pre-trained Language Models**. *Guangyuan Jiang* et al. NeurIPS 2024. [[paper](https://arxiv.org/abs/2206.07550)]
14. **Levels of AGI: Operationalizing Progress on the Path to AGI**. *Meredith Ringel Morris* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2311.02462)] **pending**
15. **Investigate-Consolidate-Exploit: A General Strategy for Inter-Task Agent Self-Evolution**. *Cheng Qian* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2401.13996)] **pending**


## 3. AGI Interface: Connecting the World with AGI

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/interface-1.png" width="600">
</p>


### 3.1 AI Interfaces to Digital World

1. **Principles of mixed-initiative user interfaces**. *Eric Horvitz.* SIGCHI 1999. [[paper](https://dl.acm.org/doi/pdf/10.1145/302979.303030)]
2. **The rise and potential of large language model based agents: A survey**. *Zhiheng Xi et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2309.07864)]
3. **Tool learning with foundation models**. *Yujia Qin et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.08354)]
4. **Creator: Disentangling abstract and concrete reasonings of large language models through tool creation**. *Cheng Qian et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2305.14318)]
5. **AppAgent: Multimodal Agents as Smartphone Users**. *Zhao Yang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2312.13771)]
6. **Mind2Web: Towards a Generalist Agent for the Web**. *Xiang Deng et al.* NeurIPS benchmark 2023. [[paper](https://openreview.net/forum?id=kiYqbO3wqw)]
7. **ToolQA: A Dataset for LLM Question Answering with External Tools**. *Yuchen Zhuang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2306.13304)]
8. **Generative agents: Interactive simulacra of human behavior**. *Joon Sung Park et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.03442)]
9. **Toolformer: Language models can teach themselves to use tools**. *Timo Schick et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2302.04761)]
10. **Gorilla: Large Language Model Connected with Massive APIs**. *Shishir G Patil et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2305.15334)]
11. **Voyager: An open-ended embodied agent with large language models**. *Guanzhi Wang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2305.16291)]
12. **OS-Copilot: Towards Generalist Computer Agents with Self-Improvement**. *Zhiyong Wu et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2402.07456)]
13. **WebArena: A Realistic Web Environment for Building Autonomous Agents**. *Shuyan Zhou et al.* ICLR 2024. [[paper](https://openreview.net/forum?id=oKn9c6ytLx)]
14. **Large Language Models as Tool Makers**. *Tianle Cai et al.* ICLR 2024. [[paper](https://openreview.net/forum?id=qV83K9d5WB)]


### 3.2 AI Interfaces to Physical World

1. **Lessons from the amazon picking challenge: Four aspects of building robotic systems**. *Clemens Eppner* et al. RSS 2016. [[paper](https://m.roboticsproceedings.org/rss12/p36.pdf)]
2. **Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**. *Mohit Shridhar* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2209.05451)]
3. **Vima: General robot manipulation with multimodal prompts**. *Yunfan Jiang* et al. arXiv 2022. [[paper](https://arxiv.org/abs/arXiv)]
4. **Do as i can, not as i say: Grounding language in robotic affordances**. *Michael Ahn* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2204.01691)]
5. **Voxposer: Composable 3d value maps for robotic manipulation with language models**. *Wenlong Huang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2307.05973)]
6. **MotionGPT: Human Motion as a Foreign Language**. *Biao Jiang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.14795)]
7. **Rt-2: Vision-language-action models transfer web knowledge to robotic control**. *Anthony Brohan* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2307.15818)]
8. **Navigating to objects in the real world**. *Theophile Gervet* et al. Science Robotics 2023. [[paper](https://arxiv.org/abs/2212.00922)]
9. **Lm-nav: Robotic navigation with large pre-trained models of language, vision, and action**. *Dhruv Shah* et al. CRL 2023. [[paper](https://proceedings.mlr.press/v205/shah23b/shah23b.pdf)]
10. **Palm-e: An embodied multimodal language model**. *Danny Driess* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2303.03378)]
11. **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**. *Chan Hee Song* et al. ICCV 2023. [[paper](https://arxiv.org/abs/2212.04088)]
12. **Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**. *Siyuan Huang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.11176)]
13. **DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**. *Alexander Khazatsky* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2403.12945)]
14. **BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation**. *Chengshu Li* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2403.09227)]


### 3.3 AI Interfaces to Intelligence

#### 3.3.1 AI Interfaces to AI Agents

1. **Counterfactual multi-agent policy gradients**. *Jakob Foerster* et al. AAAI 2018. [[paper](https://arxiv.org/abs/1705.08926)]
2. **Explanations from large language models make small reasoners better**. *Shiyang Li* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2210.06726)]
3. **In-context Learning Distillation: Transferring Few-shot Learning Ability of Pre-trained Language Models**. *Yukun Huang* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2212.10670)]
4. **Autoagents: A framework for automatic agent generation**. *Guangyao Chen* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.17288)]
5. **Neural amortized inference for nested multi-agent reasoning**.  *Kunal Jha* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2308.11071)]
6. **Knowledge Distillation of Large Language Models**. *Yuxian Gu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.08543)]
7. **Metagpt: Meta programming for multi-agent collaborative framework**. *Sirui Hong* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2308.00352)]
8. **Describe, explain, plan and select: Interactive planning with large language models enables open-world multi-task agents**. *Zihao Wang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2302.01560)]
9. **Agentverse: Facilitating multi-agent collaboration and exploring emergent behaviors in agents**. *Weize Chen* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2308.10848)]
10. **Mindstorms in natural language-based societies of mind**. *Mingchen Zhuge* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.17066)]
11. **Jarvis-1: Open-world multi-task agents with memory-augmented multimodal language models**. *Zihao Wang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2311.05997)]
12. **Symbolic Chain-of-Thought Distillation: Small Models Can Also "Think" Step-by-Step**. *Liunian Harold Li* et al. ACL 2023. [[paper](https://arxiv.org/abs/2306.14050)]
13. **Distilling step-by-step! outperforming larger language models with less training data and smaller model sizes**. *Cheng-Yu Hsieh* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.02301)]
14. **Weak-to-Strong Generalization: Eliciting Strong Capabilities With Weak Supervision**. *Collin Burns* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.09390)]
15. **Enhancing chat language models by scaling high-quality instructional conversations**. *Ning Ding* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.14233)]
16. **GAIA: a benchmark for General AI Assistants**. *Grégoire Mialon* et al. ICLR 2024. [[paper](https://arxiv.org/abs/2311.12983)]
17. **Voyager: An open-ended embodied agent with large language models**. *Guanzhi Wang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.16291)]
18. **Camel: Communicative agents for" mind" exploration of large scale language model society**. *Guohao Li* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2303.17760)]
19. **Tailoring self-rationalizers with multi-reward distillation**. *Sahana Ramnath* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2311.02805)]
20. **Vision Superalignment: Weak-to-Strong Generalization for Vision Foundation Models**. *Jianyuan Guo* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2402.03749)]
21. **WebArena: A Realistic Web Environment for Building Autonomous Agents**. *Shuyan Zhou* et al. ICLR 2024. [[paper](https://openreview.net/forum?id=oKn9c6ytLx)]
22. **Principle-driven self-alignment of language models from scratch with minimal human supervision**. *Zhiqing Sun* et al. NeurIPS 2024. [[paper](https://arxiv.org/abs/2305.03047)]
23. **Mind2web: Towards a generalist agent for the web**. *Xiang Deng* et al. NeurIPS 2024. [[paper](https://arxiv.org/abs/2306.06070)]
24. **Towards general computer control: A multimodal agent for red dead redemption ii as a case study**. *Weihao Tan* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2403.03186)]

#### 3.3.2 AI Interfaces to Human

1. **Guidelines for Human-AI Interaction**.
   *Saleema Amershi* et al. CHI 2019. [[paper](https://dl.acm.org/doi/10.1145/3290605.3300233)]
2. **Design Principles for Generative AI Applications**.
   *Justin D. Weisz* et al. CHI 2024. [[paper](http://arxiv.org/abs/2401.14484)]
3. **Graphologue: Exploring Large Language Model Responses with Interactive Diagrams**.
   *Peiling Jiang* et al. UIST 2023. [[paper](https://dl.acm.org/doi/10.1145/3586183.3606737)]
4. **Sensecape: Enabling Multilevel Exploration and Sensemaking with Large Language Models**.
   *Sangho Suh* et al. UIST 2023. [[paper](https://dl.acm.org/doi/10.1145/3586183.3606756)]
5. **Supporting Sensemaking of Large Language Model Outputs at Scale**.
   *Katy Ilonka Gero* et al. CHI 2024. [[paper](https://arxiv.org/abs/2401.13726)]
6. **Luminate: Structured Generation and Exploration of Design Space with Large Language Models for Human-AI Co-Creation**.
   *Sangho Suh* et al. CHI 2024. [[Paper](http://arxiv.org/abs/2310.12953)]
7. **AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts**.
   *Tongshuang Wu* et al. CHI 2022. [[paper](https://dl.acm.org/doi/10.1145/3491102.3517582)]
8. **Promptify: Text-to-Image Generation through Interactive Prompt Exploration with Large Language Models**.
   *Stephen Brade* et al. CHI 2023. [[paper](https://dl.acm.org/doi/10.1145/3586183.3606725)]
9. **ChainForge: A Visual Toolkit for Prompt Engineering and LLM Hypothesis Testing**.
   *Ian Arawjo* et al. CHI 2024. [[paper](https://doi.org/10.48550/arXiv.2309.09128)]
10. **CoPrompt: Supporting Prompt Sharing and Referring in Collaborative Natural Language Programming**.
    *Li Feng* et al. CHI 2024. [[paper](http://arxiv.org/abs/2310.09235)]
11. **Generating Automatic Feedback on UI Mockups with Large Language Models**.
    *Peitong Duan* et al. CHI 2024. [[paper](http://arxiv.org/abs/2403.13139)]
12. **Rambler: Supporting Writing With Speech via LLM-Assisted Gist Manipulation**.
    *Susan Lin* et al. CHI 2024. [[paper](http://arxiv.org/abs/2401.10838)]
13. **Embedding Large Language Models into Extended Reality: Opportunities and Challenges for Inclusion, Engagement, and Privacy**.
    *Efe Bozkir* et al. arXiv 2024. [[paper](http://arxiv.org/abs/2402.03907)]
14. **GenAssist: Making Image Generation Accessible**.
    *Mina Huh* et al. UIST 2023. [[paper](https://dl.acm.org/doi/10.1145/3586183.3606735)]
15. **“The less I type, the better”: How AI Language Models can Enhance or Impede Communication for AAC Users**.
    *Stephanie Valencia* et al. CHI 2023. [[paper](https://dl.acm.org/doi/10.1145/3544548.3581560)]
16. **Re-examining Whether, Why, and How Human-AI Interaction Is Uniquely Difficult to Design**.
    *Qian Yang* et al. CHI 2020. [[paper](https://dl.acm.org/doi/10.1145/3313831.3376301)]

## 4. AGI Systems: Implementing the Mechanism of AGI

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/system-1.png" width="600">
</p>

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/system_taxonomy.jpg" width="600">
</p>

### 4.2 Scalable Model Architectures

1. **Outrageously large neural networks: The sparsely-gated mixture-of-experts layer**. *Noam Shazeer* et al. arXiv 2017. [[paper](https://arxiv.org/abs/1701.06538)]
2. **Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention**. *Angelos Katharopoulos* et al. arXiv 2020. [[paper](https://arxiv.org/abs/2006.16236)]
3. **Longformer: The Long-Document Transformer**. *Iz Beltagy* et al. arXiv 2020. [[paper](https://arxiv.org/abs/2004.05150)]
4. **LightSeq: A High Performance Inference Library for Transformers**. *Xiaohui Wang* et al. arXiv 2021. [[paper](https://arxiv.org/abs/2010.13887)]
5. **Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity**. *William Fedus* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2101.03961)]
6. **Efficiently Modeling Long Sequences with Structured State Spaces**. *Albert Gu* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2111.00396)]
7. **MegaBlocks: Efficient Sparse Training with Mixture-of-Experts**. *Trevor Gale* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2211.15841)]
8. **Training Compute-Optimal Large Language Models**. *Jordan Hoffmann* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2203.15556)]
9. **Effective Long-Context Scaling of Foundation Models**. *Wenhan Xiong* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.16039)]
10. **Hyena Hierarchy: Towards Larger Convolutional Language Models**. *Michael Poli* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2302.10866)]
11. **Stanford Alpaca: An Instruction-following LLaMA model**. *Rohan Taori* et al. GitHub 2023. [[code](https://github.com/tatsu-lab/stanford_alpaca)]
12. **Rwkv: Reinventing rnns for the transformer era**. *Bo Peng* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.13048)]
13. **Deja Vu: Contextual Sparsity for Efficient LLMs at Inference Time**. *Zichang Liu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2310.17157)]
14. **Flash-LLM: Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity**. *Haojun Xia* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.10285)]
15. **ByteTransformer: A High-Performance Transformer Boosted for Variable-Length Inputs**. *Yujia Zhai* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2210.03052)]
16. **Tutel: Adaptive Mixture-of-Experts at Scale**. *Changho Hwang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2206.03382)]
17. **Mamba: Linear-Time Sequence Modeling with Selective State Spaces**. *Albert Gu, Tri Dao.* arXiv 2023. [[paper](https://arxiv.org/abs/2312.00752)]
18. **Hungry Hungry Hippos: Towards Language Modeling with State Space Models**. *Daniel Y. Fu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2212.14052)]
19. **Retentive Network: A Successor to Transformer for Large Language Models**. *Yutao Sun* et al. ArXiv, 2023.
20. **Mechanistic Design and Scaling of Hybrid Architectures**. *Michael Poli* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2403.17844)]
21. **Revisiting Knowledge Distillation for Autoregressive Language Models**. *Qihuang Zhong* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2402.11890)]
22. **DB-LLM: Accurate Dual-Binarization for Efficient LLMs**. *Hong Chen* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2402.11960)]
23. **Reducing Transformer Key-Value Cache Size with Cross-Layer Attention**. *William Brandon* et al. arXiv 2024.[[paper](https://arxiv.org/abs/2405.12981)]
24. **You Only Cache Once: Decoder-Decoder Architectures for Language Models** *Yutao Sun* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2405.05254)]

### 4.3 Large-scale Training

1. **Training Deep Nets with Sublinear Memory Cost**. *Tianqi Chen et al.* arXiv 2016. [[paper](https://arxiv.org/abs/1604.06174)]
2. **Beyond Data and Model Parallelism for Deep Neural Networks**. *Zhihao Jia et al.* arXiv 2018. [[paper](https://arxiv.org/abs/1807.05358)]
3. **GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism**. *Yanping Huang et al.* arXiv 2019. [[paper](https://arxiv.org/abs/1811.06965)]
4. **Parameter-Efficient Transfer Learning for NLP**. *Neil Houlsby et al.* ICML 2019. [paper](https://arxiv.org/abs/1902.00751)
5. **Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism**. *Mohammad Shoeybi et al.* arXiv 2020. [[paper](https://arxiv.org/abs/1909.08053)]
6. **Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning**. *Lianmin Zheng et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2201.12023)]
7. **DeepSpeed Inference: Enabling Efficient Inference of Transformer Models at Unprecedented Scale**. *Reza Yazdani Aminabadi et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2207.00032)]
8. **Memorization Without Overfitting: Analyzing the Training Dynamics of Large Language Models**. *Kushal Tirumala et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2205.10770)]
9. **SWARM Parallelism: Training Large Models Can Be Surprisingly Communication-Efficient**. *Max Ryabinin et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2301.11913)]
10. **Training Trajectories of Language Models Across Scales**. *Mengzhou Xia et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2212.09803)]
11. **HexGen: Generative Inference of Foundation Model over Heterogeneous Decentralized Environment**. *Youhe Jiang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2311.11514)]
12. **FusionAI: Decentralized Training and Deploying LLMs with Massive Consumer-Level GPUs**. *Zhenheng Tang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2309.01172)]
13. **Ring Attention with Blockwise Transformers for Near-Infinite Context**. *Hao Liu et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2310.01889)]
14. **Pythia: A Suite for Analyzing Large Language Models Across Training and Scaling**. *Stella Biderman et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.01373)]
15. **Fine-tuning Language Models over Slow Networks using Activation Compression with Guarantees**. *Jue Wang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2206.01299)]
16. **LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention**. *Renrui Zhang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2303.16199)]
17. **QLoRA: Efficient Finetuning of Quantized LLMs**. *Tim Dettmers et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2305.14314)]
18. **Efficient Memory Management for Large Language Model Serving with PagedAttention**. *Woosuk Kwon et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2309.06180)]
19. **Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache**. *Bin Lin et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2401.02669)]
20. **OLMo: Accelerating the Science of Language Models**. *Dirk Groeneveld et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2402.00838)]
21. **On Efficient Training of Large-Scale Deep Learning Models: A Literature Review**. *Li Shen et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.03589)] **pending**

### 4.4 Inference Techniques

1. **FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness**. *Tri Dao* et al. NeurIPS 2022. [[paper](https://arxiv.org/abs/2205.14135)]
2. **Draft \& Verify: Lossless Large Language Model Acceleration via Self-Speculative Decoding**. *Jun Zhang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2309.08168)]
3. **Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems**. *Xupeng Miao et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2312.15234)]
4. **FlashDecoding++: Faster Large Language Model Inference on GPUs**. *Ke Hong et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2311.01282)]
5. **Fast Inference from Transformers via Speculative Decoding**. *Yaniv Leviathan et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2211.17192)]
6. **Fast Distributed Inference Serving for Large Language Models**. *Bingyang Wu et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2305.05920)]
7. **S-LoRA: Serving Thousands of Concurrent LoRA Adapters**. *Ying Sheng et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2311.03285)]
8. **TensorRT-LLM: A TensorRT Toolbox for Optimized Large Language Model Inference**. *NVIDIA.* GitHub 2023. [[code](https://github.com/NVIDIA/TensorRT-LLM)]
9. **Punica: Multi-Tenant LoRA Serving**. *Lequn Chen et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2310.18547)]
10. **S$^3: Increasing GPU Utilization during Generative Inference for Higher Throughput**. *Yunho Jin et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2306.06000)]
11. **Multi-LoRA inference server that scales to 1000s of fine-tuned LLMs**. *Predibase.* GitHub 2023. [[code](https://github.com/predibase/lorax)]
12. **Prompt Lookup Decoding**. *Apoorv Saxena.* GitHub 2023. [[code](https://github.com/apoorvumang/prompt-lookup-decoding)]
13. **FasterTransformer**. *NVIDIA.* GitHub 2021. [[paper](https://github.com/NVIDIA/FasterTransformer)]
14. **DeepSpeed-FastGen: High-throughput Text Generation for LLMs via MII and DeepSpeed-Inference**. *Connor Holmes et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2401.08671)]
15. **SpecInfer: Accelerating Generative Large Language Model Serving with Tree-based Speculative Inference and Verification**. *Xupeng Miao et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2305.09781)]
16. **Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads**. *Tianle Cai et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2401.10774)]
17. **Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs**. *Suyu Ge et al.* ICLR 2024. [[paper](https://openreview.net/forum?id=uNrFpDPMyo)]
18. **Efficient Streaming Language Models with Attention Sinks**. *Guangxuan Xiao et al.* ICLR 2024. [[paper](https://arxiv.org/abs/2309.17453)]
19. **DeFT: Flash Tree-attention with IO-Awareness for Efficient Tree-search-based LLM Inference**. *Jinwei Yao et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2404.00242)]
20. **Efficiently Programming Large Language Models using SGLang**. *Lianmin Zheng et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2312.07104)]
21. **SPEED: Speculative Pipelined Execution for Efficient Decoding**. *Coleman Hooper et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2310.12072)]
22. **Sequoia: Scalable, Robust, and Hardware-aware Speculative Decoding**. *Zhuoming Chen et al.* arXiv 2024. [[paper](https://arxiv.org/pdf/2402.12374)] **pending**
    
### 4.5 Cost and Efficiency

1. **Demonstrate-Search-Predict: Composing Retrieval and Language Models for Knowledge-Intensive NLP**. *Omar Khattab et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2212.14024)]
2. **Automated Machine Learning: Methods, Systems, Challenges**. *Frank Hutter et al.* Springer Publishing Company, Incorporated, 2019.
3. **Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time**. *Mitchell Wortsman et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2203.05482)]
4. **Data Debugging with Shapley Importance over End-to-End Machine Learning Pipelines**. *Bojan Karlaš et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2204.11131)]
5. **Cost-Effective Hyperparameter Optimization for Large Language Model Generation Inference**. *Chi Wang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2303.04673)]
6. **Large Language Models Are Human-Level Prompt Engineers**. *Yongchao Zhou et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2211.01910)]
7. **Merging by Matching Models in Task Subspaces**. *Derek Tam et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2312.04339)]
8. **Editing Models with Task Arithmetic**. *Gabriel Ilharco et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2212.04089)]
9. **PriorBand: Practical Hyperparameter Optimization in the Age of Deep Learning**. *Neeratyoy Mallik et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2306.12370)]
10. **An Empirical Study of Multimodal Model Merging**. *Yi-Lin Sung et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.14933)]
11. **DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines**. *Omar Khattab et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2310.03714)]
12. **FrugalGPT: How to Use Large Language Models While Reducing Cost and Improving Performance**. *Lingjiao Chen et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2305.05176)]
13. **Tandem Transformers for Inference Efficient LLMs**. *Aishwarya P S et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2402.08644)]
14. **AIOS: LLM Agent Operating System**. *Kai Mei et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2403.16971)]
15. **LoraHub: Efficient Cross-Task Generalization via Dynamic LoRA Composition**. *Chengsong Huang et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2307.13269)]
16. **AutoML in the Age of Large Language Models: Current Challenges, Future Opportunities and Risks**. *Alexander Tornede et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2306.08107)]
17. **Merging Experts into One: Improving Computational Efficiency of Mixture of Experts**. *Shwai He et al.* EMNLP 2023. [[paper](https://arxiv.org/abs/2310.09832)] **pending**

### 4.6 Computing Platforms

1. **TVM: An Automated End-to-End Optimizing Compiler for Deep Learning**. *Tianqi Chen et al.* arXiv 2018. [[paper](https://arxiv.org/abs/1802.04799)]
2. **TPU v4: An Optically Reconfigurable Supercomputer for Machine Learning with Hardware Support for Embeddings**. *Norman P. Jouppi et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.01433)]


## 5. AGI Alignment: Ensuring AGI Meets Various Needs

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/AGI_Alignment-1.png" width="600">
</p>


### 5.1 Expectations of AGI Alignment

1. **Human Compatible: Artificial Intelligence and the Problem of Control**.
   *Stuart Russell*. Viking, 2019.
2. **Artificial Intelligence, Values and Alignment**.
   *Iason Gabriel*. Minds and Machines, 2020. [[paper](http://arxiv.org/abs/2001.09768)]
3. **Alignment of Language Agents**.
   *Zachary Kenton* et al. arXiv, 2021. [[Paper](http://arxiv.org/abs/2103.14659)]
4. **The Value Learning Problem**.
   *Nate Soares*. Machine Intelligence Research Institute Technical Report [[paper](https://intelligence.org/files/ValueLearningProblem.pdf)]
5. **Concrete Problems in AI Safety**.
   *Dario Amodei* et al. arXiv, 2016. [[paper](http://arxiv.org/abs/1606.06565)]
6. **Ethical and social risks of harm from Language Models**.
   *Laura Weidinger* et al. arXiv, 2021. [[paper](http://arxiv.org/abs/2112.04359)]
7. **On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?**.
   *Emily M. Bender* et al. FAccT 2021. [[paper](https://dl.acm.org/doi/10.1145/3442188.3445922)]
8. **The global landscape of AI ethics guidelines**.
   *Anna Jobin* et al. Nature Machine Intelligence, 2019. [[paper](https://www.nature.com/articles/s42256-019-0088-2)]
9. **Persistent Anti-Muslim Bias in Large Language Models**.
   *Abubakar Abid* et al. AIES, 2021. [[paper](http://arxiv.org/abs/2101.05783)]
10. **Toward Gender-Inclusive Coreference Resolution**.
      *Yang Trista Cao* et al. ACL, 2020. [[paper](https://aclanthology.org/2020.acl-main.418)]
11. **The Social Impact of Natural Language Processing**.
    *Dirk Hovy* et al. ACL 2016. [[paper](https://aclanthology.org/P16-2096)]
12. **TruthfulQA: Measuring How Models Mimic Human Falsehoods**.
    *Stephanie Lin* et al. ACL 2022. [[paper](https://aclanthology.org/2022.acl-long.229)]
13. **The Radicalization Risks of GPT-3 and Advanced Neural Language Models**.
    *Kris McGuffie* et al. arXiv, 2020. [[paper](http://arxiv.org/abs/2009.06807)]
14. **AI Transparency in the Age of LLMs: A Human-Centered Research Roadmap**.
    *Q. Vera Liao* et al. arXiv 2023. [[paper](http://arxiv.org/abs/2306.01941)]
15. **Beyond Expertise and Roles: A Framework to Characterize the Stakeholders of Interpretable Machine Learning and their Needs**.
    *Harini Suresh* et al. CHI 2021. [[paper](https://dl.acm.org/doi/10.1145/3411764.3445088)]
16. **Identifying and Mitigating the Security Risks of Generative AI**.
    *Clark Barrett* et al. arXiv, 2023. [[paper](http://arxiv.org/abs/2308.14840)]
17. **LLM Agents can Autonomously Hack Websites**.
    *Richard Fang* et al. arXiv, 2024. [[paper](http://arxiv.org/abs/2402.06664)]
18. **Deepfakes, Phrenology, Surveillance, and More! A Taxonomy of AI Privacy Risks**.
    *Hao-Ping Lee* et al. CHI 2024. [[paper](http://arxiv.org/abs/2310.07879)]
19. **Privacy in the Age of AI**.
    *Sauvik Das* et al. Communications of the ACM, 2023. [[paper](https://dl.acm.org/doi/10.1145/3625254)]

### 5.2 Current Alignment Techniques

1. **Learning to summarize with human feedback**. *Nisan Stiennon* et al. NeurIPS 2020. [[paper](https://arxiv.org/abs/2009.01325)]
2. **Second thoughts are best: Learning to re-align with human values from text edits**. *Ruibo Liu* et al. NeurIPS 2022. [[paper](https://arxiv.org/abs/2301.00355)]
3. **Training language models to follow instructions with human feedback**. *Long Ouyang* et al. NeurIPS 2022. [[paper](https://arxiv.org/abs/2203.02155)]
4. **Leashing the Inner Demons: Self-Detoxification for Language Models**. *Canwen Xu* et al. AAAI 2022. [paper](https://arxiv.org/abs/2203.03072)
5. **Aligning generative language models with human values**. *Ruibo Liu* et al. NAACL 2022. [[paper](https://aclanthology.org/2022.findings-naacl.18/)]
6. **Training a helpful and harmless assistant with reinforcement learning from human feedback**. *Yuntao Bai* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2204.05862)]
7. **Constitutional AI: Harmlessness from AI Feedback**. *Yuntao Bai* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2212.08073)]
8. **Raft: Reward ranked finetuning for generative foundation model alignment**. *Hanze Dong* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2304.06767)]
9. **Improving Language Models with Advantage-based Offline Policy Gradients**. *Ashutosh Baheti* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.14718)]
10. **Training language models with language feedback at scale**. *Jérémy Scheurer* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2303.16755)]
11. **A general theoretical paradigm to understand learning from human preferences**. *Mohammad Gheshlaghi Azar* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2310.12036)]
12. **Let's Verify Step by Step**. *Hunter Lightman* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.20050)]
14. **Open problems and fundamental limitations of reinforcement learning from human feedback**. *Stephen Casper* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2307.15217)]
15. **Aligning Large Language Models through Synthetic Feedback**. *Sungdong Kim* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.13735)]
16. **RLAIF: Scaling Reinforcement Learning from Human Feedback with AI Feedback**. *Harrison Lee* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.00267)]
17. **Preference ranking optimization for human alignment**. *Feifan Song* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.17492)]
18. **Improving Factuality and Reasoning in Language Models through Multiagent Debate**. *Yilun Du* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.14325)]
19. **Large language model alignment: A survey**. *Tianhao Shen* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.15025)]
20. **Direct preference optimization: Your language model is secretly a reward model**. *Rafael Rafailov* et al. NeurIPS 2024. [[paper](https://arxiv.org/abs/2305.18290)]
21. **Lima: Less is more for alignment**. *Chunting Zhou* et al. NeurIPS 2024. [[paper](https://arxiv.org/abs/2305.11206)]

### 5.3 How to approach AGI Alignments

1. **Ethical and social risks of harm from Language**. *Mellor Weidinger* et al. arXiv 2021. [[paper](https://arxiv.org/abs/2112.04359)]
2. **Beijing AI Safety International Consensus**. *Beijing Academy of Artificial Intelligence.* 2024. [[paper](https://news.cgtn.com/news/2024-03-14/VHJhbnNjcmlwdDc3NzI1/index.html)]
3. **Counterfactual Explanations without Opening the Black Box: Automated Decisions and the GDPR**. *Sandra Wachter* et al. Harvard Journal of Law \& Technology, 2017. [[paper](https://arxiv.org/abs/1711.00399)]
4. **Scalable agent alignment via reward modeling: a research direction**. *Jan Leike* et al. arXiv 2018. [[paper](https://arxiv.org/abs/1811.07871)]
5. **Building Ethics into Artificial Intelligence**. *Han Yu* et al. IJCAI 2018. [paper](https://arxiv.org/abs/1812.02953)
6. **Human Compatible: Artificial Intelligence and the Problem of Control**. *Stuart Russell*. Viking, 2019. [[paper](https://people.eecs.berkeley.edu/~russell/papers/mi19book-hcai.pdf)]
7. **Responsible artificial intelligence: How to develop and use AI in a responsible way**. *Virginia Dignum*. Springer Nature, 2019. [[paper](https://link.springer.com/book/10.1007/978-3-030-30371-6)]
8. **Machine Ethics: The Design and Governance of Ethical AI and Autonomous Systems**. *Alan F. Winfield* et al. Proceedings of the IEEE, 2019. [[paper](https://ieeexplore.ieee.org/document/8662743)]
9. **Open problems in cooperative AI**. *Allan Dafoe* et al. arXiv 2020. [[paper](https://arxiv.org/abs/2012.08630)]
10. **Artificial intelligence, values, and alignment**. *Iason Gabriel*. Minds and Machines, 2020. [[paper](https://arxiv.org/abs/2001.09768)]
11. **Cooperative AI: machines must learn to find common ground**. *Allan Dafoe* et al. Nature 2021. [[paper](https://www.nature.com/articles/d41586-021-01170-0)]
12. **Machine morality, moral progress, and the looming environmental disaster**. *Ben Kenward* et al. arXiv 2021. [[paper](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/ccs2.12027)]
13. **X-risk analysis for ai research**. *Dan Hendrycks* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2206.05862)]
14. **Task decomposition for scalable oversight (AGISF Distillation)**. *Charbel-Raphaël Segerie.* blog 2023. [[blog](https://www.lesswrong.com/posts/FFz6H35Gy6BArHxkc/ais-101-task-decomposition-for-scalable-oversight)]
15. **Weak-to-Strong Generalization: Eliciting Strong Capabilities With Weak Supervision**. *Collin Burns,* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.09390)]
16. **Whose opinions do language models reflect?**. *Shibani Santurkar* et al. ICML 2023. [[paper](https://arxiv.org/abs/2303.17548)]
17. **Ai alignment: A comprehensive survey**. *Jiaming Ji* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2310.19852)]
18. **Open problems and fundamental limitations of reinforcement learning from human feedback**. *Stephen Casper* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2307.15217)]
19. **The Unlocking Spell on Base LLMs: Rethinking Alignment via In-Context Learning**. *Bill Yuchen Lin* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.01552)]
20. **Large Language Model Alignment: A Survey**. *Tianhao Shen* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.15025)]

## 6. AGI Roadmap: Responsibly Approaching AGI

### 6.1 AI Levels: Charting the Evolution of Artificial Intelligence

1. **Sparks of Artificial General Intelligence: Early experiments with GPT-4**. *Sébastien Bubeck* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2303.12712)]
2. **Levels of AGI: Operationalizing Progress on the Path to AGI**. *Meredith Ringel Morris* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2311.02462)]


### 6.2 AGI Evaluation

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/levels-1.png" width="600">
</p>

#### 6.2.1 Expectations for AGI Evaluation

1. **Towards the systematic reporting of the energy and carbon footprints of machine learning**. *Peter Henderson et al.* Journal of Machine Learning Research, 2020.
2. **Green ai**. *Roy Schwartz* Communications of the ACM, 2020.
3. **Evaluating Large Language Models Trained on Code**. *Mark Chen et al.* No journal, 2021.
4. **Documenting large webtext corpora: A case study on the colossal clean crawled corpus**. *Jesse Dodge et al.* arXiv 2021. [[paper](https://arxiv.org/abs/2104.08758)]
5. **On the opportunities and risks of foundation models**. *Rishi Bommasani et al.* arXiv 2021. [[paper](https://arxiv.org/abs/2108.07258)]
6. **Human-like systematic generalization through a meta-learning neural network**. *Brenden M Lake et al.* Nature, 2023. [[paper](https://www.nature.com/articles/s41586-023-06668-3)]
7. **SuperBench is Measuring LLMs in The Open: A Critical Analysis**. *SuperBench Team.* arXiv 2023.
8. **Holistic Evaluation of Language Models**. *Percy Liang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2211.09110)]


#### 6.2.2 Current Evaluations and Their Limitations

1. **SQuAD: 100,000+ Questions for Machine Comprehension of Text**. *Pranav Rajpurkar et al.* arXiv 2016. [[paper](https://arxiv.org/abs/1606.05250)]
2. **TriviaQA: A Large Scale Distantly Supervised Challenge Dataset for Reading Comprehension**. *Mandar Joshi et al.* arXiv 2017. [[paper](https://arxiv.org/abs/1705.03551)]
3. **Coqa: A conversational question answering challenge**. *Siva Reddy et al.* Transactions of the Association for Computational Linguistics, 2019.
4. **Accurate, reliable and fast robustness evaluation**. *Wieland Brendel et al.* NeurIPS 2019. [[paper](https://arxiv.org/abs/1907.01003)]
5. **Measuring massive multitask language understanding**. *Dan Hendrycks et al.* arXiv 2020. [[paper](https://arxiv.org/abs/2009.03300)]
6. **Evaluating model robustness and stability to dataset shift**. *Adarsh Subbaswamy et al.* Presented at International conference on artificial intelligence and statistics, 2021. [paper](https://arxiv.org/abs/2010.15100)
7. **Mmdialog: A large-scale multi-turn dialogue dataset towards multi-modal open-domain conversation**. *Jiazhan Feng et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2211.05719)]
8. **Self-instruct: Aligning language models with self-generated instructions**. *Yizhong Wang et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2212.10560)]
9. **Super-naturalinstructions: Generalization via declarative instructions on 1600+ nlp tasks**. *Yizhong Wang et al.* arXiv 2022. [[paper](https://arxiv.org/abs/2204.07705)]
10. **Holistic analysis of hallucination in gpt-4v (ision): Bias and interference challenges**. *Chenhang Cui et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2311.03287)]
11. **Evaluating the Robustness to Instructions of Large Language Models**. *Yuansheng Ni et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2308.14306)]
12. **GAIA: a benchmark for General AI Assistants**. *Grégoire Mialon et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2311.12983)]
13. **A Comprehensive Evaluation Framework for Deep Model Robustness**. *Jun Guo et al.* Pattern Recognition, 2023. [[paper](https://arxiv.org/abs/2101.09617)]
14. **Agieval: A human-centric benchmark for evaluating foundation models**. *Wanjun Zhong et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2304.06364)]
15. **Mmmu: A massive multi-discipline multimodal understanding and reasoning benchmark for expert agi**. *Xiang et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2311.16502)]
16. **Evaluating Large Language Model Creativity from a Literary Perspective**. *Murray Shanahan et al.* arXiv 2023. [[paper](https://arxiv.org/abs/2312.03746)]
17. **AgentBench: Evaluating LLM**. *Xiao Liu et al.* ICLR 2024. [[paper](https://openreview.net/forum?id=zAdUB0aCTQ)]
18. **Assessing and Understanding Creativity in Large Language Models**. *Yunpu Zhao et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2401.12491)]
19. **Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena**. *Lianmin Zheng et al.* NeurIPS 2024. [[paper](https://arxiv.org/abs/2306.05685)]

<p align="center">
  <img src="https://github.com/JiaxuanYou/LLM-AGI/blob/main/assets/fig/agi_stat.jpg" width="300">
</p>
<!-- ### 6.3 Potential Ways to Future AGI -->

###  6.5 Further Considerations during AGI Development

1. **Foundational Challenges in Assuring Alignment and Safety of Large Language Models**. *Usman Anwar et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2404.09932)]
2. **Best Practices and Lessons Learned on Synthetic Data for Language Models**. *Ruibo Liu et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2404.07503)]
3. **Advancing Social Intelligence in AI Agents: Technical Challenges and Open Questions**. *Leena Mathur et al.* arXiv 2024. [[paper](https://arxiv.org/abs/2404.11023)]


## 7. Case Studies

### 7.1 AI for Science Discovery and Research

1. **Highly accurate protein structure prediction with AlphaFold**. *Jumper, John* et al. Nature, 2021. [[paper](https://www.nature.com/articles/s41586-021-03819-2)]
2. **Automated Scientific Discovery: From Equation Discovery to Autonomous Discovery Systems**. *Kramer, Stefan* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.02251)]
3. **Predicting effects of noncoding variants with deep learning--based sequence model**. *Zhou, Jian* et al. Nature methods, 2015. [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4768299/]
4. **Learning to See Physics via Visual De-animation**. *Wu, Jiajun* et al. NeurIPS 2017. [[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/4c56ff4ce4aaf9573aa5dff913df997a-Paper.pdf)]
5. **Deep learning for real-time gravitational wave detection and parameter estimation: Results with Advanced LIGO data**. *George, Daniel* et al. Physics Letters B, 2018. [[paper](https://www.sciencedirect.com/science/article/pii/S0370269317310390)]
6. **Identifying quantum phase transitions with adversarial neural networks**. *Rem, Bart-Jan* et al. Nature Physics, 2019. [[paper](https://arxiv.org/pdf/1710.08382)]
7. **OpenAGI: When LLM Meets Domain Experts**. *Ge, Yingqiang* et al. NeurIPS, 2023. [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/1190733f217404edc8a7f4e15a57f301-Paper-Datasets_and_Benchmarks.pdf)]
8. **From dark matter to galaxies with convolutional networks**. *Zhang, Xinyue* et al. arXiv 2019. [[paper](https://arxiv.org/pdf/1902.05965)]
9. **Global optimization of quantum dynamics with AlphaZero deep exploration**. *Dalgaard, Mogens* et al. npj Quantum Information, 2020. [[paper](https://www.nature.com/articles/s41534-019-0241-0)]
10. **Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing**. *Shruthi Bannur* et al. CVPR, 2023. [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Bannur_Learning_To_Exploit_Temporal_Structure_for_Biomedical_Vision-Language_Processing_CVPR_2023_paper.pdf)]
11. **Mathbert: A pre-trained language model for general nlp tasks in mathematics education**. *Shen, Jia Tracy* et al. arXiv 2021. [[paper](https://arxiv.org/abs/2106.07340)]
12. **Molecular Optimization using Language Models**. *Maziarz, Krzysztof* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2210.00299)]
13. **RetroTRAE: retrosynthetic translation of atomic environments with Transformer**. *Ucak, Umit Volkan* et al. No journal, 2022.[[paper](https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/61f177d7e59d8731714a6a9d/original/retro-trae-retrosynthetic-translation-of-atomic-environments-with-transformer.pdf)]
14. **ScholarBERT: bigger is not always better**. *Hong, Zhi* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2205.11342)]
15. **Galactica: A large language model for science**. *Taylor, Ross* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2211.09085)]
16. **Formal mathematics statement curriculum learning**. *Polu, Stanislas* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2202.01344)]
17. **Proof Artifact Co-Training for Theorem Proving with Language Models**. *Jesse Michael Han* et al. ICLR 2022. [[paper](https://openreview.net/forum?id=rpxJc9j04U)]
18. **Solving quantitative reasoning problems with language models**. *Lewkowycz, Aitor* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2206.14858)]
19. **BioGPT: generative pre-trained transformer for biomedical text generation and mining**. *Luo, Renqian* et al. Briefings in bioinformatics, 2022. 
20. **ChemCrow: Augmenting large-language models with chemistry tools**. *Bran, Andres M* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2304.05376)]
21. **Autonomous chemical research with large language models**. *Boiko, Daniil A* et al. Nature, 2023. [[paper](https://www.nature.com/articles/s41586-023-06792-0)]
22. **Emergent autonomous scientific research capabilities of large language models**. *Daniil A. Boiko* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2304.05332)]
23. **MathPrompter: Mathematical Reasoning using Large Language Models**. *Imani, Shima,* et al. Presented at Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 5: Industry Track), 2023. [[paper](https://arxiv.org/pdf/2303.05398)]
24. **Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing**. *Shruthi Bannur* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2301.04558)]
25. **LLMs for Science: Usage for Code Generation and Data Analysis**. *Nejjar, Mohamed* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2311.16733)]
26. **MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning**. *Xiangru Tang* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2311.10537)]


### 7.2 Generative Visual Intelligence

1. **Deep Unsupervised Learning using Nonequilibrium Thermodynamics**. *Jascha Sohl-Dickstein* et al. ICML 2015. [[paper](https://arxiv.org/abs/1503.03585)]
2. **Generative Modeling by Estimating Gradients of the Data Distribution**. *Yang Song* et al. NeurIPS 2019. [[paper](https://arxiv.org/abs/1907.05600)]
3. **Denoising Diffusion Probabilistic Models**. *Jonathan Ho* et al. NeurIPS 2020. [[paper](https://arxiv.org/abs/2006.11239)]
4. **Score-Based Generative Modeling through Stochastic Differential Equations**. *Yang Song* et al. ICLR 2021. [[paper](https://arxiv.org/abs/2011.13456)]
5. **GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models**. *Alex Nichol* et al. ICML 2022. [[paper](https://arxiv.org/abs/2112.10741)]
6. **SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations**. *Chenlin Meng* et al. ICLR 2022. [[paper](https://arxiv.org/abs/2108.01073)]
7. **Video Diffusion Models**. *Jonathan Ho* et al. NeurIPS 2022. [[paper](https://arxiv.org/abs/2204.03458)]
8. **Hierarchical Text-Conditional Image Generation with CLIP Latents**. *Aditya Ramesh* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2204.06125)]
9. **Classifier-Free Diffusion Guidance**. *Jonathan Ho* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2207.12598)]
10. **Palette: Image-to-Image Diffusion Models**. *Chitwan Saharia* et al. SIGGRAPH 2022. [[paper](https://arxiv.org/abs/2111.05826)]
11. **High-Resolution Image Synthesis with Latent Diffusion Models**. *Robin Rombach* et al. CVPR 2022. [[paper](https://arxiv.org/abs/2112.10752)]
12. **Adding Conditional Control to Text-to-Image Diffusion Models**. *Lvmin Zhang* et al. ICCV 2023. [[paper](https://arxiv.org/abs/2302.05543)]
13. **Scalable Diffusion Models with Transformers**. *William Peebles* et al. ICCV 2023. [[paper](https://arxiv.org/abs/2212.09748)]
14. **Sequential Modeling Enables Scalable Learning for Large Vision Models**. *Yutong Bai* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.00785)]
15. **Video Generation Models as World Simulators**. *Tim Brooks* et al. OpenAI 2024. [[paper](https://openai.com/research/video-generation-models-as-world-simulators)]

### 7.3 World Models

1. **Learning to See Physics via Visual De-animation**. *Wu, Jiajun* et al. NeurIPS 2017. [[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/4c56ff4ce4aaf9573aa5dff913df997a-Paper.pdf)]
2. **Safe model-based reinforcement learning with stability guarantees**. *Berkenkamp, Felix* et al. NeurIPS, 2017. [[paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/766ebcd59621e305170616ba3d3dac32-Paper.pdf)]
3. **SimNet: Learning Simulation-Based World Models for Physical Reasoning**. *Vicol, Paul, Menapace* et al. ICLR 2022. [[paper](https://dl.acm.org/doi/pdf/10.1145/3530891)]
4. **DreamIX: DreamFusion via Iterative Spatiotemporal Mixing**. *Khalifa, Anji* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2212.04508)]
5. **General-Purpose Embodied AI Agent via Reinforcement Learning with Internet-Scale Knowledge**. *Guo, Xiaoxiao* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2212.09710)]
6. **VQGAN-CLIP: Open Domain Image Generation and Editing with Natural Language Guidance**. *Crowson, Katherine.* arXiv 2022. [[paper](https://arxiv.org/abs/2204.08583)]
7. **A Path Towards Autonomous Machine Intelligence**. *Lecun Yann* Openreview, 2022. [[paper](https://openreview.net/pdf?id=BZ5a1r-kVsf)]
8. **Language Models Meet World Models: Embodied Experiences Enhance Language Models**. *Jiannan Xiang* et al. NeurIPS 2023. [[paper](https://openreview.net/forum?id=SVBR6xBaMl)]
9. **Mastering Diverse Domains through World Models**. *Hafner, Danijar* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2301.04104)]
10. **Acquisition of Multimodal Models via Retrieval**. *Reed, Scott* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2302.02916)]
11. **Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents**. *Dohan, David* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2302.04754)]
12. **Language Models, Agent Models, and World Models: The LAW for Machine Reasoning and Planning**. *Zhiting Hu* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.05230)]
13. **Reasoning with language model is planning with world model**. *Hao, Shibo* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.14992)]
14. **MetaSim: Learning to Generate Synthetic Datasets**. *Zhang, Yuxuan* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2302.03213)]
15. **World Model on Million-Length Video And Language With RingAttention**. *Hao Liu* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2402.08268)]
16. **Genie: Generative Interactive Environments**. *Jake Bruce* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2402.15391)]


### 7.4 Decentralized LLM

1. **Petals: Collaborative Inference and Fine-tuning of Large Models**. *Alexander Borzunov* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2209.01188)]
2. **Blockchain for Deep Learning: Review and Open Challenges**. *The Economic Times.* Cluster Computing 2021. [[paper](https://link.springer.com/article/10.1007/s10586-022-03582-7)]
3. **FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU**. *Ying Sheng* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2303.06865)]
4. **Decentralized Training of Foundation Models in Heterogeneous Environments**. *Binhang Yuan* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2206.01288)]

### 7.5 AI for Coding

1. **A framework for the evaluation of code generation models**. *Ben Allal* et al. GitHub, 2023. [[code](https://github.com/bigcode-project/bigcode-evaluation-harness)]
2. **Evaluating Large Language Models Trained on Code**. *Mark Chen* et al. arxiv 2021. [[paper](https://arxiv.org/abs/2107.03374)]
3. **Program Synthesis with Large Language Models**. *Jacob Austin* et al. arXiv 2021. [[paper](https://arxiv.org/abs/2108.07732)]
4. **Competition-level code generation with AlphaCode**. *Yujia Li* et al. Science, 2022. [[paper](https://arxiv.org/abs/2203.07814)]
5. **Efficient Training of Language Models to Fill in the Middle**. *Mohammad Bavarian* et al. arXiv 2022. [[paper](https://arxiv.org/abs/2207.14255)]
6. **SantaCoder: don't reach for the stars!**. *Loubna Ben Allal* et al. Mind, 2023. [[paper](https://arxiv.org/abs/2301.03988)]
7. **StarCoder: may the source be with you!**. *Raymond Li* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2305.06161)]
8. **Large Language Models for Compiler Optimization**. *Chris Cummins* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2309.07062)]
9. **Textbooks Are All You Need**. *Suriya Gunasekar* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.11644)]
10. **InterCode: Standardizing and Benchmarking Interactive Coding with Execution Feedback**. *John Yang* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2306.14898)]
11. **Reinforcement Learning from Automatic Feedback for High-Quality Unit Test Generation**. *Benjamin Steenhoek* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2310.02368)]
12. **InCoder: A Generative Model for Code Infilling and Synthesis**. *Daniel Fried* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2204.05999)]
13. **Refining Decompiled C Code with Large Language Models**. *Wai Kin Wong* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2310.06530)]
14. **SWE-bench: Can Language Models Resolve Real-World GitHub Issues?**. *Carlos E* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2310.06770)]
15. **EvoPrompting: Language Models for Code-Level Neural Architecture Search**. *Angelica Chen* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2302.14838)]
16. **Can Large Language Models Identify And Reason About Security Vulnerabilities? Not Yet**. *Saad Ullah* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2312.12575)]
17. **SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code**. *Ziniu Hu* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2403.01248)]
18. **DebugBench: Evaluating Debugging Capability of Large Language Models**. *Runchu Tian* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2401.04621)]
19. **AI-assisted Code Authoring at Scale: Fine-tuning, deploying, and mixed methods evaluation**. *Vijayaraghavan Murali* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2305.12050)]
20. **Code Llama: Open Foundation Models for Code**. *Baptiste Rozière* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2308.12950)]
21. **Can llm already serve as a database interface? a big bench for large-scale database grounded text-to-sqls**. *Jinyang Li* et al. NeurIPS 2024.
22. **OOP: Object-Oriented Programming Evaluation Benchmark for Large Language Models**. *Shuai Wang* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2401.06628)]


### 7.6 AI for Robotics in Real World Applications

1. **The Second Machine Age: Work, Progress, and Prosperity in a Time of Brilliant Technologies**. *Brynjolfsson, Erik* W. W. Norton \& Company, 2014.
2. **Rise of the Robots: Technology and the Threat of a Jobless Future**. *Ford, Martin.* Basic Books, 2015.
3. **Lessons from the amazon picking challenge: Four aspects of building robotic systems.**. *Eppner, Clemens, H\"o.* Presented at Robotics: science and systems, 2016. [[paper](https://m.roboticsproceedings.org/rss12/p36.pdf)]
4. **Life 3.0: Being Human in the Age of Artificial Intelligence**. *Tegmark, Max.* Knopf, 2017.
5. **A Language Agent for Autonomous Driving**. *Jiageng Mao* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2311.10813)]
6. **GPT-4V(ision) for Robotics: Multimodal Task Planning from Human Demonstration**. *Naoki Wake* et al. arXiv 2023. [[paper](https://arxiv.org/abs/2311.12015)]
7. **NOIR: Neural Signal Operated Intelligent Robots for Everyday Activities**. *Ruohan Zhang* et al. CoRL 2023. [[paper](https://openreview.net/forum?id=eyykI3UIHa)]
8. **GPT-Driver: Learning to Drive with GPT**. *Jiageng Mao* arXiv 2023. [[paper](https://arxiv.org/abs/2310.01415)]
9. **Yell At Your Robot: Improving On-the-Fly from Language Corrections**. *Lucy Xiaoyang Shi* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2403.12910)]
10. **DiLu: A Knowledge-Driven Approach to Autonomous Driving with Large Language Models**. *Licheng Wen* et al. ICLR 2024. [[paper](https://openreview.net/forum?id=OqTMUPuLuC)]
11. **AgentsCoDriver: Large Language Model Empowered Collaborative Driving with Lifelong Learning**. *Senkang Hu* et al. arXiv 2024. [[paper](https://arxiv.org/abs/2404.06345)]


### 7.7 Human-AI Collaboration

1. **CoAuthor: Designing a Human-AI Collaborative Writing Dataset for Exploring Language Model Capabilities**.
   *Mina Lee* et al. CHI 2022. [[paper](http://arxiv.org/abs/2201.06796)]
2. **A Design Space for Intelligent and Interactive Writing Assistants**.
   *Mina Lee* et al. CHI 2024. [[paper](http://arxiv.org/abs/2403.14117)]
3. **CreativeConnect: Supporting Reference Recombination for Graphic Design Ideation with Generative AI**.
   *DaEun Choi* et al. CHI 2024. [[paper](http://arxiv.org/abs/2312.11949)]
4. **I Lead, You Help but Only with Enough Details: Understanding User Experience of Co-Creation with Artificial Intelligence**.
   *Changhoon Oh* et al. CHI 2018. [[paper](https://dl.acm.org/doi/10.1145/3173574.3174223)]
5. **CodeAid: Evaluating a Classroom Deployment of an LLM-based Programming Assistant that Balances Student and Educator Needs**.
   *Majeed Kazemitabaar* et al. CHI 2024. [[paper](http://arxiv.org/abs/2401.11314)]
6. **AI-Augmented Brainwriting: Investigating the use of LLMs in group ideation**.
   *Orit Shaer* et al. CHI 2024. [[paper](http://arxiv.org/abs/2402.14978)]
7. **Is the Most Accurate AI the Best Teammate? Optimizing AI for Teamwork**.
   *Gagan Bansal* et al. AAAI 2021. [[paper](http://arxiv.org/abs/2004.13102)]
8. **Updates in Human-AI Teams: Understanding and Addressing the Performance/Compatibility Tradeoff**.
   *Gagan Bansal* et al. AAAI 2019. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/4087)]
9. **Harnessing Biomedical Literature to Calibrate Clinicians’ Trust in AI Decision Support Systems**.
   *Qian Yang* et al. CHI 2023. [[paper](https://dl.acm.org/doi/10.1145/3544548.3581393)]
10. **AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts**.
    *Tongshuang Wu* et al. CHI 2022. [[paper](https://dl.acm.org/doi/10.1145/3491102.3517582)]
11. **Designing LLM Chains by Adapting Techniques from Crowdsourcing Workflows**.
    *Madeleine Grunde-McLaughlin* et al. arXiv, 2023. [[paper](http://arxiv.org/abs/2312.11681)]
12. **Why Johnny Can’t Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompts**.
    *J.D. Zamfirescu-Pereira* et al. CHI 2023. [[paper](https://dl.acm.org/doi/10.1145/3544548.3581388)]
13. **Designing Theory-Driven User-Centric Explainable AI**.
    *Danding Wang* et al. CHI 2019. [[paper](https://dl.acm.org/doi/10.1145/3290605.3300831)]
14. **Do People Engage Cognitively with AI? Impact of AI Assistance on Incidental Learning**.
    *Krzysztof Z. Gajos* et al. IUI 2022. [[paper](https://dl.acm.org/doi/10.1145/3490099.3511138)]



<!-- ### Agent & Tool:

- [Tool learning with foundation models](https://arxiv.org/pdf/2304.08354.pdf)
- [A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/pdf/2308.11432.pdf)
- [The Rise and Potential of Large Language Model Based Agents: A Survey](https://arxiv.org/pdf/2309.07864.pdf)
- [Cognitive Architectures for Language Agents](https://arxiv.org/pdf/2309.02427.pdf)

### (Multi-Modal) LLM / Foundation Model:

#### LLM

- [A Survey of Large Language Models](https://arxiv.org/pdf/2303.18223.pdf)
- [A Survey on In-context Learning](https://arxiv.org/pdf/2301.00234.pdf)
- [Harnessing the Power of LLMs in Practice: A Survey on ChatGPT and Beyond](https://arxiv.org/pdf/2304.13712.pdf)

#### Multi-Modal LLM

- [A Survey on Multimodal Large Language Models](https://arxiv.org/pdf/2306.13549.pdf)

#### General Foundation Model

- [On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258.pdf)
- [A Comprehensive Survey on Pretrained Foundation Models: A History from BERT to ChatGPT](https://arxiv.org/pdf/2302.09419.pdf)

### Embodied AI:

#### AGI

- [One Small Step for Generative AI, One Giant Leap for AGI: A Complete Survey on ChatGPT in AIGC Era](https://arxiv.org/pdf/2304.06488.pdf)
- [Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/pdf/2303.12712.pdf)
- [Towards AGI in Computer Vision: Lessons Learned from GPT and Large Language Models](https://arxiv.org/pdf/2306.08641.pdf)
- [A Comprehensive Survey of AI-Generated Content (AIGC): A History of Generative AI from GAN to ChatGPT](https://arxiv.org/pdf/2303.04226.pdf)

### Github:

- [LLM-Agent-Paper-List](https://github.com/WooooDyy/LLM-Agent-Paper-List) (Agent)
- [Awesome-AI-Agents](https://github.com/e2b-dev/awesome-ai-agents) (Agent)
- [Awesome-Multimodal-Large-Language-Models](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) (Multi-modal LLM) -->


## 🎉 Contribution

### Contributing to this paper list

⭐ **Join us in improving this repository!** Please contribute if you know of any important work we've missed. Your efforts are highly valued!

### Contributors

<a href="https://github.com/ulab-uiuc/AGI-survey/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ulab-uiuc/AGI-survey"/>
</a>

---

<p align="center">
<a href="https://star-history.com/#Significant-Gravitas/AutoGPT">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ulab-uiuc/AGI-survey&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ulab-uiuc/AGI-survey&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Significant-Gravitas/AutoGPT&type=Date" />
  </picture>
</a>
</p>

