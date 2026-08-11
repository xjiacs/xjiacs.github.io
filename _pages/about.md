---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.publication-list { margin-top: 1rem; }
.publication-item {
  display: flex;
  gap: 1.15rem;
  align-items: flex-start;
  margin: 0 0 1.55rem 0;
  padding: 0 0 1.35rem 0;
  border-bottom: 1px solid var(--global-border-color);
}
.publication-thumb {
  flex: 0 0 235px;
  width: 235px;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.publication-thumb img {
  display: block;
  width: 100%;
  height: auto;
  max-height: 165px;
  object-fit: contain;
  object-position: center top;
  border-radius: 4px;
  border: 0;
  background: #fff;
}
.publication-content { flex: 1 1 auto; min-width: 0; }
.publication-title {
  margin: 0 0 0.28rem 0 !important;
  font-size: 1.02em !important;
  line-height: 1.35;
}
.publication-authors, .publication-venue, .publication-links, .publication-excerpt {
  margin: 0.18rem 0 !important;
}
.publication-links a { font-weight: 600; }
@media (max-width: 720px) {
  .publication-item { display: block; }
  .publication-thumb { width: 100%; max-width: 360px; margin-bottom: 0.75rem; }
  .publication-thumb img { width: 100%; height: auto; max-height: none; object-fit: contain; }
}
</style>

Hi! I am **Shijia Xu**, a Master's candidate in **Control Science and Engineering at [Chongqing University](https://www.cqu.edu.cn/)**, advised by Prof. **Zhou Wu**. I am currently a **Visiting Research Student in Computer Science at [Queen Mary University of London](https://www.qmul.ac.uk/)**, hosted by Prof. **Ahmed M. A. Sayed**.

My research interests lie in **trustworthy large language models**, **retrieval-augmented generation (RAG)**, **reasoning**, and **explainable NLP**. I am particularly interested in building language-model systems that can retrieve useful evidence, verify intermediate reasoning, and remain reliable under practical constraints.

Please feel free to contact me at **shijiaxu@stu.cqu.edu.cn** if you are interested in my research or potential collaboration.

# News

- **Jun. 2026** — Started my visiting research at **Queen Mary University of London**, focusing on NLP and RAG for reliable and reasoning-capable large language models.
- **May 2026** — Our paper **LLM-Guided Secure Federated Visual Prompts with Deep Unfolding for MRI Reconstruction** was accepted to **ICMR 2026**.
- **Apr. 2026** — Two first-author papers, **Self-Correcting RAG** and **RCBSF**, were accepted to **Findings of ACL 2026**.

# Research interests

- **Trustworthy LLMs:** hallucination reduction, faithfulness, verification, and robust reasoning.
- **Retrieval-Augmented Generation:** context selection, evidence grounding, and budget-aware retrieval.
- **Reasoning and Planning:** mechanistic analysis of autoregressive reasoning and long-horizon planning.
- **Efficient / Federated Adaptation:** resource-aware fine-tuning and privacy-preserving learning.

# Selected publications

<div class="publication-list">

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/self-correcting-rag.png' | relative_url }}" alt="Self-Correcting RAG overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">Self-Correcting RAG: Enhancing Faithfulness via MMKP Context Selection and NLI-Guided MCTS</h3>
    <p class="publication-authors"><strong>Shijia Xu</strong>, Zhou Wu, Xiaolong Jia, Yu Wang, Kai Liu, April Xiaowen Dong.</p>
    <p class="publication-venue"><em>Findings of ACL 2026</em>.</p>
    <p class="publication-links">[<a href="https://aclanthology.org/2026.findings-acl.1052/" target="_blank" rel="noopener">Paper</a>] [<a href="https://github.com/xjiacs/Self-Correcting-RAG" target="_blank" rel="noopener">Code</a>]</p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/rcbsf.png' | relative_url }}" alt="RCBSF overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">RCBSF: A Multi-Agent Framework for Automated Contract Revision via Stackelberg Game</h3>
    <p class="publication-authors"><strong>Shijia Xu</strong>, Yu Wang, Xiaolong Jia, Zhou Wu, Kai Liu, April Xiaowen Dong.</p>
    <p class="publication-venue"><em>Findings of ACL 2026</em>.</p>
    <p class="publication-links">[<a href="https://aclanthology.org/2026.findings-acl.935/" target="_blank" rel="noopener">Paper</a>] [<a href="https://github.com/xjiacs/RCBSF" target="_blank" rel="noopener">Code</a>]</p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/llm-guided-secure-federated-visual-prompts.png' | relative_url }}" alt="Federated MRI reconstruction overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">LLM-Guided Secure Federated Visual Prompts with Deep Unfolding for MRI Reconstruction</h3>
    <p class="publication-authors">Di Xiao, Yuhan Gou, Yu Ren, <strong>Shijia Xu</strong>, Yue Zhang.</p>
    <p class="publication-venue"><em>ICMR 2026</em>.</p>
    <p class="publication-links">[<a href="https://dl.acm.org/doi/full/10.1145/3805622.3810571" target="_blank" rel="noopener">Paper</a>]</p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/state-copying-crowds-out-reasoning.png' | relative_url }}" alt="Delta planning overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">State Copying Crowds Out Reasoning: Mechanistic Evidence for Delta Planning in Autoregressive Models</h3>
    <p class="publication-authors"><strong>Shijia Xu</strong>, Wang Xi.</p>
    <p class="publication-venue"><em>NeurIPS 2026 (In Submission)</em>.</p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/resource-aware-federated-lora.png' | relative_url }}" alt="Resource-aware federated LoRA overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">Resource-Aware Federated LoRA Fine-Tuning for Heterogeneous Environments</h3>
    <p class="publication-authors">Xiaolong Jia, Ahmed M. Abdelmoniem, <strong>Shijia Xu</strong>, Gaoyang Liu, Chen Wang.</p>
    <p class="publication-venue"><em>NeurIPS 2026 (In Submission)</em>.</p>
  </div>
</div>

</div>

[See all publications](/publications/)

# Education

- **[Queen Mary University of London](https://www.qmul.ac.uk/)**, London, United Kingdom  
  *Visiting Research Student in Computer Science*, Jun. 2026 – Dec. 2026.  
  Host Supervisor: Prof. Ahmed M. A. Sayed. Research focus: NLP and RAG for reliable and reasoning-capable large language models. Supported by the Chongqing University Joint Training Program for Master's Students.

- **[Chongqing University](https://www.cqu.edu.cn/)**, Chongqing, China  
  *M.E. Candidate in Control Science and Engineering*, Sep. 2024 – Jul. 2027.  
  GPA: **4.09/5.00**, Rank: **2/74**. Advisor: Prof. Zhou Wu. Research interests: trustworthy LLMs, RAG, and explainable NLP.

- **[Shandong University of Science and Technology](https://www.sdust.edu.cn/)**, Qingdao, China  
  *B.E. in Automation*, Sep. 2020 – Jul. 2024.  
  GPA: **4.03/5.00**, Rank: **3/163**.

# Selected honors & awards

- Chongqing University First Prize Master's Academic Scholarship, **2024 & 2025**
- Chongqing University Merit Student, **2025**
- Outstanding Graduate of Shandong Province, **2024**
- Shandong Provincial Government Scholarship, **2022**
- Sun Yueqi Outstanding Student Award, **2022**
- National Endeavor Scholarship (Top 3%), **2021**
- 15th MathorCup Math Application Challenge (Postgraduate), **National Second Prize, 2025**
- RAICOM Developer Robot Competition, **National Second Prize, 2023**
- National Undergraduate Robotics Competition (ROBOCON), **National Third Prize, 2022 & 2023**
