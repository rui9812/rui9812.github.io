---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Montserrat:wght@600;700&display=swap');

  /* 全局正文字体与行高优化 */
  body, p, li, a {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    line-height: 1.7;
    color: #374151; 
  }

  /* 标题字体与间距优化 */
  h1, h2, h3, h4, h5, h6 {
    font-family: 'Montserrat', sans-serif !important;
    font-weight: 700;
    color: #111827;
    margin-top: 1.6em;
    margin-bottom: 0.6em;
  }

  b, strong {
    font-weight: 600;
    color: #111827;
  }

  /* --- 论文列表专属美化 --- */
  .pub-list li {
    margin-bottom: 1.2em; /* 拉开每篇论文的间距 */
  }
  
  /* 将斜体的会议名称渲染为高亮标签 */
  .pub-list em {
    font-style: normal;
    font-weight: 600;
    color: #0284c7; /* 深蓝色 */
    background-color: #f0f9ff; /* 浅蓝背景 */
    padding: 2px 8px;
    border-radius: 6px;
    font-size: 0.9em;
    margin-right: 5px;
  }

  /* 将 Paper/Code 链接渲染为现代按钮 */
  .pub-list a {
    display: inline-block;
    background-color: #f3f4f6;
    color: #374151 !important;
    padding: 2px 10px;
    border-radius: 6px;
    font-size: 0.85em;
    font-weight: 500;
    text-decoration: none !important;
    border: 1px solid #e5e7eb;
    transition: all 0.2s ease-in-out;
  }
  
  .pub-list a:hover {
    background-color: #e5e7eb;
    transform: translateY(-1px);
    box-shadow: 0 2px 5px rgba(0,0,0,0.08);
  }
</style>

<div style="text-align:center; background: linear-gradient(135deg, #f0f7ff 0%, #e0f2fe 50%, #bae6fd 100%); padding:18px; border-radius:12px; margin-bottom:25px; color: #0369a1; font-family: 'Montserrat', sans-serif; box-shadow: 0 4px 12px rgba(0,0,0,0.03);">
  <h2 style="font-size:1.6em; margin:0; border-bottom: none; text-decoration: none; color: #0c4a6e;">
    👋 Welcome to <span style="color:#0284c7;">Rui Li</span>'s Homepage
  </h2>
</div>

## 🧑‍🎓 About Me

My name is Rui Li. I am currently a second-year PhD candidate in Renmin University of China, supervised by [Prof. Xu Chen](https://scholar.google.com/citations?user=loPoqy0AAAAJ&hl=en&oi=ao). Before embarking on my PhD journey, I received my BSc and MSc degrees in Computer Science at Dalian University of Technology, under the guidance of [Prof. Yanming Shen](https://scholar.google.com/citations?user=MvlgpWcAAAAJ&hl=en&oi=ao). My current research mainly focuses on Self-Evolving LLM Agents and Retrieval-Augmented Generation. I also maintain a strong interest in GNNs and Knowledge Graphs, particularly their interactions with LLM systems.

## 🗞️ News

- 🎉🎉 Two papers about LLM memory have been accepted by **NeurIPS 2025**.
- 🎉 One paper about RAG has been accepted by **KDD 2025**.
- 🎉 One paper about KG has been accepted by **ICML 2024**.
- 🎉 One paper about KG has been accepted by **ACL 2023**.
- 🎉🎉 Two papers about KG and GNN have been accepted by **ICML 2022**.

<div style="background-color: #fffbeb; border-left: 4px solid #f59e0b; padding: 12px 18px; margin: 25px 0; border-radius: 4px;">
  <p style="color: #92400e; margin: 0; font-size: 0.95em;">💡 I am currently seeking internship opportunities related to <b>Self-Evolving Agent/RAG Systems</b>. Please feel free to contact me if you are interested in my research or background.</p>
</div>

## 🧑‍💻 Internship Experiences

- **Huawei Noah's Ark Lab** (Aug. 2024 – Oct. 2025)  
  Worked on LLM agentic memory and self-bootstrapping retrieval-augmented generation.

- **Microsoft Research Asia** (Oct. 2021 – Apr. 2023)  
  Worked on knowledge representation learning and joint training of GNNs & LMs.

## 📚 Selected Publications

<div class="pub-list">

* **CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension** **Rui Li**, Zeyu Zhang, Xiaohe Bo, Zihang Tian, Xu Chen, Quanyu Dai, Zhenhua Dong, Ruiming Tang  
  *NeurIPS 2025* [📄 Paper](https://arxiv.org/abs/2510.05520) [💻 Code](https://github.com/rui9812/CAM)
  
* **KnowTrace: Bootstrapping Iterative Retrieval-Augmented Generation with Structured Knowledge Tracing** **Rui Li**, Quanyu Dai, Zeyu Zhang, Xu Chen, Zhenhua Dong, Ji-Rong Wen  
  *KDD 2025* [📄 Paper](https://arxiv.org/pdf/2505.20245) [💻 Code](https://github.com/rui9812/KnowTrace)

* **Generalizing Knowledge Graph Embedding with Universal Orthogonal Parameterization** **Rui Li**, Chaozhuo Li, Yanming Shen, Zeyu Zhang, Xu Chen  
  *ICML 2024* [📄 Paper](https://arxiv.org/pdf/2405.08540) [💻 Code](https://github.com/rui9812/GoldE)

* **To Copy Rather Than Memorize: A Vertical Learning Paradigm for Knowledge Graph Completion** **Rui Li**, Xu Chen, Chaozhuo Li, Yanming Shen, Jianan Zhao, Yujing Wang, Weihao Han, Hao Sun, Weiwei Deng, Qi Zhang, Xing Xie  
  *ACL 2023 Main Conference* [📄 Paper](https://arxiv.org/pdf/2305.14126) [💻 Code](https://github.com/rui9812/VLP)

* **HousE: Knowledge Graph Embedding with Householder Parameterization** **Rui Li**, Jianan Zhao, Chaozhuo Li, Di He, Yiqi Wang, Yuming Liu, Hao Sun, Senzhang Wang, Weiwei Deng, Yanming Shen, Xing Xie, Qi Zhang  
  *ICML 2022* [📄 Paper](https://proceedings.mlr.press/v162/li22ab/li22ab.pdf) [💻 Code](https://github.com/rui9812/HousE)

* **A New Perspective on the Effects of Spectrum in Graph Neural Networks** Mingqi Yang, Yanming Shen, **Rui Li**, Heng Qi, Qiang Zhang, Baocai Yin  
  *ICML 2022* [📄 Paper](https://proceedings.mlr.press/v162/yang22n/yang22n.pdf) [💻 Code](https://github.com/qslim/gnn-spectrum)

</div>

## 🏆 Awards

- Outstanding Innovative Talents Cultivation Programs, Renmin University of China, 2024.
- Outstanding Master's Thesis in Liaoning Province, 2023.
- National Scholarship for Postgraduate Students, 2022.
- Outstanding Graduate Student, Dalian University of Technology, 2022.
- Outstanding Undergraduate Graduate, Dalian University of Technology, 2020.
- First-class Academic Scholarship, Dalian University of Technology, 2017-2019.

---

<div style="text-align: center; margin-top: 50px;">
  <script type="text/javascript" id="clustrmaps" 
    src="//clustrmaps.com/map_v2.js?d=rExufzDkijQ4_HMmB45Q83dI6zdMP7Lcp9TTwd-MUJA&cl=ffffff&w=320&t=tt">
  </script>
</div>
