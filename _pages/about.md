---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ===== Homepage polish ===== */
:root {
  --pub-card-radius: 12px;
  --pub-card-pad: 1rem;
}

/* Section rhythm */
.page__content h1 {
  margin-top: 2.1rem;
  margin-bottom: 0.9rem;
  padding-bottom: 0.35rem;
  border-bottom: 1px solid var(--global-border-color);
  letter-spacing: -0.01em;
}

/* News / research / awards lists */
#news + ul,
#research-interests + ul,
#selected-honors--awards + ul {
  margin-top: 0.65rem;
}

#news + ul li,
#research-interests + ul li,
#selected-honors--awards + ul li {
  margin-bottom: 0.42rem;
  line-height: 1.6;
}

/* ===== Publication cards ===== */
.publication-list {
  margin-top: 1.05rem;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.publication-item {
  display: flex;
  gap: 1.15rem;
  align-items: center;
  margin: 0;
  padding: var(--pub-card-pad);
  border: 1px solid var(--global-border-color);
  border-radius: var(--pub-card-radius);
  background: var(--global-bg-color);
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.035);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.publication-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 7px 20px rgba(0, 0, 0, 0.08);
  border-color: var(--global-link-color);
}

.publication-thumb {
  flex: 0 0 220px;
  width: 220px;
  height: 138px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  border: 1px solid var(--global-border-color);
  border-radius: 9px;
  background: #fff;
}

.publication-thumb img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center;
  padding: 3px;
  box-sizing: border-box;
}

.publication-content {
  flex: 1 1 auto;
  min-width: 0;
}

.publication-title {
  margin: 0 0 0.34rem 0 !important;
  font-size: 1.03em !important;
  line-height: 1.38;
  font-weight: 700;
}

.publication-authors,
.publication-venue,
.publication-links,
.publication-excerpt {
  margin: 0.22rem 0 !important;
  line-height: 1.5;
}

.publication-authors {
  font-size: 0.94em;
}

.publication-venue {
  margin-top: 0.34rem !important;
}

.venue-tag {
  display: inline-block;
  padding: 0.16rem 0.52rem;
  border-radius: 999px;
  border: 1px solid var(--global-border-color);
  background: rgba(127, 127, 127, 0.08);
  font-size: 0.84em;
  font-style: normal;
  font-weight: 700;
  line-height: 1.45;
}

.venue-tag.submission {
  font-weight: 600;
  opacity: 0.86;
}

.publication-links {
  margin-top: 0.48rem !important;
}

.publication-links a {
  display: inline-block;
  margin: 0.08rem 0.32rem 0.08rem 0;
  padding: 0.18rem 0.5rem;
  border: 1px solid var(--global-border-color);
  border-radius: 6px;
  font-size: 0.86em;
  font-weight: 700;
  text-decoration: none !important;
  transition: border-color 0.15s ease, background 0.15s ease;
}

.publication-links a:hover {
  border-color: var(--global-link-color);
  background: rgba(127, 127, 127, 0.08);
}

.all-publications-link {
  margin-top: 0.9rem;
  text-align: right;
}

.all-publications-link a {
  font-weight: 700;
  text-decoration: none;
}

@media (max-width: 820px) {
  .publication-item {
    align-items: flex-start;
  }

  .publication-thumb {
    flex-basis: 190px;
    width: 190px;
    height: 120px;
  }
}

@media (max-width: 650px) {
  .publication-item {
    display: block;
    padding: 0.85rem;
  }

  .publication-thumb {
    width: 100%;
    height: auto;
    aspect-ratio: 16 / 9;
    margin-bottom: 0.75rem;
  }

  .publication-title {
    font-size: 1em !important;
  }

  .all-publications-link {
    text-align: left;
  }
}
</style>

Hi! I am **Shijia Xu**, a Master's candidate in **Control Science and Engineering at [Chongqing University](https://www.cqu.edu.cn/)**, advised by Prof. **[Zhou Wu](https://accu.cqu.edu.cn/info/1375/9163.htm)**. I am currently a **Visiting Research Student in Computer Science at [Queen Mary University of London](https://www.qmul.ac.uk/)**, hosted by Prof. **[Ahmed M. A. Sayed](https://www.qmul.ac.uk/eecs/people/profiles/sayedahmed.html)**.

