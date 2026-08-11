---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi! I am **Shijia Xu**, a Master's candidate in **Control Science and Engineering at [Chongqing University](https://www.cqu.edu.cn/)**, advised by Prof. **Zhou Wu**. I am currently a **Visiting Research Student in Computer Science at [Queen Mary University of London](https://www.qmul.ac.uk/)**, hosted by Prof. **Ahmed M. A. Sayed**.

My research interests lie in **trustworthy large language models**, **retrieval-augmented generation (RAG)**, **reasoning**, and **explainable NLP**. I am particularly interested in building language-model systems that can retrieve useful evidence, verify intermediate reasoning, and remain reliable under practical constraints.

Please feel free to contact me at **shijiaxu@stu.cqu.edu.cn** if you are interested in my research or potential collaboration.

# News

- **Jun. 2026** — Started my visiting research at **Queen Mary University of London**, focusing on NLP and RAG for reliable and reasoning-capable large language models.
- **2026** — Two first-author papers, **Self-Correcting RAG** and **RCBSF**, were accepted to **Findings of ACL 2026**.
- **2026** — Our work **LLM-Guided Secure Federated Visual Prompts with Deep Unfolding for MRI Reconstruction** was accepted to **ICMR 2026**.

# Research interests

- **Trustworthy LLMs:** hallucination reduction, faithfulness, verification, and robust reasoning.
- **Retrieval-Augmented Generation:** context selection, evidence grounding, and budget-aware retrieval.
- **Reasoning and Planning:** mechanistic analysis of autoregressive reasoning and long-horizon planning.
- **Efficient / Federated Adaptation:** resource-aware fine-tuning and privacy-preserving learning.

# Selected publications

{% assign pubs = site.publications | sort: "order" %}
{% for pub in pubs limit:5 %}
**{{ pub.title }}**  
{{ pub.citation }}  
{% if pub.paperurl %}[Paper]({{ pub.paperurl }}){% endif %}

{% endfor %}

[See all publications →](/publications/)

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
