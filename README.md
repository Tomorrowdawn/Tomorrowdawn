[![My GitHub stats](https://github-readme-stats.vercel.app/api?username=Tomorrowdawn)](https://github.com/anuraghazra/github-readme-stats)

<div align="center">
  
  ![](https://komarev.com/ghpvc/?username=Tomorrowdawn) ![GitHub User's stars](https://img.shields.io/github/stars/Tomorrowdawn) 
  
</div>

## Hi there 👋

<img align="right" width="200" src="https://hips.hearstapps.com/hmg-prod/images/euripides-9289335-1-402.jpg" alt="Euripides">

**Torrowdawn**, or *Chenxia Tang* (唐晨夏) here.

I was born in 2003, and I'm currently a Master student in USTC. My research focuses on post-training and inference optimization for large language models. I agree with Euripides: *The language of truth is simple*.

My favorite Top-2 English words are *Meditation* and *Philosophy*. I treat meditation as the best medicine for life, and I also deeply love wisdom. 

### 💻 Skills

I am highly proficient in 

- Python ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- C++ ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

which you can verify from my repos. I also wrote `verilog`, and planning to learn dart to develop some android apps.

---

### 🔬 Research Focus

**Primary Research Area:**
- Post-training & Inference Optimization for Large Language Models
- Token Sampling Methods and Generation Quality  
- High-speed Inference and Performance Optimization

**Previous Experience:**
- Reinforcement Learning, Recommendation Systems (brief exploration)

My research on large language models is particularly in-depth. I have extensive experience with RLHF (GPT-2 scale), fine-tuning (LLaMA2, 3), and have measured execution times of almost all operators in LLaMA. I am quite familiar with the bottlenecks of LLaMA, especially for single-GPU execution on the A6000.

---

### 🎓 Education

- Bachelor's Degree

<p align="right">
<em>University of Science and Technology of China (USTC) <br> Special Class for the Gifted Young (enrolled at age 16) <br> 2019 -2023</em>
</p>

- Master's Degree (Current)

<p align="right">
<em>University of Science and Technology of China (USTC) <br> School of Computer Science and Technology <br> 2023 - </em>
</p>

I served as a teaching assistant（TA）for *Algebra*，in 2023 fall.

### 📄 Papers

#### 1. Top-nσ: Eliminating Noise in Logit Space for Robust Token Sampling of LLM
**Authors:** Chenxia Tang, Jianchun Liu, Hongli Xu, Liusheng Huang  
**Conference:** ACL 2025 (Long Papers) | **Pages:** 10758-10774 | **Venue:** Vienna, Austria  

**TL;DR:** Proposed top-nσ, a novel sampling method that eliminates noise directly in logit space. Key findings: (1) pre-softmax logits show clear separation between informative tokens and noise, (2) proved mathematical equivalence of min-p and top-(1-p). Achieves temperature-invariant token selection while preserving diversity, outperforming existing methods especially at high temperatures.

**Links:** [ACL Anthology](https://aclanthology.org/2025.acl-long.528/) | [PDF](https://aclanthology.org/2025.acl-long.528.pdf)

#### 2. Heterogeneous Learning Rate Scheduling for Neural Architecture Search on Long-Tailed Datasets
**Authors:** Chenxia Tang | **Preprint:** arXiv:2406.07028 | **Submitted:** June 2024  

**TL;DR:** Proposed adaptive learning rate scheduling for DARTS on long-tailed datasets. Traditional re-sampling/re-weighting techniques cause performance degradation with DARTS. Our method specifically optimizes architecture parameters for imbalanced class distributions.

**Links:** [arXiv](https://arxiv.org/abs/2406.07028) | [PDF](https://arxiv.org/pdf/2406.07028.pdf)

### 🚀 Projects

#### 1. GITCGSimulator - Genius Invokation TCG Simulator
**Repository:** [GitHub](https://github.com/Tomorrowdawn/GITCGSimulator) |  **Language:** Python/C++

**TL;DR:** A comprehensive simulator for Genshin Impact's Genius Invokation TCG, designed specifically for AI training and reinforcement learning research.

**Key Contributions:**
- **Game Engine Development:** Built a complete TCG simulation engine with event-driven architecture supporting complex card interactions, elemental reactions, and turn-based gameplay mechanics
- **AI Framework:** Implemented MCTS (Monte Carlo Tree Search) algorithms and AlphaBeta search for intelligent gameplay, achieving competitive performance against human players
- **Modular Design:** Created extensible card system with string-based reflection, supporting custom card implementations and easy game state serialization

#### 2. VLMWalk - Vision-Language Model Research
**Repository:** [GitHub](https://github.com/Tomorrowdawn/VLMWalk) | **Language:** Python

**TL;DR:** Self-study project focused on advancing vision-language model capabilities with modern frameworks.

#### 3. seqattn - Sequence Attention Mechanisms
**Repository:** [GitHub](https://github.com/Tomorrowdawn/seqattn) | **Language:** Python

**TL;DR:** A light-weight FlashInfer wrapper that simplifies memory management and enables easy implementation of custom sparse attention operations.

**Key Contributions:**
- **Memory Management:** Developed a streamlined wrapper around FlashInfer that significantly simplifies memory allocation and deallocation for attention operations
- **Custom Sparse Attention:** Created an intuitive interface for implementing custom sparse attention patterns and operations
- **Performance Optimization:** Leveraged FlashInfer's optimized kernels while providing a more accessible API for research and development
- **Research Framework:** Built a flexible foundation for experimenting with various attention mechanisms and sparse patterns

---

### 🌟 Open Source Contributions

My research on Top-nσ sampling has been adopted by several open-source projects:
- **llama.cpp:** [Pull Request #11223](https://github.com/ggml-org/llama.cpp/pull/11223)
- **SillyTavern:** [Pull Request #3094](https://github.com/SillyTavern/SillyTavern/pull/3094)