My research interests lie in **trustworthy large language models**, **retrieval-augmented generation (RAG)**, **reasoning**, and **explainable NLP**. I am particularly interested in building language-model systems that can retrieve useful evidence, verify intermediate reasoning, and remain reliable under practical constraints.

Please feel free to contact me at **shijiaxu@stu.cqu.edu.cn** if you are interested in my research or potential collaboration.

# News

- **Sep. 2026** — As a **co-first author**, our paper **State Copying Crowds Out Reasoning: Mechanistic Evidence for Delta Planning in Autoregressive Models** was accepted to **NeurIPS 2026**.
- **Sep. 2026** — Our paper **[The Cost of Compression: A Rate-Distortion Limit on Factual Hallucination](https://arxiv.org/abs/2609.12111)** was accepted to **AACL 2026**.
- **Jun. 2026** — Started my visiting research at **Queen Mary University of London**, focusing on NLP and RAG for reliable and reasoning-capable large language models.
- **May 2026** — Our paper **LLM-Guided Secure Federated Visual Prompts with Deep Unfolding for MRI Reconstruction** was accepted to **ICMR 2026**.
- **Apr. 2026** — Two first-author papers, **Self-Correcting RAG** and **RCBSF**, were accepted to **ACL 2026**.

# Research interests

- **Trustworthy LLMs:** hallucination reduction, faithfulness, verification, and robust reasoning.
- **Retrieval-Augmented Generation:** context selection, evidence grounding, and budget-aware retrieval.
- **Reasoning and Planning:** mechanistic analysis of autoregressive reasoning and long-horizon planning.
- **Learning-Theoretic Reasoning:** analyzing representation, generalization, and optimization in structured reasoning.

# Selected publications

<div class="publication-list">
<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/self-correcting-rag.png' | relative_url }}" alt="Self-Correcting RAG overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">Self-Correcting RAG: Enhancing Faithfulness via MMKP Context Selection and NLI-Guided MCTS</h3>
    <p class="publication-authors"><strong>Shijia Xu</strong>, Zhou Wu, Xiaolong Jia, Yu Wang, Kai Liu, April Xiaowen Dong.</p>
    <p class="publication-venue"><span class="venue-tag">ACL 2026</span></p>
    <p class="publication-links"><a href="https://aclanthology.org/2026.findings-acl.1052/" target="_blank" rel="noopener">Paper ↗</a><a href="https://github.com/xjiacs/Self-Correcting-RAG" target="_blank" rel="noopener">Code ↗</a></p>
  </div>
</div>
<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/rcbsf.png' | relative_url }}" alt="RCBSF overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">RCBSF: A Multi-Agent Framework for Automated Contract Revision via Stackelberg Game</h3>
    <p class="publication-authors"><strong>Shijia Xu</strong>, Yu Wang, Xiaolong Jia, Zhou Wu, Kai Liu, April Xiaowen Dong.</p>
    <p class="publication-venue"><span class="venue-tag">ACL 2026</span></p>
    <p class="publication-links"><a href="https://aclanthology.org/2026.findings-acl.935/" target="_blank" rel="noopener">Paper ↗</a><a href="https://github.com/xjiacs/RCBSF" target="_blank" rel="noopener">Code ↗</a></p>
  </div>
</div>
<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/state-copying-crowds-out-reasoning.png' | relative_url }}" alt="State Copying Crowds Out Reasoning overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">State Copying Crowds Out Reasoning: Mechanistic Evidence for Delta Planning in Autoregressive Models</h3>
    <p class="publication-authors">Wang Xi (co-first author), <strong>Shijia Xu</strong> (co-first author).</p>
    <p class="publication-venue"><span class="venue-tag">NeurIPS 2026</span></p>
  </div>
</div>



<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/cost-of-compression.png' | relative_url }}" alt="The Cost of Compression overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">The Cost of Compression: A Rate-Distortion Limit on Factual Hallucination</h3>
    <p class="publication-authors">Wang Xi (co-first author), <strong>Shijia Xu</strong> (co-first author), Rongfeng Guo.</p>
    <p class="publication-venue"><span class="venue-tag">AACL 2026</span></p>
    <p class="publication-links"><a href="https://arxiv.org/abs/2609.12111" target="_blank" rel="noopener">Paper ↗</a></p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/llm-guided-secure-federated-visual-prompts.png' | relative_url }}" alt="Federated MRI reconstruction overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">LLM-Guided Secure Federated Visual Prompts with Deep Unfolding for MRI Reconstruction</h3>
    <p class="publication-authors">Di Xiao, Yuhan Gou, Yu Ren, <strong>Shijia Xu</strong>, Yue Zhang.</p>
    <p class="publication-venue"><span class="venue-tag">ICMR 2026</span></p>
    <p class="publication-links"><a href="https://dl.acm.org/doi/full/10.1145/3805622.3810571" target="_blank" rel="noopener">Paper ↗</a></p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/skilldes_frame.png' | relative_url }}" alt="SkillDES overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">SkillDES: Dependency- and Evidence-Aware Skill-Set Selection for Composite Tasks</h3>
    <p class="publication-authors"><strong>Shijia Xu</strong>, Wang Xi, Wenyuan Ning, Delvin Ce Zhang, Jingping Liu, Zibin Zheng.</p>
    <p class="publication-venue"><span class="venue-tag submission">ICLR 2027 · In Submission</span></p>
  </div>
</div>

<div class="publication-item">
  <div class="publication-thumb"><img src="{{ '/images/publications/memsif.png' | relative_url }}" alt="MemSIF overview"></div>
  <div class="publication-content">
    <h3 class="publication-title">MemSIF: From Structured Interactions to Dual-Track Fact Memory for LLM Agents</h3>
    <p class="publication-authors">Yufei Luo, <strong>Shijia Xu</strong>, Guangyuan Dong, Xiucheng Xu.</p>
    <p class="publication-venue"><span class="venue-tag submission">AAAI 2027 · In Submission</span></p>
  </div>
</div>

</div>

<div class="all-publications-link"><a href="/publications/">See all publications →</a></div>

# Education

- **[Queen Mary University of London](https://www.qmul.ac.uk/)**, London, United Kingdom  
  *Visiting Research Student in Computer Science*, Jun. 2026 – Dec. 2026.  
  Host Supervisor: Prof. [Ahmed M. A. Sayed](https://www.qmul.ac.uk/eecs/people/profiles/sayedahmed.html). Research focus: NLP and RAG for reliable and reasoning-capable large language models. Supported by the Chongqing University Joint Training Program for Master's Students.

- **[Chongqing University](https://www.cqu.edu.cn/)**, Chongqing, China  
  *M.E. Candidate in Control Science and Engineering*, Sep. 2024 – Jul. 2027.  
  Advisor: Prof. [Zhou Wu](https://accu.cqu.edu.cn/info/1375/9163.htm). Research interests: trustworthy LLMs, RAG, and explainable NLP.

- **[Shandong University of Science and Technology](https://www.sdust.edu.cn/)**, Qingdao, China  
  *B.E. in Automation*, Sep. 2020 – Jul. 2024.  

# Selected Honors & Awards

- Chongqing University First Prize Master's Academic Scholarship, **2024 & 2025**
- Chongqing University Merit Student, **2025**
- Outstanding Graduate of Shandong Province, **2024**
- Shandong Provincial Government Scholarship, **2022**
- Sun Yueqi Outstanding Student Award, **2022**
- National Endeavor Scholarship (Top 3%), **2021**
- 15th MathorCup Math Application Challenge (Postgraduate), **National Second Prize, 2025**
- RAICOM Developer Robot Competition, **National Second Prize, 2023**
- National Undergraduate Robotics Competition (ROBOCON), **National Third Prize, 2022 & 2023**
